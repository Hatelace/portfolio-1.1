<template>
  <div class='strayple'>
    <img class='logo' src="../assets/logo.png" alt="">
    <div class='text'>
      <p class='text__title'>
        QOS
      </p>
      <p class='text__description'>
        <b>Задача :</b> Мобильное приложение на платформах <br> iOS и Android, цель которого - продвижение Qpop <br> 
        индустрии в Казахстане. <br> <br> <b>Решение :</b> Был разработан мобильное приложение <br> на такие платформы, 
        как iOS и Android. <br> Основными разделами данного приложения являются: <br> - Медиатека -музыкальный плеер, 
        новые релизы, <br> исполнители, альбомы. <br> - Артисты - информация об артистах. <br> - Магазин -продажа продукции 
        лейблов. <br> - Концерты -система бронирование мест и покупки <br> онлайн билетов на концерт.
      </p>
      <div class='technologies'>
        <img src="../assets/detail.png" alt="">
        <p class='technologies__text'>
          <b>Технологии:</b> <br> Backend – Python <br> Frontend – Android(Kotlin), iOS(Swift) <br> Design – Figma
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
    background: url(../assets/qos.png);
    width: 51.9444%;
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
    margin-bottom: 26px;
    color: #01FFFF;
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
  margin-top: 26px;
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