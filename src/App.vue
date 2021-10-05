<template>
  <Head/>
  <router-view></router-view>
</template>

<script>
import Head from './components/head.vue'
export default {
  components: {
    Head
  },
  setup () {
    return {
      title: '條碼產生器'
    }
  }
}
</script>


<style lang="scss">
#app {
  font-family: 'Roboto Mono', 'Noto Sans TC', sans-serif;
  text-align: center;
  min-height: 100vh;
}
</style>
