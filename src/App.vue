<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div class="app">
        <nav class="nav">
            <nav>
                <RouterLink :to="{ name: 'home' }">Home page</RouterLink>
                <RouterLink :to="{ name: 'another' }">Another page</RouterLink>
            </nav>
        </nav>

        <RouterView />
    </div>
</template>

<style scoped>
.app {
    display: flex;
}
</style>
