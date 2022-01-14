<template>
  <div class="footer">
      <div class="big-footer-container">
          <div class="top-container"> 
            <div class="footer-top">
            <div class="footer-top-left">
                <div class="list">
                <ul>
                    <li class="list-title">
                    DC Comics
                        <ul>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                            <li><a href="">Characters</a></li>
                        </ul>
                    </li>
                    <li class="list-title">Shop
                        <ul>
                            <li><a href="">Shop DC</a></li>
                            <li><a href="">Shop DC collectibles</a></li>

                        </ul>
                    </li>
                </ul>
            </div>

             <div class="list">
                <ul>
                <li class="list-title">
                    DC
                    <ul>
                        <li><a href="">Terms Of Use</a></li>
                        <li><a href="">Privacy Policy (New)</a></li>
                        <li><a href="">Ad Choices</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>

                    </ul>
                </li>
                
                </ul>
            </div>

            <div class="list">
                <ul>
                    <li class="list-title">
                        Sites
                        <ul>
                            <li><a href="">DC</a></li>
                            <li><a href="">MAD Magazine</a></li>
                            <li><a href="">DC Kids</a></li>
                            <li><a href="">DC Universe</a></li>
                            <li><a href="">DC Power Visa</a></li>
                        </ul>
                    </li>
                   
                </ul>
            </div>


            </div>
            
           
        </div>

        <div class="footer-right">
            <div class="footer-right-container">

            </div>
        </div>
    </div>
      </div>

      <div class="footer-bottom">

      </div>
      
  </div>
  
</template>

<script>
export default {
    name:"Footer",
}
</script>

<style lang="scss" scoped>
    .footer {
        width: 100%;

        .big-footer-container {
            background-image: url(../assets/img/footer-bg.jpg);

            .top-container {
            width: 70%;
            margin: 0 auto;
            display: flex;

            .footer-top {
                width:60%;
                padding: 2em 0;
                color: rgba(54, 44, 44, 0.503);

                .footer-top-left {
                display: flex;
                }
                
                .list {
                    padding-right: 1em;

                    ul {
                        list-style: none;

                    .list-title {
                        color: white;
                        padding-top: 1em;

                        text-transform: uppercase;

                        ul li {
                            text-transform: none;

                            a {
                                color: rgb(150, 120, 120);
                                text-decoration: none;
                                font-size: 0.7em ;

                            }

                        }
                    }
                    }
                }
                
            }

            .footer-right {
                width: 100%;
                background-image: url(../assets/img/dc-logo-bg.png);
                background-position: center;
                background-repeat: no-repeat;
            }

            
        }
        }

        

        
    }

    .footer-bottom {
        width: 100%;
        height: 150px;
        background-color: rgba(54, 44, 44, 0.503);
    }
</style>