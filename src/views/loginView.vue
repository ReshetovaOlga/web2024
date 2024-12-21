<script setup>

</script>

<template>
  <main>
    <div class="container-main-login">
      <section class="list-login">
        <h1>Авторизация</h1>
        <form class="login-box" method="post">
          <div>
            <div class="error"> заполните логин</div>
            <input name="Username" type="username" placeholder="логин">
          </div>
          <div>
            <div class="error"> заполните пароль</div>
            <input name="Password" type="password" placeholder="пароль">
          </div>
          <div>
            <button class="but-myth"> ввести </button>
          </div>
        </form>

        <label class="from-row">
          <input type="checkbox" class="checkbox" >
          запомнить меня
        </label>
      </section>
    </div>
  </main>
</template>

<style scoped>

</style>