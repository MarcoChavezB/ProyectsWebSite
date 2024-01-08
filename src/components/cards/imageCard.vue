<template>
    <div class="imageCard">
      <div class="backimage" :style="{backgroundImage: `linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.7)), url(${img})`}"></div>
      <div class="contenido grid">
        <header>
          <div class="title h-full flex center-y">
            <h3 class="m-3">{{ title }}</h3>
          </div>
        </header>
        <body>
          <div class=""></div>
        </body>
        <footer>
          <div class="footer">
            <p class="m-3 sub-text">{{ subtext }}</p>
            <p class="m-3">{{ contenido }}</p>
          </div>
        </footer>
      </div>
    </div>
</template>

<script setup>
  import { defineProps } from 'vue';
  const props = defineProps({
    title: {
      type: String,
      default: 'title'
    },
    subtext: {
      type: String,
      default: 'subtext'
    },
    contenido: {
      type: String,
      default: 'title'
    },
    img: {
      type: String,
    }
  });
</script>

<style scoped>
  .imageCard {
    height: 100%;
    position: relative;
    background-color: black;
  }

  .contenido {
    position: relative;
    z-index: 3;
    width: 100%;
    height: 100%;
    grid-template-rows: 1fr 3fr 1.3fr;
  }

  .backimage {
    width: 100%;
    height: 100%;
    background-size: cover;
    background-position: center;
    position: absolute;
    z-index: 2;
  }
</style>
