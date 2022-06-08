<template>
  <div class="bluepart">

      <div class="container">

          <div v-for="(item, index) in shop" :key="index"  class="small-container">

              <img :src="item.img" :alt="item.alt">
              <p>{{item.text}}</p>
          </div>
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
          text: "DIGITAL COMICS"
        },
        {
          img: require("../assets/img/buy-comics-merchandise.png"),
          alt: "merchandise",
          text: "DC MERCHANDISE"
        },
        {
            img: require("../assets/img/buy-comics-subscriptions.png"),
          alt: "subs",
          text: "SUBSCRIPTION"
        },
        {
            img: require("../assets/img/buy-comics-shop-locator.png"),
            alt: "locator",
            text: "COMICS SHOP LOCATOR"
        },
        {
          img: require("../assets/img/buy-dc-power-visa.svg"),
          alt: "visa",
          text: "DC POWER VISA"
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
            align-items: center;
            justify-content: space-around;

            .small-container{
                display: flex;
                align-items: center;
                color: white;
                font-size: 14px;
                img{
                    width: 40px;
                    height: 55px;
                    margin-right: 5px;
                }
            }

      }
  }
</style>