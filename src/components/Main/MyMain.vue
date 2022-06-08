<template>
  <div>
    <div id="content">
        <h1>Content goes here</h1>
    </div>
    <div id="products">
      <a href="">
        <img src="../../assets/buy-comics-digital-comics.png" alt="">
        <span>DIGITAL COMICS</span>
      </a>
      <a href="">
        <img src="../../assets/buy-comics-merchandise.png" alt="">
        <span>DC MERCHANDISE</span>
      </a>
      <a href="">
        <img src="../../assets/buy-comics-subscriptions.png" alt="">
        <span>SUBSCRIPTION</span>
      </a>
      <a href="">
        <img id="shop_locator_img" src="../../assets/buy-comics-shop-locator.png" alt="">
        <span>COMIC SHOP LOCATOR</span>
      </a>
      <a href="">
        <img src="../../assets/buy-dc-power-visa.svg" alt="">
        <span>DC POWER VISA</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyMain'
}
</script>

<style scoped lang="scss">
  #content {
    background-color: black;
    padding-top: 30px;
    padding-bottom: 30px;
    padding-left: 10%;
    padding-right: 10%;

    h1 {
      color: white;
    }
  }

  #products {
    background-color: #0282f9;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding-top: 30px;
    padding-bottom: 30px;

    a {
      text-decoration: none;
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
      margin-right: 30px;

      img {
        width: 50px;
        margin-right: 10px;
      }

      span {
        color: white;
      }

      #shop_locator_img {
        width: 35px;
      }
    }
  }
</style>