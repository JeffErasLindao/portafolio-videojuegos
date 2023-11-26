<template>
    <PortfolioHeader />

    <LandingPart />

    <Portfolio />

    <!-- Vendor JS Files -->
</template>

<script setup lang="js">
import PortfolioHeader from '@/pages/BasePage/components/PortfolioHeader.vue'
import LandingPart from './components/LandingPart.vue'
import Portfolio from './components/Portfolio.vue'

// import '@/assets/vendor/purecounter/purecounter_vanilla.js'
// import '@/assets/vendor/aos/aos'
import aos from 'aos'
import 'bootstrap'
import 'glightbox'
// import '@/assets/vendor/glightbox/js/glightbox'
// import '@vendor/isotope-layout/isotope.pkgd'
import 'isotope-layout'
import 'swiper'
// import '@vendor/typed.js/typed.module'
// import '@vendor/waypoints/noframework.waypoints'
// import '@vendor/php-email-form/validate'
import { onMounted, provide } from 'vue'
import { select, scrollto } from '@/utils'
// import { PureCounter } from '@/assets/vendor/purecounter/purecounter_vanilla.js'
defineOptions({ name: 'PortafolioVideojuegos' })

provide('aos', aos)

onMounted(() => {
    if (window.location.hash) {
        if (select(window.location.hash)) {
            scrollto(window.location.hash)
        }
    }

    aos.init({
        duration: 1000,
        easing: 'ease-in-out',
        once: true,
        mirror: false,
    })
})
</script>
<!--

    <script src="src/assets/vendor/purecounter/purecounter_vanilla.js"></script>
<script src="src/assets/vendor/aos/aos.js"></script>
<script src="src/assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
<script src="src/assets/vendor/glightbox/js/glightbox.min.js"></script>
<script src="src/assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
<script src="src/assets/vendor/swiper/swiper-bundle.min.js"></script>
<script src="src/assets/vendor/typed.js/typed.umd.js"></script>
<script src="src/assets/vendor/waypoints/noframework.waypoints.js"></script>
<script src="src/assets/vendor/php-email-form/validate.js"></script>
 -->
