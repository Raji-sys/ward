<template>
    <div>
        <h1 class="cus-text-gr text-center uppercase text-xl">north west zone</h1>
        <div class="grid grid-cols-3 gap-4 mt-6 p-10 uppercase text-center bg-gradient-to-r from-blue-300 via-blue-400 to-blue-300 rounded-3xl">
            <NuxtLink to="/nw/jigawa"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">jigawa</p></div></NuxtLink>
            <NuxtLink to="/nw/kaduna"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">kaduna</p></div></NuxtLink>
            <NuxtLink to="/nw/kano"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">kano</p></div></NuxtLink>
            <NuxtLink to="/nw/katsina"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">katsina</p></div></NuxtLink>
            <NuxtLink to="/nw/kebbi"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">kebbi</p></div></NuxtLink>
            <NuxtLink to="/nw/sokoto"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">sokoto</p></div></NuxtLink>
            <NuxtLink to="/nw/zamfara"><div class="p-10 card-sm"><p class="cus-text-gr text-lg">zamfara</p></div></NuxtLink>
        </div>
    </div>
</template>

<script setup>
definePageMeta({
    layout:'dashboard'
})
</script>

<style scoped>

</style>