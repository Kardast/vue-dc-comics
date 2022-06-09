<template>
  <div class="footer">

      <div class="container">

        <div class="f-links">

            <ul>
                <h3>DC COMICS</h3>

                <li v-for="(item, index) in dcomics" :key="index">
                    <a href="item.url">{{item.text}}</a>
                </li>

                <h3>SHOP</h3>

                <li v-for="(item, index) in shop" :key="index">
                    <a href="item.url">{{item.text}}</a>
                </li>
            </ul>

            <ul>
                <h3>DC</h3>

                <li v-for="(item, index) in dc" :key="index">
                    <a href="item.url">{{item.text}}</a>
                </li>
            </ul>

            <ul>
                <h3>SITES</h3>

                <li v-for="(item, index) in sites" :key="index">
                    <a href="item.url">{{item.text}}</a>
                </li>
            </ul>
        </div>

        <div class="f-pic">

            <img src="../assets/img/dc-logo-bg.png" alt="logo">
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FooterPart',
    data(){
        return{
            dcomics: [
                {
                text: "Characters",
                url: "#",
                },
                {
                text: "Comics",
                url: "#",
                },
                {
                text: "Movies",
                url: "#",
                },
                {
                text: "TV",
                url: "#",
                },
                {
                text: "Games",
                url: "#",
                },
                {
                text: "Videos",
                url: "#",
                },
                {
                text: "News",
                url: "#",
                }
            ],
            shop: [
                {
                text: "Shop DC",
                url: "#",
                },
                {
                text: "Shop DC Collectibles",
                url: "#",
                },
            ],
            dc: [
                {
                text: "Terms Of Use",
                url: "#",
                },
                {
                text: "Privacy policy (New)",
                url: "#",
                },
                {
                text: "Ad Choices",
                url: "#",
                },
                {
                text: "Advertising",
                url: "#",
                },
                {
                text: "Jobs",
                url: "#",
                },
                {
                text: "Subscriptions",
                url: "#",
                },
                {
                text: "Talent Workshops",
                url: "#",
                },
                {
                text: "CPSC Certificates",
                url: "#",
                },
                {
                text: "Ratings",
                url: "#",
                },
                {
                text: "Shop Help",
                url: "#",
                },
                {
                text: "Contacts Us",
                url: "#",
                },
            ],
            sites: [
                {
                text: "DC",
                url: "#",
                },
                {
                text: "MAD Magazine",
                url: "#",
                },
                {
                text: "DC Kids",
                url: "#",
                },
                {
                text: "DC Universe",
                url: "#",
                },
                {
                text: "DC Power Visa",
                url: "#",
                }
            ]
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .footer{
    width: 100wh;
    display: flex;
    justify-content: center;
    height: 300px;
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;

        .container{
        width: 80%;
        height: 100%;
        display: flex;
        align-items: center;

            .f-links{
                width: 50%;
                display: flex;
                color: white;

                ul{
                    margin-right: 20px
                }

                h3{
                    margin-bottom: 10px;
                    margin-top: 10px;
                }

                li{
                    list-style: none;

                    a{
                        text-decoration: none;
                        color: grey;
                        font-size: 12px;
                    }
                }
            }

            .f-pic{
                width: 35%;
                display: flex;
                justify-content: center;

                img{
                    width: 80%;
                }
            }

      }
  }
</style>