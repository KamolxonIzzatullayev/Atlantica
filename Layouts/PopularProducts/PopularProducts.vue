<template>
  <div class="l-popular-products">
    <div class="container-fluid">
      <h1>Хиты продаж</h1>
      <div class="row">
        
      </div>
      <ProductCard
        :name="product.name"
        :owner="product.owner"
        :rating="product.rating"
        :soldNumber="product.soldNumber"
        :shipNamer="product.shipNamer"
        :status="product.status"
        :price="product.price"
        :img="product.img"
      ></ProductCard>
    </div>
  </div>
</template>

<script>
import ProductCard from "../../components/Common/ProductCard/ProductCard.vue";

export default {
  components: { ProductCard },
  data() {
    return {
      product: {
        name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
        owner: "Xiaomi",
        rating: 4.0,
        soldNumber: 102,
        shipNamer: "Datlan",
        status: "Platinum",
        price: "$ 510.00",
        img: "images/productImage.png",
      },
    };
  },
};
</script>

<style lang="scss" scoped>
@import "./PopularProducts.style.scss";
</style>
