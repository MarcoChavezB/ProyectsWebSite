<template>
<button type="button" class="butt flex center">{{ text }}</button>
</template>

<script setup>
import { defineProps } from 'vue';
const props = defineProps({
    text: {
        type: String,
    }
})
</script>

<style scoped>
.butt{
    color: #ffffff;
    border: 1px solid #ffffff;
    border-radius: 20px;
    width: 9rem;
    cursor: pointer;
    transition: all 0.3s ease;
}

.butt:hover{
    background-color: #ffffff;
    color: #000000;
}
</style>