<template>
    <div>
        <header class="shadow-xl bg-gradient-to-r from-blue-300 via-blue-400 to-blue-300">
            <nav class="container mx-auto p-4 flex justify-between uppercase">
                <!-- <NuxtLink to="/" class="font-bold text-white"><img src="logo1.png"></NuxtLink> -->
            </nav>
    </header>

    <!-- output page content -->
    <div class="container mx-auto p-4">
        <slot />
    </div>
</div>
</template>

<style scoped>
/* .router-link-exact-active{ */
    /* color:#12b488; */
/* } */
</style>