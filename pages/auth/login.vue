<template>
  <div class="p-login login">
    <div class="container-fluid">
      <div
        class="login-header d-flex justify-content-between align-items-center"
      >
        <div class="login-header__logo">
          <main-logo></main-logo>
        </div>
        <div class="login-header__lang text-light">Русский</div>
      </div>
      <div class="login-body row">
        <div class="login-body__form col-5">
          <login-panel></login-panel>
        </div>
        <div class="login-body__back col-7"></div>
      </div>
    </div>
  </div>
</template>

<script>
import MainLogo from "../../components/Custom/Icons/MainLogo.vue";
import LoginPanel from "../../components/Custom/LoginForm/LoginPanel.vue";
export default {
  components: {
    MainLogo,
    LoginPanel,
  },
};
</script>

<style></style>
