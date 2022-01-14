<template>
    <div class="header-container">
        <div class="logo-container">
            <img src="..\assets\img\dc-logo.png" alt="">
        </div>
        <ul>
            <li class="active"><a href="">characters</a></li>
            <li><a href="">comics</a></li>
            <li><a href="">movies</a></li>
            <li><a href="">tv</a></li>
            <li><a href="">games</a></li>
            <li><a href="">collectibles</a></li>
            <li><a href="">videos</a></li>
            <li><a href="">fans</a></li>
            <li><a href="">news</a></li>
            <li><a href="">shop</a></li>
        </ul>
      
  </div>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style lang="scss" scoped>

    .logo-container img {
        width: 60%;
    }

    .header-container {
        padding: 1em 0;
        width:60%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        ul {
            display: flex;
            justify-content: space-between;
            align-items: center;
            list-style: none;

            li a {
                display: block;
                text-decoration: none;
                padding: 1em;
                text-transform: uppercase;
                font-size: 10px;
                color: rgba(0, 0, 0, 0.823);
                
            }
            li:hover,
            li:active,
            li.active {
                border-bottom: 2px solid blue;
            }

            
        }
    }

</style>