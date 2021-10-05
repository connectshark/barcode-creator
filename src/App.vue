<template>
  <h1 class="title">{{title}}</h1>
  <router-view></router-view>
</template>

<script>
export default {
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
}
.title{
  font-size: 30px;
  line-height: 1.9;
}
</style>
