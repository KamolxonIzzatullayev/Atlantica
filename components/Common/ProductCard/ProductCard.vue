<template>
  <div class="c-co-product-card">
    <div class="product-card">
      <div class="product-card__fav">
        <img src="~/assets/icons/notLiked.svg" alt="" />
      </div>
      <div class="product-card__img">
        <img :src="require('@/assets/' + img)" alt="" />
      </div>

      <div class="product-card__owner">
        <span>
          {{ owner }}
        </span>
      </div>

      <div class="product-card__title">
        <p>
          {{ name }}
        </p>
      </div>

      <div class="product-card__statistics">
        <img src="~/assets/icons/ratingStar.svg" alt="" />
        <span class="product-card__statistics-rating">
          {{ rating }}
        </span>
        <span class="product-card__statistics-buyers">
          {{ soldNumber }} купили
        </span>
      </div>

      <div class="product-card__shipping">
        <span class="product-card__shipping-owner">
          Постщик: {{ shipNamer }}
        </span>
        <span class="product-card__shipping-status">
          <img src="~/assets/icons/platinumStatus.svg" alt="" />
          <span>{{ status }}</span>
        </span>
      </div>

      <div class="product-card__footer">
        <span class="product-card__footer-price">{{ price }}</span>
        <button><span>+</span></button>
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
      type: String,
      default: "0.0",
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
