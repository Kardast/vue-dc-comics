<template>
  <div class="bluepart">

      <div class="container">

          <img v-for="(item, index) in shop" :key="index" src="item.img" alt="item.alt">
      </div>
  </div>
</template>

<script>
export default {
  name: 'BluePart',
  data(){
    return{
      shop: [
        {
          img: require("../assets/img/buy-comics-digital-comics.png"),
          alt: "digital",
        },
        {
          img: require("../assets/img/buy-comics-merchandise.png"),
          alt: "merchandise",
        },
        {
          img: require("../assets/img/buy-comics-shop-locator.png"),
          alt: "locator",
        },
        {
          img: require("../assets/img/buy-comics-subscriptions.png"),
          alt: "subs",
        },
        {
          img: require("../assets/img/buy-dc-power-visa.svg"),
          alt: "visa",
        }
      ]
    }
  }
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
        display: flex;

        // debug
        background-color: rgb(185, 80, 80);
      }
  }
</style>