<template>
    <div>
        <hero></hero>
        <section class="section section-sm">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/imagenes/equipo2.webp" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-single-02" class="mb-5" size="lg" type="success" shadow rounded></icon>

                            <h2>Quiénes Somos</h2>
                            <h5>Experiencia y Compromiso con la Seguridad Laboral</h5>
                            <p>
                                En PT Consultores, somos un equipo de profesionales con amplia experiencia en los sectores
                                industrial,
                                de construcción, manufactura y servicios.
                                Nos especializamos en ofrecer soluciones integrales en Seguridad,
                                Salud Ocupacional y Producción Industrial, cumpliendo la normativa legal vigente y
                                garantizando la optimización de recursos para nuestros clientes.
                            </p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Carefully crafted components</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">Amazing page examples</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">Super friendly support team</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <div class="position-relative section-sm">
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex" style="transform: translateY(-280px); ">
                    <div class="row justify-content-center">
                        <div class="container">
                            <h1 class="display-3  text-white">
                                Nuestros Servicios Principales
                            </h1>
                            <br>
                            <div class="row justify-content-center">
                                <div class="col-lg-12">
                                    <div class="row row-grid">
                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="primary" rounded class="mb-4">
                                                    <img src="img/consultoria/seguridadYsalud.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>

                                                <img src="img/imagenes/seguridadYSalud.webp" class="img-fluid">
                                                <h6 class="text-primary text-uppercase"> Sistema de Gestión en Seguridad y
                                                    Salud Ocupacional
                                                </h6>
                                                <ul class="description mt-3">
                                                    <li>Elaboración de matrices de riesgos laborales</li>
                                                    <li>Planes y reglamentos de seguridad</li>
                                                    <li>Capacitaciones preventivas y emergentes</li>
                                                    <li>Evaluaciones psicosociales y ocupacionales</li>
                                                </ul>
                                                <div>
                                                    <badge type="primary" rounded>riesgos</badge>
                                                    <badge type="primary" rounded>seguridad</badge>
                                                    <badge type="primary" rounded>Evaluaciones</badge>
                                                </div>
                                                <base-button tag="a" href="#" type="primary" class="mt-4">
                                                    Leer Más
                                                </base-button>
                                            </card>
                                        </div>

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="success" rounded class="mb-4">
                                                    <img src="img/consultoria/certificado.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>

                                                <img src="img/imagenes/certificados.png" class="img-fluid">
                                                <h6 class="text-success text-uppercase">Certificación en Competencias
                                                    Laborales</h6>
                                                <ul class="description mt-3">
                                                    <li>Formación en prevención de riesgos laborales (Registro SENESCYT)
                                                    </li>
                                                    <li>Acompañamiento integral para la certificación</li>
                                                    <li>Capacitación en normativa vigente y análisis de riesgos</li>
                                                </ul>
                                                <div>
                                                    <badge type="success" rounded>certificado</badge>
                                                    <badge type="success" rounded>capacitación</badge>
                                                    <badge type="success" rounded>normativa</badge>
                                                </div>
                                                <base-button tag="a" href="#" type="success" class="mt-4">
                                                    Leer más
                                                </base-button>
                                            </card>
                                        </div>

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="warning" rounded class="mb-4">
                                                    <img src="img/consultoria/gestionAmbiental.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>

                                                <img src="img/imagenes/gestionIntegral.jpg" class="img-fluid">
                                                <h6 class="text-warning text-uppercase">
                                                    Sistemas de Gestión Integral
                                                </h6>
                                                <ul class="description mt-3">
                                                    <li>Implementación y auditoría de sistemas de gestión basados en normas
                                                        ISO (9001, 14001, 45001)</li>
                                                    <li>Integración de procesos de calidad, seguridad y medio ambiente</li>
                                                    <li>Acompañamiento técnico en mejora continua y cumplimiento normativo
                                                    </li>
                                                </ul>
                                                <div>
                                                    <badge type="warning" rounded>licencias</badge>
                                                    <badge type="warning" rounded>mitigación</badge>
                                                    <badge type="warning" rounded>residuos</badge>
                                                </div>
                                                <base-button tag="a" href="#" type="warning" class="mt-4">
                                                    Leer más
                                                </base-button>
                                            </card>
                                        </div>
                                    </div>
                                </div>

                                <div class="col-lg-12" style="transform: translateY(30px); ">
                                    <div class="row row-grid">

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="info" rounded class="mb-4">
                                                    <img src="img/consultoria/industria.svg" style="svg" class="img-fluid">
                                                </icon>
                                                <img src="img/imagenes/confeccionIndustrial.jpg" class="img-fluid">
                                                <h6 class="text-info text-uppercase">
                                                    Producción y Confección Textil Industrial
                                                </h6>
                                                <ul class="description mt-3">
                                                    <li>Optimización de procesos productivos</li>
                                                    <li>Balanceo de líneas y tiempos</li>
                                                    <li>Implementación de sistemas “Justo a Tiempo”</li>
                                                </ul>
                                                <div>
                                                    <badge type="info" rounded>procesos</badge>
                                                    <badge type="info" rounded>sistemas</badge>
                                                    <badge type="info" rounded>textil</badge>
                                                </div>
                                                <base-button tag="a" href="#" type="info" class="mt-4">
                                                    Leer Más
                                                </base-button>
                                            </card>
                                        </div>

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="warning" rounded class="mb-4">
                                                    <img src="img/consultoria/equiposProteccion.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>
                                                <img src="img/imagenes/equiposProteccion.jpg" class="img-fluid">
                                                <h6 class="text-warning text-uppercase">Venta y Asesoramiento en Equipos de
                                                    Protección Personal</h6>
                                                <ul class="description mt-3">
                                                    <li>Selección y cotización de EPP según riesgo laboral </li>
                                                    <li>Comercialización de marcas certificadas</li>
                                                </ul>
                                                <div>
                                                    <badge type="warning" rounded>cotización</badge>
                                                    <badge type="warning" rounded>riesgo</badge>
                                                    <badge type="warning" rounded>laboral</badge>
                                                </div>
                                                <base-button tag="a" href="#" type="warning" class="mt-4">
                                                    Leer más
                                                </base-button>
                                            </card>
                                        </div>

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="light" rounded class="mb-4">
                                                    <img src="img/consultoria/regulacionGestionAmbiental.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>

                                                <img src="img/imagenes/regulacionAmbiental.jpg" class="img-fluid">
                                                <h6 class="text-light text-uppercase">
                                                    Regularización y Gestión Ambiental
                                                </h6>
                                                <ul class="description mt-3">
                                                    <li>Certificados, registros y licencias ambientales</li>
                                                    <li>Planes de manejo y mitigación</li>
                                                    <li>Gestión integral de residuos sólidos y efluentes</li>
                                                </ul>
                                                <div>
                                                    <badge type="light" rounded>licencias</badge>
                                                    <badge type="light" rounded>mitigación</badge>
                                                    <badge type="light" rounded>residuos</badge>
                                                </div>
                                                <base-button tag="a" href="#" type="light" class="mt-4">
                                                    Leer más
                                                </base-button>
                                            </card>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

        </div>

        <section class="section section-lg section-shaped my-0 overflow-hidden" style="transform: translateY(-350px); ">
            <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <icon size="lg" class="bg-gradient-white" color="primary" shadow rounded>
                                    <i class="fa fa-sitemap bg-gradient-white" color="primary" aria-hidden="true"></i>
                                </icon>

                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Nuestros Objetivos</h4>
                            </div>
                        </div>

                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">POSICIONAMIENTO</h5>
                                    <base-modal ref="modal1" title="POSICIONAMIENTO" button-text="Leer Más"
                                        button-type="primary" @confirm="guardarInfo">
                                        <p>Ser reconocidos a nivel nacional como una empresa líder en asesoría y
                                            capacitación
                                            técnica dentro de los campos de seguridad, salud laboral, ambiente y producción
                                            industrial,
                                            fortaleciendo la confianza y satisfacción de nuestros clientes mediante
                                            servicios
                                            oportunos,
                                            eficientes y de alta calidad.</p>
                                    </base-modal>
                                </div>
                            </div>
                        </card>

                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">CRECIMIENTO</h5> 
                                    <base-modal ref="modal2" title="CRECIMIENTO" button-text="Leer Más"
                                        button-type="warning" @confirm="confirmarAccion">
                                        <p>
                                            Impulsar un crecimiento sostenible y continuo, tanto en la capacidad técnica
                                            del
                                            equipo humano
                                            como en la cobertura de servicios ofrecidos, consolidando alianzas
                                            estratégicas que
                                            promuevan
                                            la mejora constante y la innovación dentro de los procesos industriales y
                                            empresariales.
                                        </p>
                                    </base-modal>
                                </div>
                            </div>
                        </card>

                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">RENTABILIDAD</h5>
                                    <!--  -->
                                    <base-modal ref="modal3" title="RENTABILIDAD" button-text="Leer Más"
                                        button-type="success" @confirm="verDetalles">
                                        <p>
                                            Asegurar la eficiencia económica de los proyectos desarrollados,
                                            optimizando recursos y generando soluciones que incrementen la productividad y
                                            competitividad
                                            de nuestros clientes, siempre bajo principios de responsabilidad social y
                                            sostenibilidad
                                            ambiental.
                                        </p>
                                    </base-modal>
                                </div>
                            </div>
                        </card>

                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">EFICIENCIA Y PRODUCTIVIDAD</h5> 
                                    <base-modal ref="modal4" title="EFICIENCIA Y PRODUCTIVIDAD" button-text="Leer Más"
                                        button-type="success" @confirm="verDetalles">
                                        <p>
                                            Fomentar la optimización de procesos industriales y administrativos,
                                            aplicando metodologías de mejora continua, planificación estratégica y control
                                            de
                                            producción.
                                            El objetivo es garantizar resultados medibles en calidad,
                                            costo, entrega y seguridad.
                                        </p>
                                    </base-modal>
                                </div>
                            </div>
                        </card>

                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">SEGURIDAD Y MEDIO AMBIENTE</h5>
                                    <base-modal ref="modal5" title="SEGURIDAD Y MEDIO AMBIENTE" button-text="Leer Más"
                                        button-type="info" @confirm="verDetalles">
                                        <p>
                                            Promover una cultura de prevención de riesgos laborales y de responsabilidad
                                            ambiental,
                                            mediante la implementación de prácticas seguras y sostenibles que aseguren el
                                            bienestar
                                            del trabajador, la protección del entorno y el cumplimiento de la normativa
                                            vigente.
                                        </p>
                                    </base-modal>
                                </div>
                            </div>
                        </card>


                    </div>
                </div>
            </div>
            <br><br><br><br><br><br>
        </section>

        <section class="section section-sm" style="transform: translateY(-250px); ">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">Nuestra experiencia se refleja en:</h2>

                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0 floating">
                        <div class="px-4">

                            <div class="rounded-circle img-center img-fluid shadow shadow-lg--hover "
                                style="display: flex; justify-content: center; align-items: center; height: 180px; background-color: #444444;">
                                <i class="fa fa-calendar fa-4x" aria-hidden="true" style="color: white;"></i>
                            </div>


                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-4 h4">+10 años </span>
                                    <small class="h5 text-muted mb-1">de experiencia técnica</small>
                                </h5>

                            </div>
                        </div>
                    </div>

                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0 floating">
                        <div class="px-4">
                            <div class="rounded-circle img-center img-fluid shadow shadow-lg--hover "
                                style="display: flex; justify-content: center; align-items: center; height: 180px; background-color: #136c34;">
                                <i class="fa fa-briefcase fa-4x" aria-hidden="true" style="color: white;"></i>
                            </div>

                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-4 h4">+150 proyectos</span>
                                    <small class="h5 text-muted">ejecutados a nivel nacional</small>
                                </h5>

                            </div>
                        </div>
                    </div>

                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0 floating">
                        <div class="px-4">
                            <div class="rounded-circle img-center img-fluid shadow shadow-lg--hover "
                                style="display: flex; justify-content: center; align-items: center; height: 180px; background-color: #b178cb;">
                                <i class="fa fa-users fa-4x" aria-hidden="true" style="color: white;"></i>
                            </div>

                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-4 h4">+1,200 profesionales</span>
                                    <small class="h5 text-muted">capacitados constantemente</small>
                                </h5>

                            </div>
                        </div>
                    </div>

                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0 floating">
                        <div class="px-4">
                            <div class="rounded-circle img-center img-fluid shadow shadow-lg--hover  "
                                style="display: flex; justify-content: center; align-items: center; height: 180px; background-color: #4c1824;">

                                <i class="ni ni-building shadow rounded" style="font-size: 80px; color: white; "></i>
                            </div>

                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-4 h4">+80 empresas</span>
                                    <small class="h5 text-muted">asesoradas en distintos sectores</small>
                                </h5>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>


        <section class="section bg-secondary ">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/img-1-1200x1000.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                    class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">Design System</h4>
                                <p class="lead text-italic text-white">The Arctic Ocean freezes every winter and much of
                                    the sea-ice then thaws every summer, and that process will continue whatever
                                    happens.</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="ni ni-settings" class="mb-5" size="lg" type="warning" shadow rounded></icon>

                            <h3>Our customers</h3>
                            <p class="lead">Don't let your uses guess by attaching tooltips and popoves to any element.
                                Just make sure you enable them first via JavaScript.</p>
                            <p>The kit comes with three pre-built pages to help you get started faster. You can change
                                the text and images and you're good to go.</p>
                            <p>The kit comes with three pre-built pages to help you get started faster. You can change
                                the text and images and you're good to go.</p>
                            <a href="#" class="font-weight-bold text-warning mt-5">A beautiful UI Kit for impactful
                                websites</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>



        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="warning" no-body shadow-size="lg" class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">We made website building easier for you.</h3>
                                <p class="lead text-white mt-3">I will be the leader of a company that ends up being
                                    worth billions of dollars, because I got the answers. I understand culture.</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="https://www.creative-tim.com/product/vue-argon-design-system"
                                    type="white" block size="lg">
                                    Download Vue
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>

        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Build something</h2>
                        <p class="lead text-white">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record low maximum sea ice extent
                            tihs year down to low ice.</p>
                    </div>
                </div>
                <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <icon name="ni ni-settings" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Building tools</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-ruler-pencil" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Grow your market</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-atom" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Launch time</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                </div>
            </div>
        </section>


        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 text-center">
                        <h2 class="display-3">Do you love this awesome
                            <span class="text-success">Design System for Bootstrap 4?</span>
                        </h2>
                        <p class="lead">Cause if you do, it can be yours for FREE. Hit the button below to navigate to
                            Creative Tim where you can find the Design System in HTML. Start a new project or give an
                            old Bootstrap project a new look!</p>
                        <div class="btn-wrapper">
                            <a href="https://www.creative-tim.com/product/vue-argon-design-system"
                                class="btn btn-primary mb-3 mb-sm-0">Download Vue</a>
                        </div>
                        <div class="text-center">
                            <h4 class="display-4 mb-5 mt-5">Available on these technologies</h4>
                            <div class="row justify-content-center">
                                <div class="col-lg-2 col-4">
                                    <a href="https://getbootstrap.com/" target="_blank" data-toggle="tooltip"
                                        data-original-title="Bootstrap 4 - Most popular front-end component library">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/bootstrap.jpg'"
                                            class="img-fluid">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="https://www.sketchapp.com/" target="_blank" data-toggle="tooltip"
                                        data-original-title="[Coming Soon] Sketch - Digital design toolkit">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/sketch.jpg'"
                                            class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="https://www.adobe.com/products/photoshop.html" data-toggle="tooltip"
                                        data-original-title="[Coming Soon] Adobe Photoshop - Software for digital images manipulation">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/ps.jpg'"
                                            class="img-fluid  opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="https://vuejs.org/" target="_blank" data-toggle="tooltip"
                                        data-original-title="Vue.js - The progressive javascript framework">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/vue.jpg'"
                                            class="img-fluid">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="https://angularjs.org/" target="_blank" data-toggle="tooltip"
                                        data-original-title="[Coming Soon] Angular - One framework. Mobile &amp; desktop">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/angular.jpg'"
                                            class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="https://reactjs.org/" target="_blank" data-toggle="tooltip"
                                        data-original-title="[Coming Soon] React - A JavaScript library for building user interfaces">
                                        <img v-lazy="'https://s3.amazonaws.com/creativetim_bucket/tim_static_images/presentation-page/react.jpg'"
                                            class="img-fluid opacity-5">
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <div class="row">






            <!-- Modal 2 -->


            <!-- Modal 3 -->
            <div class="col-md-4">

            </div>

        </div>

    </div>
</template>

<script>
import Hero from "./components/Hero";
import BaseModal from "./components/BaseModal";
export default {
    name: "home",
    components: {
        Hero,
        BaseModal
    },
    methods: {
        guardarInfo() {
            console.log("Información guardada correctamente ✅");
        },
        confirmarAccion() {
            console.log("Acción confirmada ⚠️");
        },
        verDetalles() {
            console.log("Mostrando detalles del proceso 📋");
        },
    },
};
</script>
<style  >
.modal-dialog {
    display: flex !important;
    align-items: center !important;
    /* centra vertical */
    min-height: 100vh;
    /* ocupa toda la altura de la ventana */
}
</style>