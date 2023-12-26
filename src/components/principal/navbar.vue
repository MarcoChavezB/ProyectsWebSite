<template>
    <div class="navbar grid grid-cols-2 items-center">
        <div class="logo flex items-center gap-10">
            <div class="img"><img src="https://th.bing.com/th/id/R.fd717fef3ec1752144ff1a9bbfff7247?rik=B%2b4nsHOuSFZUwQ&pid=ImgRaw&r=0" alt=""></div>
            <div class="socials flex flex-col gap-5 h-full items-end">
                <div class="text grid  h-full grid-rows-2">
                    <div class="name">
                        <h2 class="resaltado">Paulo Sergio Chavez Jasso</h2>
                    </div>
                    <div class="ocupation grid gap-10">
                        <div class="oc">Ingeniero Civil</div>
                        <div class="socials">
                            <socials />
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="sections flex center-y justify-end">
            <contact />
            <location />
        </div>
    </div>
</template>

<script setup>
import contact from '../controllers/contact.vue';
import location from '../controllers/location.vue';
import socials from '../icons/socials.vue';
</script>

<style scoped>

.img {
    width: 8rem;
}
.logo{
    margin-left: 20px;
}

.sections{
    margin-right: 20px;
}
.navbar{
    width: 100%;
} 
.ocupation{
    grid-template-columns: 1fr 2fr;
}
</style>


