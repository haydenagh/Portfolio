<script setup>
    import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div>
        <div>
            <RouterLink to="/"><h3>Hayden's Portfolio</h3></RouterLink>
         </div>
        <div>
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
            <RouterLink to="/portfolio">Portfolio</RouterLink>
        </div>
    </div>

</template>

<style>
</style>