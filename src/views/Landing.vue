<template>
    <div>
        <hero></hero>
        <section class="section section-lg fade-in-section">
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
                                En PT Consultores, somos un equipo de profesionales con amplia experiencia en los
                                sectores
                                industrial,
                                de construcción, manufactura y servicios.
                                Nos especializamos en ofrecer soluciones integrales en Seguridad,
                                Salud Ocupacional y Producción Industrial, cumpliendo la normativa legal vigente y
                                garantizando la optimización de recursos para nuestros clientes.
                            </p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">Asesoramos, capacitamos y fortalecemos tu gestión empresarial.
                                        </h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="fa fa-heartbeat"></badge>
                                        <h6 class="mb-0">Seguridad, salud y ambiente con excelencia técnica.</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Impulsamos eficiencia, prevención y sostenibilidad.</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            <br><br>
        </section>

        <div class="position-relative section-sm fade-in-section">
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
                <div class="container shape-container d-flex">
                    <div class="row justify-content-center">
                        <div class="container">
                            <h1 class="display-3  text-white">
                                Nuestros Servicios Principales
                            </h1>
                            <br>
                            <div class="row justify-content-center">
                                <div class="col-lg-12">
                                    <div class="row row-grid">
                                        <div class="col-lg-4" style="padding-bottom: 3rem;">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="primary" rounded class="mb-4">
                                                    <img src="img/consultoria/seguridadYsalud.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>

                                                <img src="img/imagenes/seguridadYSalud.webp" class="img-fluid">
                                                <h6 class="text-primary text-uppercase"> Sistema de Gestión en Seguridad
                                                    y
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
                                          <!--       <base-button tag="a" href="#" type="primary" class="mt-4">
                                                    Leer Más
                                                </base-button> -->
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
                                              <!--   <base-button tag="a" href="#" type="success" class="mt-4">
                                                    Leer más
                                                </base-button> -->
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
                                                    <li>Implementación y auditoría de sistemas de gestión basados en
                                                        normas
                                                        ISO (9001, 14001, 45001)</li>
                                                    <li>Integración de procesos de calidad, seguridad y medio ambiente
                                                    </li>
                                                    <li>Acompañamiento técnico en mejora continua y cumplimiento
                                                        normativo
                                                    </li>
                                                </ul>
                                                <div>
                                                    <badge type="warning" rounded>licencias</badge>
                                                    <badge type="warning" rounded>mitigación</badge>
                                                    <badge type="warning" rounded>residuos</badge>
                                                </div>
                                         <!--        <base-button tag="a" href="#" type="warning" class="mt-4">
                                                    Leer más
                                                </base-button> -->
                                            </card>
                                        </div>
                                    </div>
                                </div>

                                <div class="col-lg-12">
                                    <div class="row row-grid">

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="info" rounded class="mb-4">
                                                    <img src="img/consultoria/industria.svg" style="svg"
                                                        class="img-fluid">
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
                                           <!--      <base-button tag="a" href="#" type="info" class="mt-4">
                                                    Leer Más
                                                </base-button> -->
                                            </card>
                                        </div>

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="warning" rounded class="mb-4">
                                                    <img src="img/consultoria/equiposProteccion.svg" style="svg"
                                                        class="img-fluid">
                                                </icon>
                                                <img src="img/imagenes/equiposProteccion.jpg" class="img-fluid">
                                                <h6 class="text-warning text-uppercase">Venta y Asesoramiento en Equipos
                                                    de
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
                                              <!--   <base-button tag="a" href="#" type="warning" class="mt-4">
                                                    Leer más
                                                </base-button> -->
                                            </card>
                                        </div>

                                        <div class="col-lg-4">
                                            <card class="border-0" hover shadow body-classes="py-5">
                                                <icon type="light" rounded class="mb-4">
                                                    <img src="img/consultoria/regulacionGestionAmbiental.svg"
                                                        style="svg" class="img-fluid">
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
                                            <!--     <base-button tag="a" href="#" type="light" class="mt-4">
                                                    Leer más
                                                </base-button> -->
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

        <section class="section section-sm section-shaped  my-0 fade-in-section " style="transform: translateY(-17px); ">
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
                                    <icon name="fa fa-leaf" gradient="primary" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-primary">SEGURIDAD Y MEDIO AMBIENTE</h5>
                                    <base-modal ref="modal5" title="SEGURIDAD Y MEDIO AMBIENTE" button-text="Leer Más"
                                        text-color="text-primary" button-type="primary" @confirm="verDetalles">
                                        <p>
                                            Promover una cultura de prevención de riesgos laborales y de responsabilidad
                                            ambiental,
                                            mediante la implementación de prácticas seguras y sostenibles que aseguren
                                            el
                                            bienestar
                                            del trabajador, la protección del entorno y el cumplimiento de la normativa
                                            vigente.
                                        </p>
                                    </base-modal>
                                </div>
                            </div>
                        </card>

                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="fa fa-cogs" gradient="info" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-info">EFICIENCIA Y PRODUCTIVIDAD</h5>
                                    <base-modal ref="modal4" title="EFICIENCIA Y PRODUCTIVIDAD" button-text="Leer Más"
                                        text-color="text-info" button-type="info" @confirm="verDetalles">
                                        <p>
                                            Fomentar la optimización de procesos industriales y administrativos,
                                            aplicando metodologías de mejora continua, planificación estratégica y
                                            control
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
                                    <icon name="fa fa-bar-chart" gradient="success" color="white" shadow rounded>
                                    </icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">POSICIONAMIENTO</h5>
                                    <base-modal ref="modal1" title="POSICIONAMIENTO" button-text="Leer Más"
                                        text-color="text-success" button-type="success" @confirm="guardarInfo">
                                        <p>Ser reconocidos a nivel nacional como una empresa líder en asesoría y
                                            capacitación
                                            técnica dentro de los campos de seguridad, salud laboral, ambiente y
                                            producción
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
                                    <icon name="fa fa-line-chart" gradient="warning" color="white" shadow rounded>
                                    </icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">CRECIMIENTO</h5>
                                    <base-modal ref="modal2" title="CRECIMIENTO" button-text="Leer Más"
                                        text-color="text-warning" button-type="warning" @confirm="confirmarAccion">
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
                                    <icon name="fa fa-usd" gradient="light" color="white" shadow rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-light">RENTABILIDAD</h5>
                                    <!--  -->
                                    <base-modal ref="modal3" title="RENTABILIDAD" button-text="Leer Más"
                                        button-type="light" text-color="text-light" @confirm="verDetalles">
                                        <p>
                                            Asegurar la eficiencia económica de los proyectos desarrollados,
                                            optimizando recursos y generando soluciones que incrementen la productividad
                                            y
                                            competitividad
                                            de nuestros clientes, siempre bajo principios de responsabilidad social y
                                            sostenibilidad
                                            ambiental.
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

        <section class="section section-sm fade-in-section">
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-default">Nuestra experiencia se refleja en:</h2>

                    </div>
                </div>
                <div class="row row-grid mt-5">

                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0 floating">
                        <div class="px-4">

                            <div class="rounded-circle img-center img-fluid shadow shadow-lg--hover "
                                style="display: flex; justify-content: center; align-items: center;  max-width: 180px; height: 180px; background-color: #444444;">
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
                                style="display: flex; justify-content: center; align-items: center; max-width: 180px; height: 180px; background-color: #136c34;">
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
                                style="display: flex; justify-content: center; align-items: center; max-width: 180px; height: 180px; background-color: #b178cb;">
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
                                style="display: flex; justify-content: center; align-items: center; max-width: 180px; height: 180px; background-color: #4c1824;">

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
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">

                        <p class="lead text-default">“Más de una década acompañando a empresas ecuatorianas en el
                            cumplimiento
                            normativo y la mejora continua en seguridad y ambiente.”</p>
                    </div>
                </div>

            </div>
        </section>



        <a href="https://api.whatsapp.com/send?phone=593983697453&text=Hola Necesito mas informacion"
            class="whatsapp-float" target="_blank" title="Chatea con nosotros en WhatsApp">
            <i class="fa fa-whatsapp" aria-hidden="true"></i>
            <span class="whatsapp-tooltip">¿Tienes alguna pregunta?</span>
        </a>
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
    mounted() {
        const sections = document.querySelectorAll('.fade-in-section');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, { threshold: 0.2 });

        sections.forEach(section => observer.observe(section));
    }
};
</script>
<style>
.modal-dialog {
    display: flex !important;
    align-items: center !important;
    /* centra vertical */
    min-height: 100vh !important;
    /* ocupa toda la altura de la ventana */
}

.whatsapp-float {
    position: fixed;
    width: 60px;
    height: 60px;
    bottom: 250px;
    right: 25px;
    background-color: #25d366;
    color: white;
    border-radius: 50%;
    text-align: center;
    font-size: 32px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
    animation: pulse 1s infinite;
}

.whatsapp-float:hover {
    background-color: #1ebe57;
    transform: scale(1.1);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4);
    animation: none;
}

.whatsapp-tooltip {
    position: absolute;
    right: 70px;
    /* distancia del icono */
    background-color: #333;
    color: #fff;
    padding: 6px 10px;
    border-radius: 8px;
    font-size: 14px;
    white-space: nowrap;
    opacity: 0;
    pointer-events: none;
    transform: translateY(0);
    transition: opacity 0.3s ease, transform 0.3s ease;
}

.whatsapp-float:hover .whatsapp-tooltip {
    opacity: 1;
    transform: translateY(-5px);
}

/* --- Animación de pulso --- */
@keyframes pulse {
    0% {
        transform: scale(1);
        box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
    }

    50% {
        transform: scale(1.1);
        box-shadow: 0 4px 16px rgba(0, 0, 0, 0.4);
    }

    100% {
        transform: scale(1);
        box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
    }
}

.fade-in-section {
    opacity: 0;
    transform: translateY(40px);
    transition: all 0.8s ease-out;
}

.fade-in-section.visible {
    opacity: 1;
    transform: translateY(0);
}
</style>