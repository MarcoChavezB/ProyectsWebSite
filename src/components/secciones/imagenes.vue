<template>
    <div class="cardsImages flex center">
        <div class="images-cont gap-10 grid grid-cols-4">
            <div class="sec">
                <imageCard title="Hola" subtext="soaksokok" contenido="ksakso" img="src/assets/img/fotos/image3.jpeg"/>
            </div>
            <div class="sec">
                <imageCard title="Hola" subtext="soaksokok" contenido="ksakso" img="src/assets/img/fotos/image1.jpeg"/>
            </div>
            <div class="sec">
                <imageCard title="Hola" subtext="soaksokok" contenido="ksakso" img="src/assets/img/fotos/image2.jpeg"/>
            </div>
            <div class="sec">
                <imageCard title="Hola" subtext="soaksokok" contenido="ksakso" img="src/assets/img/fotos/image3.jpeg"/>
            </div>
        </div>
    </div>
</template>

<script setup>
import imageCard from '../cards/imageCard.vue';
</script>
<style scoped>
.cardsImages{
    width: 100%;
    height: 60vh;
    background-color: #202020;
}

.images-cont{
    width: 90%;
    height: 90%;
}
</style>