<template>
  <div class="main-container">
      <div class="content-container">
            
      </div>
        <div class="thumbs-container">
            <div class="thumb-container">               
                <Thumbnail class="single-thumb" 
                     v-for="(thumbnail, index) in thumbs"
                     :key="index"
                     :img="thumbnail.thumb"
                     :name="thumbnail.series"
                     >
                    <!-- <div class="thumb-img">
                      <img :src="thumbnail.thumb" alt="">
                    </div>
                    <h2> {{ thumbnail.series }} </h2> -->
                </Thumbnail>
            </div>
        </div>
      <div class="cards-container">

          <div class="cards">
              <ul>
                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><a href="">digital comics</a></li>

                <li><img src="../assets/img/buy-comics-merchandise.png" alt=""><a href="">dc merchandise</a></li>

                <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""><a href="">subscription</a></li>

                <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""><a href="">comic shop locator</a></li>

                <li><img src="../assets/img/buy-dc-power-visa.svg" alt=""><a href="">dc power visa</a></li>
          </ul>
          </div>
          
      </div>


  </div>
</template>

<script>
import Thumbnail from "./Thumbnail.vue";
export default {
    name:"Main",
    components: {
    Thumbnail,
  },
    data () {
        return {
            thumbs: [    
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
                price: "$19.99",
                series: "Action Comics",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
                price: "$3.99",
                series: "American Vampire 1976",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
                price: "$16.99",
                series: "Aquaman",
                type: "graphic novel"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
                price: "$2.99",
                series: "Batgirl",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                price: "$3.99",
                series: "Batman",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                price: "$2.99",
                series: "Batman Beyond",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
                price: "$3.99",
                series: "Batman/Superman",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
                price: "$4.99",
                series: "Batman/Superman Annual",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
                price: "$5.99",
                series: "Batman: The Joker War Zone",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
                price: "$6.99",
                series: "Batman: Three Jokers",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
                price: "$4.99",
                series: "Batman: White Knight Presents: Harley Quinn",
                type: "comic book"
                },
                {
                thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
                price: "$16.99",
                series: "Catwoman",
                type: "graphic novel"
            }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .main-container {
        width: 100%;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        

        .content-container {
            width: 60%;
            height: 300px;
            padding-top: 1em;
            margin: 0 auto;
            color: white;
            font-size: 2em;
        }

        .thumbs-container {
            margin-top: 4em;
            width: 100%;
            background-color: RGB(50, 50, 50);

            .thumb-container {
                width: 60%;
                margin: 0 auto;
                padding: 4em 0;
                display: flex;
                flex-wrap: wrap;
                gap: 30px;

            
            }
        }

        .cards-container {
            background-color: RGB(2, 130, 249);
            width: 100%;
            padding: 2em 0;
            margin: 0 auto;
    
            .cards {
                width: 60%;
                margin: 0 auto;

                ul {
                    list-style: none;
                    display: flex;
                    justify-content: center;
                    align-items: center;

                    li {
                        display: flex;
                        align-items: center;
                       margin-left: 3%;

                        img {
                            width: 20%;
                            margin-right: 10px;
                        }

                        a {
                            color: white;
                            text-transform: uppercase;
                            font-size: 0.6em;
                            text-decoration: none;
                        }
                    }
                }
            }

            
        }


    }
</style>