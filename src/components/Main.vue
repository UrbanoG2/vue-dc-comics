<template>
  <div class="main-container">
      <div class="content-container">
          --> Content goes here
      </div>
      <div class="cards-container">
          <ul>
              <li><img src="../assets/img/buy-comics-digital-comics.png" alt=""></li>
          </ul>
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

        .content-container {
        width: 100%;
        height: 200px;
        background-color: rgba(0, 0, 0, 0.823);
        color: white;
        font-size: 2em;
        }

        .cards-container {
            background-color: RGB(2, 130, 249);
        }


    }
</style>