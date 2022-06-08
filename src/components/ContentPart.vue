<template>
  <div class="content">

      <div class="container">

          <p>Content goes here</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'ContentPart',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .content{
    width: 100wh;
    background-color: #1c1c1c;
    display: flex;
    justify-content: center;
    // debug
    height: 120px;
        .container{
        width: 80%;
        height: 100%;
        color: white;
      }
  }
</style>