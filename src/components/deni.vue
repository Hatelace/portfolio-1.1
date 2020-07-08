<template>
  <div class="deni">
    <img class='logo' src="../assets/logo.png" alt="">
    <div class='text'>
      <p class='text__title'>
        Deni Coffee
      </p>
      <p class='text__description'>
        <b>Задача :</b>  Первый в Казахстане сервис по поиску <br> офисной недвижимости. Мы предоставляем <br> платформу, 
        которая облегчает весь процесс <br> поиска необходимого помещения. <br> <br> <b>Решение :</b>  Здесь собрана 
        самая широкая база <br> бизнес центров по всей стране.
      </p>
      <div class='technologies'>
        <img src="../assets/detail.png" alt="">
        <p class='technologies__text'>
          <b>Технологии:</b> <br> Здесь собрана самая широкая база <br> бизнес центров по всей стране.
        </p>
      </div>
    </div>
    <div class='right_image'>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.deni {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
}
.logo {
  position: absolute;
  top: 40px;
  left: 60px;
}
.text {
  padding-left: 60px;
  &__title {
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 47px;
    letter-spacing: 0.1em;
    color: #FFC800;
    margin-bottom: 63px;
  }
  &__description {
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-size: 20px;
    line-height: 23px;
    color: #1D1E27;
  }
}
.technologies {
  margin-top: 75px;
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
.right_image {
  background-image: url(../assets/deni.png);
  height: 100vh;
  width: 56.805%;
  // width: 818px;
  // background-size: contain;
  // background-repeat: no-repeat;
  background-size: 100% 100%;
}
</style>