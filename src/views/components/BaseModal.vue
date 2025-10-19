<template>
  <div>
    <base-button
      v-if="showTriggerButton"
      block
      :type="buttonType"
      class="mb-3"
      @click="isVisible = true"
    >
      {{ buttonText }}
    </base-button>

    <modal :show.sync="isVisible" :gradient="gradient" :modal-classes="modalClasses">
      <!-- Encabezado -->
      <h6 slot="header" class="modal-title">
        {{ title }}
      </h6>

      <!-- Cuerpo (slot opcional) -->
      <div>
        <slot>
          {{ body }}
        </slot>
      </div>

      <!-- Pie del modal -->
      <template slot="footer">
        <slot name="footer">
          <base-button type="primary" @click="confirmAction">
            {{ confirmText }}
          </base-button>
          <base-button type="link" class="ml-auto" @click="isVisible = false">
            {{ closeText }}
          </base-button>
        </slot>
      </template>
    </modal>
  </div>
</template>

<script>
import Modal from "@/components/Modal.vue";
import { nextTick } from "vue";
export default {
  name: "BaseModal",
  components: {
    Modal,
  },
  props: {
    title: {
      type: String,
      default: "Default Title",
    },
    body: {
      type: String,
      default: "",
    },
    confirmText: {
      type: String,
      default: "Guardar",
    },
    closeText: {
      type: String,
      default: "Cerrar",
    },
    buttonText: {
      type: String,
      default: "Abrir modal",
    },
    buttonType: {
      type: String,
      default: "primary",
    },
    gradient: {
      type: String,
      default: "",
    },
    modalClasses: {
      type: String,
      default: "",
    },
    showTriggerButton: {
      type: Boolean,
      default: true,
    },
  },
  data() {
    return {
      isVisible: false,
    };
  },
   watch: {
  isVisible(newVal) {
    if (newVal) {
      this.$nextTick(() => {
        const modalDialog = this.$el.querySelector(".modal-dialog");
        if (modalDialog) {
          modalDialog.scrollIntoView({ behavior: "smooth", block: "start" });
        }
      });
    }
  },
},
  methods: {
    confirmAction() {
      this.$emit("confirm"); // Emite un evento al confirmar
      this.isVisible = false;
    },
  },
};
</script>
