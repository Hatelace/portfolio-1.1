<template>
  <div class='strayple'>
    <img class='logo' src="../assets/logo.png" alt="">
    <div class='text'>
      <p class='text__title'>
        Strayple
      </p>
      <p class='text__description'>
        <b>Задача :</b> Первый в Казахстане сервис по поиску <br> офисной недвижимости. Мы предоставляем <br> 
        платформу, которая облегчает весь процесс <br> поиска необходимого помещения. <br><br> <b>Решение :</b> Первый 
        в Казахстане сервис по поиску офисной <br> недвижимости. Мы предоставляем платформу, которая <br> облегчает весь 
        процесс поиска необходимого помещения. <br> Собрана самая широкая база бизнес центров по всей стране.
      </p>
      <div class='technologies'>
        <img src="../assets/detail.png" alt="">
        <p class='technologies__text'>
          <b>Технологии:</b> <br> Backend – Python <br> Frontend – VueJS <br> Design – Figma
        </p>
      </div>
    </div>
    <div class="strayple__image">
    </div>
  </div>
</template>

<style lang="scss" scoped>
.strayple {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  &__image {
    background: url(../assets/strayple.png);
    width: 57.5201%;
    height: 100%;
    background-size: 100% 100%;
  }
}
.logo {
  position: absolute;
  top: 40px;
  left: 60px;
}
.text {
  padding-left: 60px;
  &__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 47px;
    letter-spacing: 0.1em;
    margin-bottom: 63px;
    color: #171717;
  }
  &__description {
    font-family: 'Roboto';
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    color: #1D1E27;
  }
}
.technologies {
  margin-top: 29px;
  display: flex;
  align-items: flex-start;
  &__text {
    font-family: 'Roboto';
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    color: #1D1E27;
    margin-left: 12px;
    margin-top: 6px;
  }
}
</style>