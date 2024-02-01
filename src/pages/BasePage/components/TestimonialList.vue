<template>
  <Swiper
    class="testimonials-slider"
    slides-per-view="auto"
    data-aos="fade-up"
    data-aos-delay="100"
  >
    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/img/testimonials/validacion1.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Manuel Martinez </h3>
        <span class="badge bg-primary">Iteración 1</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Entrevistado por Sergio Basurto
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/img/testimonials/validacion2.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Yalile Pavon</h3>
        <span class="badge bg-primary">Iteración 1</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Entrevistado por Sergio Basurto
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/validaciones/entrevista-laura-cedeno-3it.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Laura Cedeño</h3>
        <span class="badge bg-primary">Iteración 3</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Entrevistado por Sergio Basurto
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/img/testimonials/validacion3.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Joseph Morante</h3>
        <span class="badge bg-primary">Iteración 1</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Explicando las reglas del juego
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/img/testimonials/validacion4.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Joseph Morante</h3>
        <span class="badge bg-primary">Iteración 1</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Jugando
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/img/testimonials/validacion5.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Joseph Morante</h3>
        <span class="badge bg-primary">Iteración 1</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Menciona que se puede añadir mas niveles de difcultades, como rapidez,
          ingredientes especiales buenos y malos.
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/validaciones/entrevista-joseph-morante-2it.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Joseph Morante [Iteracion 2]</h3>
        <span class="badge bg-primary">Iteración 2</span>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Menciona que se puede añadir mas niveles de difcultades, como rapidez,
          ingredientes especiales buenos y malos.
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>

    <SwiperSlide>
      <div class="carousel2-inner">
        <img
          src="@assets/validaciones/entrevista-joseph-morante-3it.png"
          class="d-block w-100 carousel2-image"
          alt=""
        />
        <h3>Joseph Morante [Iteracion 3]</h3>
        <h4>Entrevistado - Validador</h4>
        <p>
          <i class="bx bxs-quote-alt-left quote-icon-left"></i>
          Menciona que se puede añadir mas niveles de difcultades, como rapidez,
          ingredientes especiales buenos y malos.
          <i class="bx bxs-quote-alt-right quote-icon-right"></i>
        </p>
      </div>
    </SwiperSlide>
    <SwiperSlide>
      <Testimonial
      nombre-entrevistado="Entrevistado por Andrés"
      iteracion="1"
      descripcion="Entrevistado por Andrés"
      :img="UrlImgEntrevistadoAndres1"
      />
    </SwiperSlide>
    <SwiperSlide>
      <Testimonial
      nombre-entrevistado="Entrevistado por Andrés"
      iteracion="2"
      descripcion="Entrevistado por Andrés"
      :img="UrlImgEntrevistadoAndres2"
      />
    </SwiperSlide>
  
  <SwiperSlide>
      <Testimonial
      nombre-entrevistado="Entrevistado por Joel"
      iteracion="3"
      descripcion="Entrevistado por Joel"
      :img="UrlImgEntrevistadoJoel1"
      />
    </SwiperSlide>
  
  <SwiperSlide>
      <Testimonial
      nombre-entrevistado="Paula"
      iteracion="4"
      descripcion="Entrevistado por Joel"
      :img="UrlImgPaulaJoel"
      />
    </SwiperSlide>
  </Swiper>
</template>

<script setup lang="js">
import { Swiper, SwiperSlide } from 'swiper/vue'
import Testimonial from './Testimonial.vue'
import UrlImgEntrevistadoAndres1 from '@assets/validaciones/entrevista-validacion-andres-1it.png'
import UrlImgEntrevistadoAndres2 from '@assets/validaciones/entrevista-validacion-andres-2it.png'
import UrlImgEntrevistadoJoel1 from '@assets/validaciones/entrevista-validacion-joel-3it.png'
import UrlImgPaulaJoel from '@assets/validaciones/entrevista-paula-joel-4it.png'
</script>
