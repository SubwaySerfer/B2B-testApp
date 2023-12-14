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
        <img class='video-info__icon' src="/public/assets/icons/home/youtube-promo-icon.svg" alt="youtube icon.">
        <p class="video-info__description">Узнайте больше<span class="video-info__description__small"> о туре за 1
            минуту</span></p>
      </div>
      <div><button>забронировать тур</button>
        <p>Выбирайте для себя лучшее.
          Отправляйтесь в невероятное мебельное путешествие в Китай с нами!
        </p>
      </div>
      <div>
        <p>Собственная ТК –
          несём полную ответственность

          Лично убедитесь
          в качестве мебели</p>
      </div>
      <figure><img src="/public/assets/images/home/lamp-image.png" alt="backgroung lamp."></figure>
      <img src="/public/assets/images/home/sofa-image.png" alt="orange sofa with pillow.">
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