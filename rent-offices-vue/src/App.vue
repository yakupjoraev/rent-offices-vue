<script setup>
import HeaderVue from "./components/HeaderVue.vue";
import HeroVue from "./components/HeroVue.vue";
import FooterVue from "./components/FooterVue.vue";
</script>

<template>
  <div class="wrapper">
    <HeaderVue />
    <main>
      <HeroVue />
    </main>
    <FooterVue />
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100%;
}
</style>
