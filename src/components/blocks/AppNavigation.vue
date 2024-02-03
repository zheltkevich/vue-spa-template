<template>
    <nav class="nav">
        <nav>
            <RouterLink :to="{ name: 'home' }">Home page</RouterLink>
            <RouterLink :to="{ name: 'another' }">Another page</RouterLink>
        </nav>
    </nav>
</template>
