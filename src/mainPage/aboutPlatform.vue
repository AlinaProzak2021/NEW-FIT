<template>
  <div class="about-platform">
    <div class="about-platform__content">
      <div class="about-platform__main-info">
        <div class="abaut-platform__title">
          Занимайтесь <br />
          с тренером <span>онлайн</span>
        </div>
        <div class="about-platform__subtitle">
          Выберите тренера, запланируйте занятие и начните заниматься по
          видеозвонку в удобное время и месте
        </div>
        <ul class="about-platform__list-info">
          <li class="list-info__item">
            <span class="checkMark">✓</span>Подберем оптимальную программу и
            тренера
          </li>
          <li class="list-info__item">
            <span class="checkMark">✓</span>Занятия 1 на 1 в удобное время
          </li>
          <li class="list-info__item">
            <span class="checkMark">✓</span>от 500 рублей за тренировку
          </li>
        </ul>
        <button class="about-platform__button">НАЧАТЬ СЕЙЧАС</button>
        <div class="about-platform__subtitle about-platform__subtitle__center">
          Первая тренировка бесплатно!
        </div>
      </div>
      <div class="about-platform__image-content">
        <div class="image-content__main-item">
          <img src="../../resources/scale_1200 .png" alt="" />
        </div>
        <div class="image-content__side-item">
          <div class="image-content__arrow">
            <span>Онлайн тренер</span>
            <img src="../../resources/up-arrow 1 (1).png" alt="" />
          </div>
          <img src="../../resources/train2.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.about-platform {
  font-family: "Inter", sans-serif;
  width: 100%;
  height: 100%;
  font-style: normal;
}
.about-platform__content {
  width: 90%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin: 0 auto;
}
.about-platform__main-info {
  width: 660px;
}
.abaut-platform__title {  
 margin-top: 90px;
  font-weight: 500;
  font-size: 50px;
  line-height: 61px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #353535;
  margin-bottom: 26px;
}
.abaut-platform__title > span {

  color: #8dce76;
  background: url("../../resources/Vector 2.png");
  background-repeat: no-repeat;
  background-position: bottom;
}
.about-platform__subtitle {
  font-weight: 400;
  font-size: 18px;
  line-height: 22px;
  letter-spacing: 0.1em;
  max-width: 550px;
  color: #353535;
  margin-bottom: 30px;
}
.about-platform__list-info {
  margin-bottom: 32px;
}
ul {
  list-style: none;
}
.list-info__item {
  font-weight: 500;
  font-size: 22px;
  line-height: 27px;
  text-align: justify;
  letter-spacing: 0.1em;
  margin-bottom: 7px;
}
.checkMark {
  font-weight: 600;
  font-size: 18px;
  line-height: 22px;
  letter-spacing: 0.1em;
  margin-right: 40px;
}
.about-platform__button {
  width: 622px;
  height: 60px;
  left: 146px;
  top: 610px;
  background: #8dce76;
  border-radius: 5px;
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 27px;
  text-align: justify;
  letter-spacing: 0.1em;
  color: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
  margin-bottom: 5px;
}
.about-platform__subtitle__center {
  text-align: center;
  max-width: 95%;
}
.about-platform__image-content {
  display: flex;
  position: relative;
}
.image-content__main-item {
  width: 747px;
  height: 498px;
}

.image-content__main-item img {
  width: 100%;
  border-radius: 20px;
  height: 100%;
}
.image-content__arrow {
  display: flex;
  width: 175px;
  height: 30px;
  align-items: center;
  justify-content: space-between;
  position: relative;
  top: 290px;
}
.image-content__side-item {
  display: flex;
  width: 445px;
  justify-content: space-between;
  position: absolute;
  top: 250px;
  right: -110px;
}

.image-content__arrow img {
  height: 22.52px;
  width: 49.77px;
}
</style>