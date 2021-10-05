<template>
<header>
  <h1>{{title}}</h1>
</header>
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

<style lang="scss" scoped>
header{
  background-image: linear-gradient(to right, #5D98FC, #9B5FFC);
  h1{
    color: #F8F8F8;
    font-size: 30px;
    line-height: 2;
  }
}
</style>