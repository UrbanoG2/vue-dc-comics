<template>
  <div class="footer-background">
      <div class="top-bottom-container"> 
        <div class="footer-top">
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
                            <li><a href="">Shop Dc</a></li>
                            <li><a href="">Shop DC collectibles</a></li>

                        </ul>
                    </li>
                </ul>
            </div>

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
                        <li><a href="">Shop Dc</a></li>
                        <li><a href="">Shop DC collectibles</a></li>

                    </ul>
                </li>
            </ul>
            </div>

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
                            <li><a href="">Shop Dc</a></li>
                            <li><a href="">Shop DC collectibles</a></li>

                        </ul>
                    </li>
                </ul>
            </div>
            

           
        </div>

        <div class="footer-bottom">
            
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
    .footer-background {
        width: 100%;
        background-image: url(../assets/img/footer-bg.jpg);

        .top-bottom-container {
            width: 70%;
            margin: 0 auto;
            display: flex;

            .footer-top {
                width:60%;
                padding: 2em 0;
                color: rgba(54, 44, 44, 0.503);
                display: flex;
                
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

            .footer-bottom {
                width: 100%;
                background-image: url(../assets/img/dc-logo-bg.png);
                background-position: center;
                background-repeat: no-repeat;
            }
        }
    }
</style>