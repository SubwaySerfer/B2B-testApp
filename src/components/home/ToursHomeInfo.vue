<template>
  <section class="home-tours">
    <h2 class="home-tours__title">Мебельные туры <span class="home-tours__title__white">в Фошань под ключ</span></h2>
    <h3 class="home-tours__description">Предоставляем <span class="home-tours__description__gold">полный спектр
        услуг</span> и несём полную ответственность на
      каждом этапе:
    </h3>
    <div class="home-tours__main-block">
      <ul class="main-block__tours-info">
        <li class="tours-info__elem padding-top">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">01</h4><img src="/assets/icons/home/line.svg"
              alt="line icon from label to main picture." class="label-box__line">
          </div>
          <h5 class="elem__title">Организация поездки</h5>
          <p class="elem__description">От оформления визы до бронирования гостиницы</p>
        </li>
        <li class="tours-info__elem">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">02</h4><img src="/assets/icons/home/line2.svg"
              alt="line icon from label to main picture." class="label-box__line">
          </div>
          <h5 class="elem__title">Контроль качества</h5>
          <p class="elem__description">Не просто оформляем, а выполняем тщательную проверку: на складе производителя и
            перед отправкой.
            Предоставляем вам видео и фотоотчёт перед отправкой</p>
        </li>
        <li class="tours-info__elem transform-y">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">03</h4><img src="/assets/icons/home/line3.svg"
              alt="line icon from label to main picture." class="label-box__line">
          </div>
          <h5 class="elem__title">Оформление документов</h5>
          <p class="elem__description">Готовим все сопроводительные бумаги, выполняем растаможивание и доставляем товары
            прямо до вашей двери</p>
        </li>
        <li class="elem__img-box">
          <figure class="img-box__figure">
            <img src="/assets/images/home/tours-image.png" alt="Woman with champagne sits in a future armchair.">
          </figure>
          <span class="img-box__bg"></span>
        </li>
        <li class="tours-info__elem padding-top tours-info__elem__revert">
          <div class="elem__label-box elem__label-box__revert"><img src="/assets/icons/home/list-icon.svg"
              alt="dot icon.">
            <h4 class="label-box__title">04</h4><img src="/assets/icons/home/line4.svg"
              alt="line icon from label to main picture." class="label-box__line__revert">
          </div>
          <h5 class="elem__title text__revert">Транспортировка</h5>
          <p class="elem__description text__revert">Перевозим собственной ТК. Гарантируем, что все будет доставлено без
            повреждений</p>
        </li>
        <li class="tours-info__elem tours-info__elem__revert transform-bottom ">
          <div class="elem__label-box elem__label-box__revert"><img src="/assets/icons/home/list-icon.svg"
              alt="dot icon.">
            <h4 class="label-box__title">05</h4><img src="/assets/icons/home/line5.svg"
              alt="line icon from label to main picture." class="label-box__line__revert">
          </div>
          <h5 class="elem__title text__revert">Персональный <br> менеджер-переводчик</h5>
          <p class="elem__description text__revert">Более 10 лет опыта индивидуального подбора мебели</p>
        </li>
        <li class="tours-info__btn">
          <button class="btn">забронировать тур</button>
        </li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
.home-tours {
  height: 1124px;
  background: #1C1C1C;
  color: #FFF;
  text-align: center;
  font-family: Noto Sans;
  font-size: 2.4rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  padding-top: 7.1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: start;
  /* gap: 2.2rem; */
}

.home-tours__title {
  margin-right: 3rem;
  color: #F0D683;
  font-family: Oranienbaum;
  font-size: 4rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  letter-spacing: 0.12rem;
  text-transform: uppercase;
  margin-bottom: .7rem;
}

.home-tours__title__white {
  color: #FFF;
}

.home-tours__description {
  font-size: 2.4rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  width: 82rem;
  margin-bottom: 2rem;
  margin-right: 3.3rem;
}

.home-tours__description__gold {
  color: #F0D683;
  font-weight: 700;
}

.label-box__title {
  color: #F0D683;
  font-family: Oranienbaum;
  font-size: 4rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  letter-spacing: 0.12rem;
  text-transform: uppercase;
}

.elem__title {
  font-size: 1.8rem;
  font-style: normal;
  font-weight: 700;
  line-height: 130%;
  padding-left: 2.7rem;
}

.elem__description {
  font-size: 1.6rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  padding-left: 2.7rem;
}

.main-block__tours-info {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  list-style-type: none;
  align-items: center;
  justify-content: space-between;
  height: 100%;
}

.tours-info__elem {
  display: flex;
  flex-direction: column;
  align-items: start;
  width: 34.5rem;
  text-align: start;
  gap: 1rem;
}



.elem__label-box {
  display: flex;
  flex-direction: row;
  align-items: center;
  position: relative;
  padding-left: .7rem;
}

.home-tours__main-block {
  width: 100%;
  height: 66.3rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.elem__img-box {
  flex: 0 1 100%;
  width: 66.3rem;
  height: 66.3rem;
  border-radius: 66.3rem;
  margin-right: 10.3rem;
  margin-left: 10.3rem;
  /* background: radial-gradient(50% 50% at 50% 50%, #17858C 0%, rgba(4, 59, 63, 0.00) 100%); */
  display: flex;
  justify-content: center;
  align-items: center;
}

.img-box__figure {
  width: 48.1rem;
  height: 48.1rem;
  border-radius: 48.1rem;
  border: 1px solid #F0D683;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 2;
}

.img-box__bg {
  filter: blur(50px);
  background: radial-gradient(50% 50% at 50% 50%, #17858C 0%, rgba(4, 59, 63, 0.00) 100%);
  width: 66.3rem;
  height: 66.3rem;
  border-radius: 66.3rem;
  position: absolute;
  z-index: 1;
}

.label-box__line {
  position: absolute;
  top: 2.3rem;
  left: 12rem;
}

.elem__label-box__revert {
  flex-direction: row-reverse;
  align-self: flex-end;
  padding-left: 0;
  padding-right: 1rem;

}

.tours-info__elem__revert {
  align-items: end
}

.label-box__line__revert {
  right: 12rem;
  top: 2.3rem;
  position: absolute;
}

.text__revert {
  text-align: end;
  padding-left: 0;
  padding-right: 2.7rem;

}

.padding-top {
  padding-top: 1.7rem;
}

.transform-y {
  transform: translateY(2.3rem);
}

.transform-bottom {
  transform: translateY(-3.8rem);

}

.tours-info__btn {
  margin: 0 0 0.5rem 2.6rem;
  width: 26.3rem;
  height: 6.8rem;
  background: linear-gradient(90deg, #67310A -108.98%, #F0D683 129.77%);
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: .4rem .5rem;
}

@media(max-width: 1600px) {
  .elem__img-box {
    width: 34.73vw;
    height: 66.3rem;
  }

  .label-box__line__revert,
  .label-box__line {
    width: 20vw;
  }
}

@media(max-width: 1450px) {
  .elem__img-box {
    margin-right: 4vw;
    margin-left: 4vw;
  }
}

@media(max-width: 1230px) {
  .home-tours {
    height: 190rem;
    padding-bottom: 5rem;
  }

  .main-block__tours-info {
    flex-wrap: nowrap;
    row-gap: 3rem;
    width: 100vw;
  }

  .tours-info__btn {
    align-self: center;
    margin: 0;
  }

  .tours-info__elem {
    margin-right: 6vw;
  }

  .tours-info__elem__revert {
    margin-left: 6vw;
  }


}
</style>