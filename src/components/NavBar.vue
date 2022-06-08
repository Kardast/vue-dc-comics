<template>
  <div class="navbar">

    <div class="container">

      ciao
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navbar{
    width: 100wh;
    height: 120px;
    display: flex;
    justify-content: center;
    // debug
    background-color: yellow;
      .container{
        width: 80%;
        height: 100%;
        // debug
        background-color: red;
      }
  }
</style>
