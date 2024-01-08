<template>
    <div class="principal-cont flex center">
        <div class="cont grid grid-cols-3">
            <div class="tiempo flex center">
                <div class="contenedor flex center">
                    <div class="contenido flex gap-3 ">
                        <h1 class="yellow flex center">15</h1>
                        <p class="flex center">Experience <br> in the industry</p>
                    </div>
                </div>
            </div>
            <div class="title flex center">
                <div class="conte">
                    <p class="yellow">About me</p>
                    <h2>Lorem, ipsum dolor sit amet consectetur </h2>
                </div>

            </div>
            <div class="info felx center">
                <div class="conte flex gap-6 flex-col">
                    <p class="sub-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, itaque asperiores omnis sapiente quis voluptate animi porro, dolorum numquam quas repellendus eligendi cumque eos aspernatur </p>
                    <buton text="Contact me" ico="arrow_right_alt"/>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import buton from '../controllers/buton.vue';
</script>

<style scoped>
.conte{
    height: 45%;
    width: 90%;
}
h1{
    font-size: 6rem;

}
.cont{
    width: 90%;
    height: 100%;
    background-color: #111111;
}
.contenedor{
    width: 58%;
    height: 46%;
    border: 5px solid #32353c;
}

.principal-cont{
    width: 100%;
    height: 40vh;
    background-color: #111111;
}


</style>