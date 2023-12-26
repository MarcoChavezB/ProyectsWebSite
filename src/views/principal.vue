<template>
    <div class="principal grid">
        <div class="navbar">
            <navbarVue />
        </div>
        <div class="body bg-slate-50">

        </div>
    </div>
</template>

<script setup>
import navbarVue from '../components/principal/navbar.vue';
</script>

<style scoped>

.principal{
    grid-template-rows: auto 1fr;
    width: 100%;
}
.navbar{
    width: 100%;
}
</style>