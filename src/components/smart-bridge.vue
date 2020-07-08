<template>
  <div class='smart'>
    <img class='logo' src="../assets/logo.png" alt="">
    <div class='text'>
      <p class='text__title'>
        Smart Bridge
      </p>
      <p class='text__description'>
        <b>Задача :</b> Разработать платформу для <br> правительственных услуг. <br> <br> <b>Решение :</b> Наша команда 
        приняла участие в проекте<br> SmartBridge. Цель проекта — это создание единой <br> платформы для всей информации 
        в системе и базе <br> данных государственных учреждений, обеспечение <br> взаимодействия, обмена и контроля
        целостности <br> данных для внутренней и внешней системы.
      </p>
      <div class='technologies'>
        <img src="../assets/detail.png" alt="">
        <p class='technologies__text'>
          <b>Технологии:</b> <br> Frontend – ReactJS
        </p>
      </div>
    </div>
    <div class='smart__image'>

    </div>
  </div>
</template>

<style lang="scss" scoped>
.smart {
  position: relative;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  &__image {
    background: url(../assets/smart_bridge.png);
    width: 55.3472%;
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
    color: #194985;
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