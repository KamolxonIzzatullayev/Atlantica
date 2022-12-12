<template>
  <div class="c-co-product-card">
    <div class="product-card">
      hello
      <div class="product-card__im">
        <img :src="require('@/assets/' + img)" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      default: "",
    },
    owner: {
      type: String,
      default: "",
    },
    rating: {
      type: Number,
      default: 0.0,
    },
    soldNumber: {
      type: Number,
      default: 0,
    },
    shipNamer: {
      type: String,
      default: "",
    },
    status: {
      type: String,
      default: "",
    },
    price: {
      type: String,
      default: "$ 0.00",
    },
    img: {
      type: String,
      default: "",
    },
  },
};
</script>

<style lang="scss" scoped>
@import "./ProductCard.style.scss";
</style>
