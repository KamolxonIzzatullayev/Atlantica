<template>
  <div class="c-co-main-header">
    <div class="container-fluid">
      <nav>
        <div class="navbar">
          <ul class="navbar-users__list d-flex">
            <li>
              <nuxt-link to="#">Производители</nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Поставщики</nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Услуги</nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Консультанты</nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Служба поддержки</nuxt-link>
            </li>
          </ul>
          <ul class="navbar-auth__list d-flex">
            <li>
              <nuxt-link to="#"></nuxt-link>
            </li>
            <li>
              <nuxt-link to="#"></nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Русский</nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Регистрации</nuxt-link>
            </li>
            <li>
              <nuxt-link to="#">Войти</nuxt-link>
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.c-co-main-header {
  background: #232f3f;
  border-bottom: 1px solid rgba(251, 251, 251, 0.2);
  .container-fluid {
    padding: 0 4rem;
  }
  .navbar {
    &-users__list {
      list-style: none;
      margin-bottom: 0;
      padding: 0;
      li {
        margin-right: 1rem;
        a {
          color: white;
        }
      }
    }

    &-auth__list {
      list-style: none;
      margin-bottom: 0;
      padding: 0;
      li {
        margin-left: 1rem;
        a {
          color: white;
        }
      }
    }
  }
}
</style>
