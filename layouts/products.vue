<template>

<div class="ms-10 my-10 font-pacifico text-4xl font-thin text-purple-500">
   <NuxtLink to="/"> FakeStore</NuxtLink>
   </div>
    <slot />
    <div class="mx-10 my-10 pt-5 flex gap-7 font-bold shadow-inner">
    <button><NuxtLink to="/"> home</NuxtLink></button>
    <button><NuxtLink to="/about">about</NuxtLink></button>
    <button><NuxtLink to="/products">products</NuxtLink></button>
   </div>
    
</template>

<script setup>

</script>