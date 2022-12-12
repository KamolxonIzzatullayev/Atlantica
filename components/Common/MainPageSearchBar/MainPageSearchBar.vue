<template>
  <div class="c-co-main-search">
    <div class="search container-fluid">
      <nav class="navbar d-flex justify-content-between">
        <div class="search-logo">
          <main-logo></main-logo>
        </div>

        <div class="search-bar">
          <input type="text" placeholder="Поиск на атлантики" />
          <button>
            <img src="~/assets/icons/search_icon.svg" alt="" /> Поиск
          </button>
        </div>

        <div class="search-actions">
          <ul class="search-actions__list d-flex">
            <li class="search-actions__list-item">
              <img src="../../../assets/icons/login.svg" alt="" />
              <p>Кабинет</p>
            </li>
            <li class="search-actions__list-item">
              <img src="../../../assets/icons/currency.svg" alt="" />
              <p>Валюта: USD</p>
            </li>
            <li class="search-actions__list-item">
              <img src="../../../assets/icons/applications.svg" alt="" />
              <p>Запросы</p>
            </li>
            <li class="search-actions__list-item">
              <img src="../../../assets/icons/favourite.svg" alt="" />
              <p>Избранное</p>
            </li>
            <li class="search-actions__list-item">
              <img src="../../../assets/icons/cart.svg" alt="" />
              <p>Корзина</p>
            </li>
          </ul>
        </div>
      </nav>
    </div>

    <div class="filter container-fluid">
      <nav class="navbar">
        <ul class="filter-list">
          <li class="filter-list__item catalogue">
            <img src="../../../assets/icons/catalogue.svg" alt="" /> Каталог
          </li>
          <li class="filter-list__item">Товары на складе</li>
          <li class="filter-list__item">Для покупателя</li>
          <li class="filter-list__item">Поиск решений</li>
          <li class="filter-list__item">Поставщикам</li>
          <li class="filter-list__item">Помощь</li>
        </ul>

        <p class="filter-shipping">
          Доставка в: <img src="../../../assets/icons/uzb_flag.svg" alt="" />
        </p>
      </nav>
    </div>
  </div>
</template>

<script>
import MainLogo from "../../Custom/Icons/MainLogo.vue";
export default {
  components: { MainLogo },
};
</script>

<style scoped lang="scss">
@import "./MainPageSearchBar.style.scss";
</style>
