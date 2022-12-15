<template>
  <div class="l-popular-products">
    <div class="container-fluid">
      <h1>Хиты продаж</h1>
      <div class="product-list">
        <div
          class="product-list__item"
          v-for="(product, index) in products"
          :key="index"
        >
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
    </div>
  </div>
</template>

<script>
import ProductCard from "../../components/Common/ProductCard/ProductCard.vue";

export default {
  components: { ProductCard },
  data() {
    return {
      products: [
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage2.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage3.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage2.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage3.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage2.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage3.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage2.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage3.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage2.png",
        },
        {
          name: "Стиральная машина Samsung WW60A4S00CE/LD, белая",
          owner: "Xiaomi",
          rating: "4.00",
          soldNumber: 102,
          shipNamer: "Datlan",
          status: "Platinum",
          price: "$ 510.00",
          img: "images/productImage3.png",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "./PopularProducts.style.scss";
</style>
