<template>
  <div class="footer_low">

    <div class="container">

      <div class="button">
        <a href="#">SIGN-UP NOW!</a>
      </div>

      <div class="socials">
        <h3>FOLLOW US</h3>
        <ul>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="social"></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="social"></a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="social"></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="social"></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="social"></a></li>
        </ul>
      </div>
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
        display: flex;
        align-items: center;

        .button{
          width: 20%;

          a{
            color: white;
            text-decoration: none;
            border: 2px solid #0282f9;
            padding: 10px;
          }
        }

        .socials{
          width: 80%;
          display: flex;
          align-items: center;
          justify-content: end;

          h3{
            margin-right: 20px;
            color: #0282f9;
          }

          ul{
            display: flex;

            li{
              list-style: none;
              margin: 5px;
            }
          }
        }
      }
  }
</style>