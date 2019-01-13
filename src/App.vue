<template>
  <div id="app">
    <header-partial></header-partial>
    <main class="main">
      <router-view/>
    </main>
    <footer-partial></footer-partial>
  </div>
</template>

<script>
import HeaderPartial from './components/Header.vue';
import FooterPartial from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    HeaderPartial,
    FooterPartial,
  },
};
</script>

<style lang="scss" src="./scss/main.scss"></style>
