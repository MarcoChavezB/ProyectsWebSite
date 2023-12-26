<template>
    <div class="navbar grid grid-cols-2">
        <div class="logo flex items-center gap-10">
            <div class="img bg-red-400"><img src="https://th.bing.com/th/id/R.fd717fef3ec1752144ff1a9bbfff7247?rik=B%2b4nsHOuSFZUwQ&pid=ImgRaw&r=0" alt=""></div>
            <div class="socials flex gap-5">
                <div class="tite center sub-text">
                    <p>Social networks:</p>
                </div>
                <div class="socials-ico">
                    <socials />
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
    height: 5rem;
}
.navbar{
    width: 100%;
} 
</style>


robloxisforyankis