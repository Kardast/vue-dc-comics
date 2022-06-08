<template>
  <div class="footer">

      <div class="container">

          <p>footer goes here</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPart',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .footer{
    width: 100wh;
    display: flex;
    justify-content: center;
    height: 300px;
    // debug
    background-color: #506f8d;
        .container{
        width: 80%;
        height: 100%;
        // debug
        background-color: rgb(187, 128, 128);
      }
  }
</style>