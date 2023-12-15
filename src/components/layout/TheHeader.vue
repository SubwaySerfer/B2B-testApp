<template>
  <header class="header">
    <div class="header__logo-box">
      <img src="/assets/icons/header/logo.svg" alt="company logo.">
      <p class="logo-box__text">Индивидуальные мебельные туры в Китай для частных клиентов и бизнеса</p>
    </div>
    <div class="header__info-block">
      <div class="info-block__email">
        <span class="info-clock__email__title">E-mail:</span>
        <a href="Mailto:rosexpress-msk@yandex.ru" class="info-block__email__adress">rosexpress-msk@yandex.ru</a>
      </div>
      <ul class="info-block__media">
        <li><img src="/assets/icons/header/youtube-icon.svg" alt="our youtube."></li>
        <li><img src="/assets/icons/header/tg-icon.svg" alt="our telegram."></li>
        <li><img src="/assets/icons/header/vk-icon.svg" alt="out vkontakte."></li>
      </ul>
      <div class="info-block__phone">
        <a href="tel:+88003338901" class="phone__label">8 (800) 333-89-01</a>
        <a class="phone__pick-call">Обратный звонок</a>
      </div>
    </div>
  </header>
</template>

<style scoped>
.header {
  width: 100%;
  height: 10.1rem;
  background: #010E0F;
  /* filter: blur(2px); */
  display: flex;
  align-items: center;
  padding: 0 20.8rem;
  font-family: 'Noto Sans', sans-serif;
  font-size: 1.4rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  color: #E5C97B;
  justify-content: space-between;
}

.header__logo-box {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 2.5rem;
}

.logo-box__text {
  width: 19.9rem;
  text-align: start;
  padding-bottom: .4rem;
}

.header__info-block {
  display: flex;
  gap: 7.4rem;
}

.info-block__email {
  display: flex;
  flex-direction: column;
  line-height: 140%;
}

.info-clock__email__title {
  color: #767676;
  text-align: start;
}

.info-block__email__adress {
  border-bottom: 1px dashed;
  margin: 0;
  color: #F0D683;
  padding-bottom: 3px;
}

.info-block__media {
  list-style-type: none;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 2rem;
  padding-bottom: 1.1rem;
}

.info-block__phone {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  /* gap: 0.8rem; */
}

.phone__label {
  color: #FFF;
  font-family: Oranienbaum;
  font-size: 2rem;
  font-style: normal;
  font-weight: 400;
  line-height: 120%;
  letter-spacing: 0.1rem;
  text-transform: uppercase;
}

.phone__pick-call {
  border-bottom: 1px dashed;
}
</style>