<script setup>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div>
    <Header />
    <Content />
    <Footer />
  </div>
</template>

<style scoped>
main {
  display: flex;
  align-self: center;
  height: calc(100vh - var(--header-height) - var(--footer-height));
}
</style>
