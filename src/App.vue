<template>
  <AppTitle/>
  <AppHero/>
</template>

<script>
  import AppTitle from './components/icons/AppTitle.vue';
  import AppHero from './components/icons/AppHero.vue';
  export default {
    name: 'App',
    components: {
    AppTitle,
    AppHero
},
    data() {
      return {
      }
    }
  }
</script>

<style lang="scss" scoped>
</style>
