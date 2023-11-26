<template>
  <header id="header" class="d-flex flex-column justify-content-center">
    <nav id="navbar" class="navbar nav-menu">
      <ul>
        <li>
          <a href="#hero" class="nav-link scrollto active"
            ><i class="bx bx-home"></i> <span>Home</span></a
          >
        </li>
        <li>
          <a href="#about" class="nav-link scrollto"
            ><i class="bx bx-user"></i> <span>Nosotros</span></a
          >
        </li>
        <li>
          <a href="#prototipo" class="nav-link scrollto"
            ><i class="bx bx-file-blank"></i> <span>Prototipo</span></a
          >
        </li>
        <li>
          <a href="#portfolio" class="nav-link scrollto"
            ><i class="bx bx-book-content"></i> <span>Portfolio</span></a
          >
        </li>
        <li>
          <a href="#contact" class="nav-link scrollto"
            ><i class="bx bx-envelope"></i> <span>Contacto</span></a
          >
        </li>
      </ul>
    </nav>
    <!-- .nav-menu -->
  </header>
  <!-- End Header -->
</template>

<script setup>
import { onMounted } from "vue"
import { on, select } from '@/utils'

onMounted(() => {
  /**
   * Navbar links active state on scroll
   */
  let navbarlinks = select("#navbar .scrollto", true);
  const navbarlinksActive = () => {
    let position = window.scrollY + 200;
    navbarlinks.forEach((navbarlink) => {
      if (!navbarlink.hash) return;
      let section = select(navbarlink.hash);
      if (!section) return;
      if (
        position >= section.offsetTop &&
        position <= section.offsetTop + section.offsetHeight
      ) {
        navbarlink.classList.add("active");
      } else {
        navbarlink.classList.remove("active");
      }
    });
  };

  navbarlinksActive()
});
</script>
