<template>
    <footer class="footer has-cards">


        <div class="container">


            <div class="container">
                <div class="row row-grid align-items-center ">
                    <div class=" row col-lg-6">
                        <div class="col-lg-12">
                            <div class="row row-grid align-items-center my-md">
                                <div class=" row col-lg-12">
                                    <div class="col-lg-12  ">
                                        <i class="fa fa-map-marker fa-2x" aria-hidden="true"></i> 
                                        Quito – Ecuador
                                    </div>

                                    <div class="col-lg-12 mt-3">
                                        <i class="fa fa-mobile fa-2x" type="success"></i> 0983697453
                                    </div>

                                     <div class="col-lg-12 mt-3">
                                        <i class="fa fa-envelope-o" aria-hidden="true"></i>ptambo@pt-consultores.com 
                                    </div>

                                      
                                </div>
                            </div>
                        </div>


                        <div class="col-lg-12 text-lg-center btn-wrapper my-3">
                            <a target="_blank" rel="noopener" href="https://twitter.com/creativetim"
                                class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                                data-original-title="Follow us">
                                <i class="fa fa-twitter"></i>
                            </a>
                            <a target="_blank" rel="noopener" href="https://www.facebook.com/creativetim"
                                class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                                data-original-title="Like us">
                                <i class="fa fa-facebook-square"></i>
                            </a>
                            
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
