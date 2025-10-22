<template>
    <footer class="footer has-cards ">
        

        <div class="container ">


            <div class="container">
                <div class="row row-grid align-items-center ">
                    <div class=" row col-lg-6">
                        <div class="col-lg-12 text-lg-center btn-wrapper my-3">
                            <a target="_blank" rel="noopener" href="https://twitter.com/creativetim"
                                class="btn btn-neutral btn-icon-only  btn-round btn-lg" data-toggle="tooltip"
                                data-original-title="Follow us">
                                <i class="fa fa-linkedin-square fa-3x"></i>
                            </a>
                            <a target="_blank" rel="noopener" href="https://www.facebook.com/creativetim"
                                class="btn btn-neutral btn-icon-only   btn-round btn-lg" data-toggle="tooltip"
                                data-original-title="Like us">
                                <i class="fa fa-facebook-square fa-3x"></i>
                            </a>

                        </div>

                        <div class="col-lg-12">
                            <div class="row row-grid align-items-center my-md">
                                <div class=" row col-lg-12">
                                    <div class="col-lg-12  " style="font-size: 18px;">
                                        <i class="fa fa-map-marker fa-2x  " aria-hidden="true"
                                            style="margin-right: 20px; color: #4c1824;"></i>
                                        Quito – Ecuador
                                    </div>

                                    <div class="col-lg-12 mt-3" style="font-size: 18px;">
                                        <a href="https://api.whatsapp.com/send?phone=593983697453&text=Hola Necesito mas informacion"
                                            target="_blank" style="color: #525f7f;">
                                            <i class="fa fa-whatsapp fa-2x" type="success"
                                                style="margin-right: 15px; color: #25D366;"></i>
                                            0983697453
                                        </a>
                                    </div>


                                    <div class="col-lg-12 mt-3" style="font-size: 18px;">
                                        <i class="fa fa-envelope-o fa-2x" aria-hidden="true"
                                            style="margin-right: 15px; color: #b178cb;"></i>ptambo@pt-consultores.com
                                    </div>


                                </div>
                            </div>
                        </div>



                    </div>
                    <div class="col-lg-5">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Contactate con nosotros</h4>
                            <base-input class="mt-2" alternative placeholder="Nombres" addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative placeholder="Correo Electronico" addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-2">
                                <textarea class="form-control form-control-alternative" name="name" rows="4" cols="10"
                                    placeholder="Tu mensaje"></textarea>
                            </base-input>
                            <base-button type="default" round block size="md">
                                Contactar
                            </base-button>
                        </card>
                    </div>
                </div>

            </div>


            <hr>
            <div class="justify-content-center" style="text-align: center;">

                <div class="copyright">
                    &copy; 2025 Creado por PT Consultores
                </div>

            </div>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'app-footer',
    data() {
        return {
            year: new Date().getFullYear()
        }
    }
};
</script>
<style></style>
