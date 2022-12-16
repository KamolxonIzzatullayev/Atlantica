<template>
  <div class="c-cu-login-form login-form">
    <h1 class="login-form__title">ВОЙТИ</h1>
    <p class="login-form__desc mb-3">
      Подпишитесь, чтобы получать последние обновления на вещи тебя это
      интересует
    </p>
    <div class="input-group mb-3">
      <input
        type="text"
        class="form-control"
        placeholder="Recipient's username"
        aria-label="Recipient's username"
        aria-describedby="basic-addon2"
      />
      <span class="input-group-text" id="basic-addon2">@example.com</span>
    </div>
    <div class="input-group mb-3">
      <input
        type="text"
        class="form-control"
        placeholder="Recipient's username"
        aria-label="Recipient's username"
        aria-describedby="basic-addon2"
      />
      <span class="input-group-text" id="basic-addon2">@example.com</span>
    </div>
    <p class="login-form__desc">Забыл пароль ?</p>
    <button class="login-form__btn">ВОЙТИ</button>
    <p class="login-form__desc">
      У вас нет аккаунта? <span> Зарегистрироваться сейчас</span>
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "./LoginPanel.style.scss";
</style>
