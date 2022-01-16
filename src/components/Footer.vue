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
            <div class="footer-bottom-contained">
                <div class="sign-up-container">
                    <button><a href="#"> sign-up now! </a></button>
                </div>

                <div class="follow-container">
                    <h5>follow us</h5>
                    <a href="https://www.facebook.com/dc"><img src="../assets/img/footer-facebook.png" alt=""></a>
                    <a href="https://twitter.com/DCComics"><img src="../assets/img/footer-twitter.png" alt=""></a>
                    <a href="https://www.youtube.com/dcentertainment"><img src="../assets/img/footer-youtube.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
                </div>
            </div>
          
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
                                    a:hover {
                                        text-decoration: underline;
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
        padding: 2em;
        background-color: rgba(0, 0, 0, 0.816);
        display: flex;
        justify-content: space-between;
        align-items: center;

        .footer-bottom-contained {

            width: 70%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            .sign-up-container {

                button {
                    background-color:rgba(0, 0, 0, 0);
                    padding: 1em;
                    border: 2px solid RGB(2, 130, 249);

                    a {
                        color: white;
                        text-transform: uppercase;
                        text-decoration: none;
                        font-weight: bold;
                    }

                    a:hover {
                        text-decoration: underline;
                    }


                }
            }

            .follow-container {

                display: flex;
                align-items: center;
                gap: 10px;
                h5 {
                    color: RGB(2, 130, 249);
                    text-transform: uppercase;
                    font-size: 1.3em;
                }

                img {
                     margin-left: 2%;
                }

                img:hover {
                    border:2px solid RGB(2, 130, 249);
                    border-radius: 50%;
                }
            }
        }
    }
</style>