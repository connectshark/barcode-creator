<template>
  <h1 class="title">{{title}}</h1>
  <p>*1234*</p>
  <router-view></router-view>
</template>

<script>
export default {
  setup () {
    return {
      title: 'Hello'
    }
  }
}
</script>


<style lang="scss">
@import url('./assets/scss/font.scss');
@font-face {
  font-family: free3of9;
  src: url('/font/fre3of9x.ttf') url('/font/free3of9.ttf');
}
#app {
  font-family: free3of9,'Roboto Mono', 'Noto Sans TC', sans-serif;
  text-align: center;
}
.title{
  font-size: 30px;
  line-height: 1.9;
}
</style>
