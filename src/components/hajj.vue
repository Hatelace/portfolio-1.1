<template>
  <div class='strayple'>
    <img class='logo' src="../assets/logo.png" alt="">
    <div class='text'>
      <p class='text__title'>
        Hajj & Umrah
      </p>
      <p class='text__description'>
       <b> Задача :</b> Разработка мобильного приложения для <br> туристического агентство Хикмет. <br><br> <b>Решение :</b> 
       Мы сделали приложение, которое <br> поможет вам совершать Хадж и Умру самыми <br> творческими способами. 
       Здесь собраны сотни Дуа <br> и Зикр из Корана и Сунны, которые вы сможете выучить <br> или прочитать в любое время. 
       Контрольный список <br> Рамадана поможет вам провести священный месяц <br> Рамадан продуктивно и осознанно. 
       Выбирай свои цели <br> и следи за собой, увеличивай свое благочестие!
      </p>
      <div class='technologies'>
        <img src="../assets/detail.png" alt="">
        <p class='technologies__text'>
          <b>Технологии:</b> <br>Backend – Python <br>a Frontend – Android(Kotlin), iOS(Swift)
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
    background: url(../assets/hajj.png);
    width: 45.4166666%;
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
  margin-top: 42px;
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