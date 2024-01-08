<template>
    <div class="principal grid">
        <div class="navbar">
            <navbarVue />
        </div>
        <div class="body ">
            <div class="back-image"></div>
            <div class="cont-image flex center">
                <div class="title-cont grid">
                    <div class="title grid grid-cols-3 gap-4">
                        <div class="grid1">
                        </div>
                        <div class="grid2 col-span-2 flex flex-col justify-center texto gap-10">
                        <div class="flex gap-10 items-center">
                            <img class="w-20 h-20 rounded-full" src="https://media.licdn.com/dms/image/D4E03AQEuX3jkSO1K4g/profile-displayphoto-shrink_800_800/0/1700948126550?e=1710374400&v=beta&t=Vbwe-G3DiP-H5JHs4oYqyc6VINZ1d-wmd48JRTkPuDA" alt="Rounded avatar">
                        <h1 class="text-4xl font-bold">Costos y Proyectos</h1>
                        </div>
                        <h2 class="text-xl">Ing. Paulo Sergio Chavez Jasso</h2>
                        </div>
                    </div>
                    <div class="images">
                        <div class="black"></div>
                        <div class="cont flex center">
                            <div class="contenido grid">
                                <div class="texto flex center-x flex-col gap-4">
                                    <socialsVue />
                                    <p class="small-text w-4/5">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione, facilis </p>
                                    <buttonOutline text="Contactar" />                
                                </div>
                                <div class="imagenes  flex gap-5">
                                    <div class="img flex">
                                        <img src="../assets/img/fotos/image1.jpeg" alt="">
                                    </div>
                                    <div class="img flex">
                                        <img src="../assets/img/fotos/image3.jpeg" alt="">
                                    </div>
                                    <div class="img flex">
                                        <img src="../assets/img/fotos/image2.jpeg" alt="">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="experiencia w-full">
                <experiencia />
            </div>

            <div class="cards w-full">
                <imagenes />         
            </div>
            
            <div class="habilities w-full">
                <habilities />
            </div>

            <div class="cardLeft w-full">
                <cardLeft />
            </div>

            <div class="cardRight w-full">
                <cardRight />
            </div>

            <div class="textArea w-full">
                <textAreaSec />
            </div>

            <div class="history w-full">
                <History />
            </div>

        </div>
    </div>
</template>

<script setup>
import History from '../components/secciones/history.vue';
import textAreaSec from '../components/secciones/textArea.vue';
import cardRight from '../components/secciones/cardRight.vue';
import cardLeft from '../components/secciones/cardLeft.vue';
import habilities from '../components/cards/habilidades.vue';
import imagenes from '../components/secciones/imagenes.vue';
import buttonOutline from '../components/controllers/buttonOutline.vue';
import socialsVue from '../components/icons/socialOutline.vue';
import navbarVue from '../components/principal/navbar.vue';
import experiencia from '../components/secciones/experiencia.vue';
</script>

<style scoped>
.habilities{
    width: 100%;
    height: 40vh;
}


.cardLeft{
    width: 100%;
    height: 70vh;
}

.history{
    width: 100%;
    height: 100vh;
}
.textArea{
    width: 100%;
    height: 20vh;
    background-color: #202020;
}

.cardRight{
    width: 100%;
    height: 70vh;
}
.imagenes .img {
  width: 30%;
  height: 100%;
  justify-content: center;
  align-items: center;
}
.imagenes .img img {
  width: 95%;
  border-radius: 10px;
  height: 95%;
  object-fit: cover;
}
.texto h1{
    font-size: 4rem;
}

.principal{
    grid-template-rows: auto 1fr;
    width: 100%;
    height: 300vh;
}
.navbar{
    width: 100%;
    background-color: #111111;
    position: fixed;
    z-index: 9999;
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
    position: absolute;
    width: 100%;
    z-index: -1;
}
.cont{
    height: 100%;
    width: 100%;
}
.contenido{
    width: 80%;
    height: 90%;
    grid-template-columns: 1fr 2fr;
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