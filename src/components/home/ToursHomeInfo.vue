<template>
  <section class="home-tours">
    <h2 class="home-tours__title">Мебельные туры <span class="home-tours__title__white">в Фошань под ключ</span></h2>
    <h3 class="home-tours__description">Предоставляем <span class="home-tours__description__gold">полный спектр
        услуг</span> и несём полную ответственность на
      каждом этапе:
    </h3>
    <div class="home-tours__main-block">
      <ul class="main-block__tours-info">
        <li class="tours-info__elem">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">01</h4><img src="/public/assets/icons/home/line.svg"
              alt="line icon from label to main picture.">
          </div>
          <h5 class="elem__title">Организация поездки</h5>
          <p class="elem__description">От оформления визы до бронирования гостиницы</p>
        </li>
        <li class="tours-info__elem">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">02</h4><img src="/public/assets/icons/home/line.svg"
              alt="line icon from label to main picture.">
          </div>
          <h5 class="elem__title">Контроль качества</h5>
          <p class="elem__description">Не просто оформляем, а выполняем тщательную проверку: на складе производителя и
            перед отправкой.
            Предоставляем вам видео и фотоотчёт перед отправкой</p>
        </li>
        <li class="tours-info__elem">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">03</h4><img src="/public/assets/icons/home/line.svg"
              alt="line icon from label to main picture.">
          </div>
          <h5 class="elem__title">Оформление документов</h5>
          <p class="elem__description">Готовим все сопроводительные бумаги, выполняем растаможивание и доставляем товары
            прямо до вашей двери</p>
        </li>
        <li>
          <figure class=""><img src="" alt=""></figure>
        </li>
        <li class="tours-info__elem">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">04</h4><img src="/public/assets/icons/home/line.svg"
              alt="line icon from label to main picture.">
          </div>
          <h5 class="elem__title">Транспортировка</h5>
          <p class="elem__description">Перевозим собственной ТК. Гарантируем, что все будет доставлено без повреждений</p>
        </li>
        <li class="tours-info__elem">
          <div class="elem__label-box"><img src="/assets/icons/home/list-icon.svg" alt="dot icon.">
            <h4 class="label-box__title">05</h4><img src="/public/assets/icons/home/line.svg"
              alt="line icon from label to main picture.">
          </div>
          <h5 class="elem__title">Персональный менеджер-переводчик</h5>
          <p class="elem__description">Более 10 лет опыта индивидуального подбора мебели</p>
        </li>
        <li>
          <button></button>
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
}

.elem__description {
  font-size: 1.6rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
}

.main-block__tours-info {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  list-style-type: none;
  align-items: center;
  gap: 6.4rem;
  justify-content: center;
  height: 100%;
}

.tours-info__elem {
  display: flex;
  flex-direction: column;
  align-items: start;
  width: 34.5rem;
  text-align: start;
}

.elem__label-box {
  display: flex;
  flex-direction: row;
  gap: 1.4rem;
  align-items: center;
}

.home-tours__main-block {
  width: 100%;
  height: 66.3rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>