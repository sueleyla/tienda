<template>
    <div>
        
        <img :src="product.image" alt=""srcset="">
        <p>{{ product.tittle }}</p>
        <NuxtLink :to="`/products/${product.id}`">
        <p class="btn my-4">ver detalle</p>
        </NuxtLink>
    </div>
</template>

<script setup>
const { product } = defineProps(["product"])
</script>

<style scoped>
img{
    max-height: 120px;
    max-width: 70%;
    margin: auto;

}
</style>