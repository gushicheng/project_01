<template>
  <div class="home">
    <div class="left"></div>
    <div class="right"></div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
  }
}
</script>

<style lang='scss' scoped>
.home{
  height: 100%;
  display: flex;
  .left{
    width: 200px;
    background: aqua;
    height: 100%
  }
  .right{





    flex: 1;
    background: red;
  }
}

</style>
