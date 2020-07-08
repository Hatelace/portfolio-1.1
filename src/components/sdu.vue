<template>
  <div class='strayple'>
    <img class='logo' src="../assets/logo.png" alt="">
    <div class='text'>
      <p class='text__title'>
        SDU
      </p>
      <p class='text__description'>
       <b>Задача :</b> Разработка мобильного приложения <br> для объедение всех выпускников ВУЗа <br><br> <b>Решение :</b> 
       было сделано мобильное приложение для ассоциации <br> выпускников университета им. Сулеймана Демиреля с адаптивной <br> 
       версией под все мобильные устройства, которое предоставит <br> пользователю возможность переписываться, 
       загружать объявления <br> и просматривать вакансии на работу, а также доступ <br> ко всей базе выпускников.
      </p>
      <div class='technologies'>
        <img src="../assets/detail.png" alt="">
        <p class='technologies__text'>
          <b>Технологии:</b> <br> Backend – Python <br> Frontend – Android, iOS(React Native) <br> Design – Adobe XD
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
    background: url(../assets/sdu.png);
    width: 46.527777%;
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
    color: #1B213E;
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