<template>
    <div class="principal grid">
        <div class="navbar">
            <navbarVue />
        </div>
        <div class="body ">
            <div class="back-image"></div>
            <div class="cont-image flex center">
                <div class="title-cont grid">
                    <div class="title grid grid-cols-2 ">
                        <div class="grid1">

                        </div>
                        <div class="grid2 flex flex-col justify-center">
                            <h1>Costos y Proyectos</h1>
                            <h2>Ing. Paulo Sergio Chavez Jasso</h2>
                        </div>
                    </div>
                    <div class="images">
                        <div class="black"></div>
                    </div>
                </div>
            </div>
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
    height: 300vh;
}
.navbar{
    width: 100%;
    background-color: #111111;
    position: fixed;
    z-index: 1;
}
.cont-image{
    width: 100%;
    height: 100vh;
}
.title-cont{
    width: 100%;
    height: fill;
    margin-top: 6rem;
    grid-template-rows: 2fr 0.8fr;
}
.black{
    background-color: black;
    opacity: 0.5;
    height: 100%;
}

.back-image{
    background-image: url('../assets/img/casas/casa2.jpeg');
    background-size: cover;
    background-position: center;
    width: 100%;
    z-index: -1;
    height: 100vh;
    opacity: 0.5;
    position: absolute;    
}
</style>