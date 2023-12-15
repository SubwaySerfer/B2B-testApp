<template>
  <section class="home-promo">
    <div class="home-promo__main-block">
      <h1 class="main-block__label">Мебельные туры<br>
        <span class="main-block__label__white">с полным сопровождением</span>
      </h1>
      <h3 class="main-block__info">Экономия до 500% <span class="main-block__info__white">
          по сравнению <br>
          с заказами из Европы и РФ
        </span>
      </h3>
    </div>
    <div class="home-promo__info-block">
      <div class="info-block__video-info">
        <img class='video-info__icon' src="/assets/icons/home/youtube-promo-icon.svg" alt="youtube icon.">
        <p class="video-info__description">Узнайте больше<span class="video-info__description__small"> о туре за 1
            минуту</span></p>
      </div>
      <div class="info-block__order">
        <figure class="order__background">
          <button class="order__btn btn">забронировать тур</button>
        </figure>
        <p class="order__description">Выбирайте для себя лучшее.
          Отправляйтесь в невероятное мебельное путешествие в Китай с нами!
        </p>
        <img src="/assets/icons/home/arrow-promo-icon.svg" alt="arrow icon from description to button.">
      </div>
      <div class="info-block__aside-info">
        <p class="aside-info__text">Собственная ТК –
          <span class="aside-info__text__white">несём полную ответственность</span>
        </p>
        <p class="aside-info__text">Лично убедитесь
          <span class="aside-info__text__white">в качестве мебели</span>
        </p>

      </div>
      <figure class="info-block__back-lamp"><img src="/assets/images/home/lamp-image.png" alt="backgroung lamp."></figure>
      <img class="info-block__sofa-img" src="/assets/images/home/sofa-image.png" alt="orange sofa with pillow.">
    </div>ideeo-i
  </section>
</template>

<style scoped>
.home-promo {
  height: 1105px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 8.9rem 0;
  background-image: url('/assets/images/home/back-image.png');
  /* TODO: сделать сверху фильтр */
  color: #F0D683;
  font-family: Noto Sans;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

.home-promo__main-block {
  display: flex;
  flex-direction: column;
  max-width: 79.2rem;
  gap: 3.2rem;
}

.main-block__label {
  text-align: center;
  font-family: Oranienbaum;
  font-size: 5.6rem;
  font-style: normal;
  font-weight: 400;
  line-height: 120%;
  letter-spacing: 0.28rem;
  text-transform: uppercase;
}

.main-block__label__white {
  color: #FFF;
}

.main-block__info {
  text-align: center;
  font-size: 3rem;
  font-style: normal;
  font-weight: 700;
  line-height: 130%;
}

.order__background {
  width: 26.3rem;
  height: 6.8rem;
  background: linear-gradient(90deg, #67310A -108.98%, #F0D683 129.77%);
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: .4rem .5rem;
}

.info-block__order {
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  gap: 1.6rem;
}

.order__description {
  color: #fff;
  width: 25.7rem;
  text-align: center;
  font-size: 1.2rem;
  line-height: 130%;
}

.info-block__aside-info {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  align-items: center;
  grid-area: 1 / 4 / 3 / 5;
  width: 27.3rem;
  padding: 6.8rem 4.2rem 0 4.3rem;
  height: 37.2rem;
  border-radius: 2rem;
  border: 2px solid #9F734C;
  background: linear-gradient(348deg, rgba(240, 214, 131, 0.50) 6.97%, rgba(123, 63, 10, 0.50) 95.39%);
}

.aside-info__text {
  width: 18.8rem;
  text-align: center;
  font-size: 1.8rem;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
}

.aside-info__text__white {
  color: #fff;
  font-weight: 400;

}

.main-block__info__white {
  color: #FFF;
  font-weight: 400;
}

.home-promo__info-block {
  display: grid;
  width: 100%;
  height: 600px;
  grid-template-rows: repeat(3, 1fr);
  grid-template-columns: repeat(5, 1fr);
}

.info-block__sofa-img {
  grid-area: 2 / 1 / 3 / 5;
}

.info-block__back-lamp {
  grid-area: 1 / 5 / 3 / 6;
}

.info-block__video-info {
  width: 26rem;
  height: 12rem;
  border-radius: 1.5rem;
  background: linear-gradient(180deg, #062B2E 0%, #17868D 50.52%, #17868D 100%);
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 2.4rem;
  padding: 2.6rem;
}

.video-info__icon {
  width: 6.8rem;
  height: 6.8rem;
}

.video-info__description {
  color: #FFF;
  text-align: start;
  font-family: Noto Sans;
  font-size: 1.6rem;
  font-weight: 700;
  line-height: 130%;

}

.video-info__description__small {
  font-weight: 400;
}
</style>