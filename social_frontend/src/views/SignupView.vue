<template>
  <div class="flexed-container">
    <div class="flexed-container__left">
      <div class="flexed-container__content-box">
        <h1 class="flexed-container__header">Регистрация</h1>
        <p class="flexed-container__text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci temporibus deserunt debitis dolores recusandae? Ipsa repudiandae officiis ipsum laudantium, aut itaque, quas molestiae id quisquam ducimus officia illo totam nam?
        </p>
        <p class="flexed-container__text flexed-container__text_font_bold">
          Уже есть аккаунт? <RouterLink :to="{'name': 'login'}" class="link link_underlined">Нажмите здесь</RouterLink>, чтобы войти!
        </p>
      </div>
    </div>
    <div class="flexed-container__right">
      <div class="flexed-container__content-box">
        <form class="form">
          <div class="form__inputs-group">
            <label>Имя</label><br>
            <input type="text" placeholder="Ваше полное имя" class="form__input">
          </div>

          <div class="form__inputs-group">
            <label>E-mail</label><br>
            <input type="email" placeholder="Ваш e-mail адрес" class="form__input">
          </div>

          <div class="form__inputs-group">
            <label>Пароль</label><br>
            <input type="password" placeholder="Пароль" class="form__input">
          </div>

          <div class="form__inputs-group">
            <label>Повторите пароль</label><br>
            <input type="password" placeholder="Повторите пароль" class="form__input">
          </div>

          <div class="form__inputs-group">
            <button class="form__button">Зарегистрироваться</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>