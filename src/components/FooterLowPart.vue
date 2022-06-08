<template>
  <div class="footer_low">

      <div class="container">

          <p>footer low goes here</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'FooterLowPart',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .footer_low{
    width: 100wh;
    display: flex;
    justify-content: center;
    height: 100px;
    background-color: #303030;
        .container{
        width: 80%;
        height: 100%;
        // debug
        background-color: rgb(190, 153, 153);
      }
  }
</style>