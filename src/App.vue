<template>
  <AppHeader />
  <AppMainContent />

</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMainContent from './components/AppMainContent.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMainContent
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%);
  min-height: 100vh;
  font-family: 'Rubik', sans-serif;
}

#app {
  height: 50px;
}
</style>
