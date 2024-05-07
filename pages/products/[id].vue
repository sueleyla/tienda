<template>
    <div>
      <h1 class="text-3xl font-bold mx-10 my-10 tex text-lime-600">
      Catálogo
    </h1>
   <p>Detalle del artículo {{ id }} </p>
    </div>
  </template>

<script setup>
//paginas producto

const { id } = useRoute().params
</script>