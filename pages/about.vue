<template>
    <div>
        <p>about</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio, possimus.</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio, possimus.</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
// const { data } = await useFetch('/api/main?name=musa',{method: 'POST', body: { age: 30 }})
const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
h2{
    margin-bottom:20px;
    font-size: 36px;
}
</style>