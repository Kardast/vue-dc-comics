<template>
  <div class="navbar">

    <div class="container">

      <div class="logo">

        <img src="../assets/img/dc-logo.png" alt="dc-logo">
      </div>
      <ul class="navlist">
        <li v-for="(link, index) in links" :key="index">
          <a :class="link.current ? 'here' : ''" href="link.url">{{link.text}}</a>
        </li>

      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  data(){
    return{
      links: [
        {
          text: "CHARACTERS",
          url: "#",
          current: false
        },
        {
          text: "COMICS",
          url: "#",
          current: true
        },
        {
          text: "MOVIES",
          url: "#",
          current: false
        },
        {
          text: "TV",
          url: "#",
          current: false
        },
        {
          text: "GAMES",
          url: "#",
          current: false
        },
        {
          text: "COLLECATIBLES",
          url: "#",
          current: false
        },
        {
          text: "VIDEOS",
          url: "#",
          current: false
        },
        {
          text: "FANS",
          url: "#",
          current: false
        },
        {
          text: "NEWS",
          url: "#",
          current: false
        },
        {
          text: "SHOP",
          url: "#",
          current: false
        },
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navbar{
    width: 100wh;
    height: 120px;
    display: flex;
    justify-content: center;

    .container{
      width: 80%;
      height: 100%;
      display: flex;

      .logo{
        height: 100%;
        width: 40%;
        display: flex;
        align-items: center;
        padding-left: 15px;
          img{
            width: 80px;
          }
      }

      .navlist{
        width: 60%;
        list-style: none;
        display: flex;
        align-items: center;
        justify-content: end;

        li{
          margin: 0 5px;

          a{
            color: black;
            text-decoration: none;
            padding: 43px 5px;
            font-size: 13px;
            font-weight: bold;

            &:hover{
              color: violet;
            }

            &.here{
              border-bottom: 8px solid rgb(0, 110, 255);
              color: rgb(0, 110, 255);
            }
          }
        }
      }
    }
  }
</style>
