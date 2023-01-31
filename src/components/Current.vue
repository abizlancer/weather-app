<template >
  <section class="current">
    <article class="current__day">
      <div class="current__day--temp">
        <h1><span>20°</span>Сегодня</h1>
        <img src="/img/icons/sunny.svg" alt="temp img">
      </div>
      <div class="current__day--info">
        <p class="current__day--info-time">Время: 21:54</p>
        <p class="current__day--info-city">Город: Санкт-Петербург</p>
      </div>
    </article>
    <article class="current__temp">
      <img src="/img/cloud-bg.png" class="current__temp--bg" alt="cloud bg">
      <div class="current__temp--content">
        <div class="current__temp--content--items current__temp--temp">
          <div class="current__temp--img">
            <img src="/img/icons/header/temperature.svg" alt="temperature">
          </div>
          <span>Температура</span>
          <p>20° - ощущается как 17°</p>
        </div>
        <div class="current__temp--content--items current__temp--pressure">
          <div class="current__temp--img">
            <img src="/img/icons/header/pressure.svg" alt="pressure">
          </div>
          <span>Давление </span>
          <p>765 мм ртутного столба - нормальное</p>
        </div>
        <div class="current__temp--content--items current__temp--precipitation">
          <div class="current__temp--img">
            <img src="/img/icons/header/precipitation.svg" alt="precipitation">
          </div>
          <span>Осадки</span>
          <p>Без осадков</p>
        </div>
        <div class="current__temp--content--items current__temp--wind">
          <div class="current__temp--img">
            <img src="/img/icons/header/wind.svg" alt="wind">
          </div>
          <span>Ветер</span>
          <p>3 м/с юго-запад - легкий ветер</p>
        </div>
      </div>
    </article>
  </section>
</template>

<script>
export default {
  name: "Current"  
}
</script>