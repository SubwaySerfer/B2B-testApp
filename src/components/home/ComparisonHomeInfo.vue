<template>
  <section class="home-comparison">
    <div class="home-comparidon__info-block">
      <ul class="info-block__content-adventures">
        <li class="content-adventures__elem">
          <h3 class="elem__label">15+</h3>
          <p class="elem__description">лет опыта в мебельных турах</p>
        </li>
        <li class="content-adventures__elem">
          <h3 class="elem__label">700+</h3>
          <p class="elem__description">доставленных контейнеров</p>
        </li>
        <li class="content-adventures__elem">
          <h3 class="elem__label">2+</h3>
          <p class="elem__description">млрд руб. сэкономили клиентам на покупке мебели</p>
        </li>
        <li class="content-adventures__elem">
          <h3 class="elem__label">15</h3>
          <p class="elem__description">опытных сотрудников в России</p>
        </li>
        <li class="content-adventures__elem">
          <h3 class="elem__label">10</h3>
          <p class="elem__description">штатных сотрудников в Китае</p>
        </li>
      </ul>
    </div>
    <h2 class="home-comparison__label"><span class="home-comparison__label__gold">95% магазинов</span> заказывают мебель
      из Китая и не только в России, но весь остальной мир!</h2>
    <div>
      <div></div>
      <div></div>
      <div></div>
    </div>
  </section>
</template>

<style scoped>
.home-comparison {
  height: 1332px;
  background: linear-gradient(180deg, #010E0F 79.28%, rgba(1, 14, 15, 0.00) 100%);
  color: #FFF;
  font-family: Noto Sans;
  font-size: 2.4rem;
  font-style: normal;
  padding-top: 21.9rem;
  font-weight: 400;
  line-height: 130%;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
}

.home-comparidon__info-block {
  height: 27.3rem;
  width: 150.1rem;
  padding: 1rem;
  border-radius: 4.1rem;
  background: #010E0F;
  position: absolute;
  top: -15.6rem;
  /* transform: translateY(-15.6rem); */
  margin-right: .8rem;
}

.info-block__content-adventures {
  list-style-type: none;
  display: flex;
  flex-direction: row;
  gap: 7.1rem;
  padding: 3.6rem 3.73rem 0;
  height: 100%;
  border-radius: 3.5rem;
  border: 2px solid #9F734C;
  align-items: start;
  justify-content: space-between;
  width: 100%;
}

.content-adventures__elem {
  display: flex;
  flex-direction: column;
  /* gap: 1rem; */
  height: min-content;
  align-items: center;
  justify-content: start;
}

.elem__label {
  color: #F0D683;
  text-align: center;
  font-family: Oranienbaum;
  font-size: 8rem;
  font-style: normal;
  font-weight: 400;
  line-height: 120%;
  letter-spacing: 0.4rem;
  text-transform: uppercase;
}

.elem__description {
  color: #FFF;
  font-family: Noto Sans;
  font-size: 2rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  max-width: 22.7rem;
  transform: translateY(-.7rem);
}

.home-comparison__label {
  color: #FFF;
  font-family: Oranienbaum;
  font-size: 4rem;
  font-style: normal;
  font-weight: 400;
  line-height: 130%;
  letter-spacing: 0.12rem;
  text-transform: uppercase;
  width: 91.6rem;
  text-align: center;
  padding-right: 7px;
}

.home-comparison__label__gold {
  color: #ECD180;
}
</style>