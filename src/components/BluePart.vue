<template>
  <div class="bluepart">

      <div class="container">

          <p>blue part goes here</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'BluePart',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .bluepart{
    width: 100wh;
    background-color: #0282f9;
    display: flex;
    justify-content: center;
    // debug
    height: 140px;
        .container{
        width: 80%;
        height: 100%;
        // debug
        background-color: rgb(185, 80, 80);
      }
  }
</style>