<template>
  <main>

    <!-- ======= NOSOTROS ======= -->
    <section id="about" class="about">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>ACERCA DE NOSOTROS</h2>
          <p>Estudiantes de Espol</p>
        </div>

        <div class="row">
          <div class="col-lg-2">
            <div class="circle-container">
            <img src="@assets/img/joel.png" class="rounded-circle" alt="">
            </div>
          </div>

          <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3>JOEL ALVARADO JIMENEZ - Estudiante de Ingenieria en Computación.</h3>
            <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>joealalv@espol.edu.ec</span></li>
          </div>

          <!-- FIN DE JOEL -->
        </div>

        <div class="row">
          <div class="col-lg-2">
            <div class="circle-container">
            <img src="@assets/img/luis.png" class="rounded-circle" alt="">
            </div>
          </div>

            <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3>LUIS BAJAÑA FERNANDEZ - Estudiante de Ingenieria en Computación.</h3>
            <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>labajana@espol.edu.ec</span></li>

          </div><!-- FIN DE LUIS -->
        </div>

        <div class="row">
          <div class="col-lg-2">
            <div class="circle-container">
            <img src="@assets/img/sergio.png" class="rounded-circle" alt="">
            </div>
          </div>

            <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3>SERGIO BASURTO CEDEÑO - Estudiante de Ingenieria en Computación.</h3>
            <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>sbasurto@espol.edu.ec</span></li>

          </div><!-- FIN DE LUIS -->
        </div>

        <div class="row">
          <div class="col-lg-2">
            <div class="circle-container">
            <img src="@assets/img/lea.png" class="rounded-circle" alt="">
            </div>
          </div>

            <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3>LEA CORDOVA ANCHUNDIA - Estudiante de Ingenieria en Computación.</h3>
            <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>lealcord@espol.edu.ec</span></li>
          </div><!-- FIN DE LUIS -->
        </div>

        <div class="row">
          <div class="col-lg-2">
            <div class="circle-container">
            <img src="@assets/img/jefferson.png" class="rounded-circle" alt="">
            </div>
          </div>

            <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3>JEFFERSON ERAS LINDAO -Estudiante de Ingenieria en Computación.</h3>
            <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>jeras@espol.edu.ec</span></li>
          </div><!-- FIN DE LUIS -->
        </div>

        <div class="row">
          <div class="col-lg-2">
            <div class="circle-container">
            <img src="@assets/img/andres.png" class="rounded-circle" alt="">
            </div>
          </div>

            <div class="col-lg-8 pt-4 pt-lg-0 content">
            <h3>ANDRES MOSCOSO ESQUIVEL - Estudiante de Ingenieria en Computación.</h3>
            <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>aumoscos@espol.edu.ec</span></li>
            <p class="fst-italic">
              Biografia de Compañero2
            </p>
            <div class="row">

              <div class="col-lg-6">
                <p class="fst-italic">
                  Pegar Foto
                </p>
              </div>
            </div>
          </div><!-- FIN DE LUIS -->
        </div>



      </div>
    </section><!-- End NOSOTROS -->

    <!-- ======= PROTOTIPO ======= -->

    <section id="prototipo" class="prototipo">

      <div class="container" data-aos="fade-up">
        <section id="facts" class="facts">
          <div class="container" data-aos="fade-up">

            <div class="section-title">
              <h2>PROTOTIPO</h2>
              <p>Primera version del juego "BURGER"</p>
            </div>


            <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="@assets/protoDigital.png" class="d-block w-100" alt="Slide 1">
                </div>
                <div class="carousel-item">
                  <img src="@assets/proto1.png" class="d-block w-100" alt="Slide 2">
                </div>
                <div class="carousel-item">
                  <img src="@assets/proto.png" class="d-block w-100" alt="Slide 2">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>

          </div>
        </section><!-- End PROTOTIPO -->

      </div>
    </section><!-- End PROTOTIPO -->

    <!-- ======= PORTFOLIO ======= -->
    <section id="portfolio" class="portfolio section-bg">
      <div class="container" data-aos="fade-up">
        <div class="section-title">
          <h2>Portfolio</h2>
          <h3>- PROCESO DE IDEACION -</h3>
          <p>En esta parte se encuentra nuestro proceso, desde el proceso de ideacion hasta la idea final</p>
        </div>

        <div class="row">
          <div class="col-lg-12 d-flex justify-content-center" data-aos="fade-up" data-aos-delay="100">
            <ul ref="portfolioFilters" id="portfolio-flters">
              <li data-filter="*" class="filter-active">MATRIZ DE IDEAS</li>
              <li data-filter=".filter-app">TOP IDEAS</li>

            </ul>
          </div>
        </div>

        <div ref="portfolioContainer" class="row portfolio-container" data-aos="fade-up" data-aos-delay="200">

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea1.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>App 1</h4>
                <p>App</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea1.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="App 1"><i class="bx bx-plus"></i></a>
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea2.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Web 3</h4>
                <p>Web</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea2.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Web 3"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea3.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>App 2</h4>
                <p>App</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea3.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="App 2"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea4.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Card 2</h4>
                <p>Card</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea4.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Card 2"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea5.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Web 2</h4>
                <p>Web</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea5.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Web 2"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea6.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>App 3</h4>
                <p>App</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea6.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="App 3"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea7.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Card 1</h4>
                <p>Card</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea7.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Card 1"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea8.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Card 3</h4>
                <p>Card</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea8.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Card 3"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea9.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Web 3</h4>
                <p>Web</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea9.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Web 3"><i class="bx bx-plus"></i></a>

                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="@assets/ideas/idea10.jpeg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Web 3</h4>
                <p>Web</p>
                <div class="portfolio-links">
                  <a href="@assets/ideas/idea10.jpeg" data-gallery="portfolioGallery" class="portfolio-lightbox"
                    title="Web 3"><i class="bx bx-plus"></i>
                    </a>

                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </section>
    <!-- End PORTFOLIO -->

    <SeccionValidaciones />

    <!-- ======= SOBRE EL JUEGO ======= -->
    <section id="contact" class="contact">
      <div class="container" data-aos="fade-up">

        <div class="section-title">
          <h2>SKY BURGER</h2>
          <p>¡Bienvenido a "BurgerStack" - donde la emoción de Tetris se encuentra con la deliciosa creatividad de las hamburguesas! En este  juego, tu misión es construir las hamburguesas más deliciosas y altas que puedas, ¡mientras desafías tu destreza y velocidad!</p>
        </div>

          <h3>Objetivo del Juego:</h3>
          <p> Tu misión es construir la hamburguesa perfecta. A medida que juegas, verás un contador en la parte superior que representa tu hambre creciente. Debes apilar ingredientes rápidamente para satisfacer tu apetito y mantener el contador bajo control. ¡Pero cuidado, la velocidad aumenta con el tiempo, así que mantente ágil!</p>

          <h3>Mecánica del Juego:</h3>
          <p>Ingredientes Descendentes: Desde la parte superior de la pantalla, caerán diversos ingredientes de hamburguesas, como pan, carne, queso, lechuga, tomate, y más. Utiliza las teclas de dirección para desplazar y rotar cada pieza a medida que desciende.

Velocidad: Con el tiempo, la velocidad del juego puede ir aumentando, dependera de la dificultad, desafiándote a tomar decisiones rápidas y precisas. ¿Puedes mantener el ritmo y seguir construyendo hamburguesas perfectas a medida que la presión aumenta?

Ingredientes Especiales: Algunos ingredientes tienen habilidades especiales. Por ejemplo, un ingrediente puede eliminar una fila completa o congelar el contador de hambre por un breve período. Aprende a aprovechar estas habilidades para alcanzar puntuaciones más altas.</p>

        <h3>Desafíos y Logros:</h3>
        <p>A lo largo del juego, te enfrentarás a desafíos únicos que pondrán a prueba tu habilidad para construir hamburguesas en condiciones extraordinarias. Completa estos desafíos para desbloquear logros especiales y recompensas deliciosas, y lograr puntuaciones máximas.</p>  

        

      </div>
    </section><!-- End CONTACTO  -->


  </main>
  <footer id="footer">
    <div class="container">
      <h3>ESCUELA SUPERIROR POLITECNICA DEL LITORAL</h3>
      <p>Proyecto desarrollado para la materia "Desarrollo de Video Juegos" dictado por Pdh. Javier Tibau</p>

      <div class="copyright">
        &copy; Copyright <strong><span></span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you purchased the pro version. -->
        <!-- Licensing information: [license-url] -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/free-html-bootstrap-template-my-resume/ -->
        Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a>
      </div>
    </div>
  </footer><!-- End Footer -->
</template>

<script setup lang="js">
import { on, select } from '@/utils'
import { inject, onMounted, ref } from 'vue'
import Isotope from 'isotope-layout'
import SeccionValidaciones from '@/pages/BasePage/sections/SeccionValidaciones.vue'

const AOS = inject('aos')

/**
 * @type {import('vue').Ref<HTMLDivElement>}
 */
const portfolioContainer = ref()

/**
 * @type {import('vue').Ref<HTMLLIElement>}
 */
const portfolioFilters = ref()

const mountPortfolio = () => {
  const portfolioIsotope = new Isotope(portfolioContainer.value, {
    itemSelector: '.portfolio-item',
  })
  let portfolioFilters = select('#portfolio-flters li', true);
  on('click', '#portfolio-flters li', function (e) {
    e.preventDefault();
    portfolioFilters.forEach(function (el) {
      el.classList.remove('filter-active');
    });
    this.classList.add('filter-active');

    portfolioIsotope.arrange({
      filter: this.getAttribute('data-filter')
    });
    portfolioIsotope.on('arrangeComplete', function () {
      AOS.refresh()
    });
  }, true);
}

// const mount

const mountTestimonials = () => {
  const swiper = 2
}


onMounted(() => {
  mountPortfolio()
})

</script>