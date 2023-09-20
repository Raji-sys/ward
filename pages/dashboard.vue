<template>
    <h1 class="cus-text-gr text-center uppercase text-xl">zones</h1>
    <div class="grid grid-cols-3 gap-4 mt-6 p-14 uppercase text-center bg-gradient-to-r from-blue-300 via-blue-400 to-blue-300 rounded-3xl">
      <NuxtLink to="/nc"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">north-central</p></div></NuxtLink>
        <div class="p-10 card-sm"><p class="cus-text-gr text-lg">north-east</p></div>
      <NuxtLink to="/nw"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">north-west</p></div></NuxtLink>
        <div class="p-10 card-sm"><p class="cus-text-gr text-lg">south-east</p></div>
        <div class="p-10 card-sm"><p class="cus-text-gr text-lg">south-south</p></div>
        <div class="p-10 card-sm"><p class="cus-text-gr text-lg">south-west</p></div>
    </div>
</template>

<script setup>
definePageMeta({
    layout:'dashboard'
})
</script>

<style scoped>

</style>