<template>
  <div class="main-container">
      <div class="content-container">
          --> Content goes here
      </div>
      <div class="cards-container">

          <div class="cards">
              <ul>
                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><a href="">digital comics</a></li>

                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><a href="">dc merchandise</a></li>

                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><a href="">subscription</a></li>

                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><a href="">comic shop locator</a></li>

                <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""><a href="">dc power visa</a></li>
          </ul>
          </div>
          
      </div>

      
  </div>
</template>

<script>
export default {
    name:"Main",
}
</script>

<style lang="scss" scoped>
    .main-container {
        width: 100%;
        background-color: rgba(0, 0, 0, 0.823);

        .content-container {
            width: 60%;
            height: 200px;
            padding-top: 1em;
            margin: 0 auto;
            color: white;
            font-size: 2em;
        }



        .cards-container {
            background-color: RGB(2, 130, 249);
            width: 100%;
            padding: 1em 0;
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