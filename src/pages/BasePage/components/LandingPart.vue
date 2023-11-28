<template>
    <section id="hero" class="d-flex flex-column justify-content-center">
        <div class="container" data-aos="zoom-in" data-aos-delay="100">
            <h1 >SKY BURGER</h1>
             <p>Nuestro Juego <span class="typed" data-typed-items=", es Diversion!, es Entretenimiento!, es Experiencia!, es Pasión!, Próximamente!"></span></p>
        </div>
    </section>
</template>

<script setup>
    import aos from 'aos';
    import Typed from 'typed.js';

    // Esperar a que el DOM esté completamente cargado
    import { onMounted } from 'vue';

    onMounted(() => {
        aos.init();

        const typed = document.querySelector('.typed');
        if (typed) {
            let typed_strings = typed.getAttribute('data-typed-items');
            typed_strings = typed_strings.split(',');
            new Typed('.typed', {
                strings: typed_strings,
                loop: true,
                typeSpeed: 100,
                backSpeed: 50,
                backDelay: 2000
            });
        }
    });
</script>
