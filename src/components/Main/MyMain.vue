<template>
  <div>
    <!-- blocco fumetti -->
    <div id="content">
        <h1>Content goes here</h1>
    </div>

    <!-- riga blu -->
    <div id="products">
      <a href="" v-for="(product, i) in products" :key="i">
        <img :src="product.img" alt="">
        <span>{{product.name}}</span>
      </a>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'MyMain',
    data () {
      return {
        products : [
          {
            img : require("../../assets/buy-comics-digital-comics.png"),
            name : "DIGITAL COMICS"
          },
          {
            img : require("../../assets/buy-comics-merchandise.png"),
            name : "DC MERCHANDISE"
          },
          {
            img : require("../../assets/buy-comics-subscriptions.png"),
            name : "SUBSCRIPTION"
          },
          {
            img : require("../../assets/buy-comics-shop-locator.png"),
            name : "COMIC SHOP LOCATOR"
          },
          {
            img : require("../../assets/buy-dc-power-visa.svg"),
            name : "DC POWER VISA"
          }
        ]
      }
    }
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
    }
  }
</style>