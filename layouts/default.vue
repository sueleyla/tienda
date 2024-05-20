<template>
    <div>
<header class="flex justify-between mx-10 my-10">
   <div class="font-bold font-pacifico text-4xl text-purple-500">
   <NuxtLink to="/"> FakeStore</NuxtLink>
   </div>
   <div class="flex gap-7">
    <button class="btn"><NuxtLink to="/"> home</NuxtLink></button>
    <button class="btn"><NuxtLink to="/about">about</NuxtLink></button>
    <button class="btn"><NuxtLink to="/products">products</NuxtLink></button>
   </div>
</header>
    </div>
    <slot />
</template>

<script setup>

</script>

