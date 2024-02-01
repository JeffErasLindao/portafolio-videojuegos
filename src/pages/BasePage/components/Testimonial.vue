<script setup>
defineProps({
  nombreEntrevistado: { type: String, required: true },
  iteracion: { type: Number, required: true, default: 1 },
  descripcion: { type: String, required: true, default: "" },
  img: { type: String, required: true }
});
</script>

<template>
  <div class="carousel2-inner">
    <img
      :src="img"
      class="d-block w-100 carousel2-image"
      alt=""
    />
    <h3>{{ nombreEntrevistado }}</h3>
    <span class="badge bg-primary">Iteración {{ iteracion }}</span>
    <h4>Entrevistado - Validador</h4>
    <p>
      <i class="bx bxs-quote-alt-left quote-icon-left"></i>
      {{ descripcion }}
      <i class="bx bxs-quote-alt-right quote-icon-right"></i>
    </p>
  </div>
</template>
