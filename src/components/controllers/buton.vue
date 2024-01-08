<template>
    <button class="flex cente gap-5">
        {{ text }}
        <span class="material-symbols-outlined">
            {{ ico }}
        </span>
    </button>
</template>

<script setup>
import { defineProps } from 'vue';
const props = defineProps({
    text: {
        type: String,
        default: 'Button'
    },
    ico: {
        type: String,
        default: 'arrow_right_alt'
    }
})
</script>


<style scoped>
button{
    width: 11rem;
}

</style>