<template>
  <div class="main-page">
    <navBar></navBar>
    <div class="main-page__about-platform">
      <div class="about-platform__info-sector">
        <div class="info-sector__title">
          Занимайтесь <br />
          с тренером <span>онлайн</span>
        </div>
        <div class="info-sector__sub-title">
          Выберите тренера, запланируйте занятие и начните заниматься по
          видеозвонку в удобное время и месте
        </div>
        <div class="info-sector__list-info">
          <ul class="list-info">
            <li>
              <i class="fa fa-check"> </i> Подберите оптимальную программу и
              тренера
            </li>
            <li><i class="fa fa-check"> </i> Занятия 1 на 1 в удобное время</li>
            <li><i class="fa fa-check"> </i> От 500 руб. за тренирвку</li>
          </ul>
        </div>
        <div class="info-sector__button">НАЧАТЬ СЕЙЧАС</div>
        <div
          class="info-sector__sub-title info-sector__sub-title__align-center"
        >
          Первая тренировка бесплатно!
        </div>
      </div>
      <div class="about-platform__images-sector">
        <img src="../../resources/scale_1200 .png" alt="" />
        <div class="images-sector__online-trainer">
          <div class="online-trainer__arrow">
            <span>Онлайн тренер</span>
            <img src="../../resources/up-arrow 1 (1).png" alt="" />
          </div>
          <img
            src="../../resources/576164130689931d518b456b_5a376258c93ce.png"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import navBar from "../nav-bar/nav-bar.vue";

export default {
  name: "MainPage",
  components: {
    navBar,
  },
};
</script>
<style>
.main-page {
  width: 100%;
  height: 100%;
}
.main-page__about-platform {
  padding-top: 150px;
  margin-left: auto;
  margin-right: auto;
  width: 90%;
  display: flex;
  justify-content: space-between;
}
.about-platform__info-sector {
  max-width: 622px;
  padding-top: 50px;
}
.info-sector__title {
  font-style: normal;
  font-weight: 500;
  font-size: 50px;
  line-height: 61px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #353535;
  margin-bottom: 25px;
}
.info-sector__title span {
  color: #8dce76;
  background: url("../../resources/Vector 2.png");
  background-repeat: no-repeat;
  background-position-y: 100%;
}
.info-sector__sub-title {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 22px;
  letter-spacing: 0.1em;
  color: #353535;
  margin-bottom: 30px;
  max-width: 630px;
}
.list-info {
  list-style: none;
  margin-bottom: 32px;
  width: 100%;
}

.list-info li {
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 26px;
  font-family: "San Francisco Pro", sans-serif;
  letter-spacing: 0.1em;
  color: #353535;
  position: relative;
  margin-bottom: 15px;
  padding-left: 10px;
}

.list-info i {
  color: #353535;
}
.info-sector__button {
  width: 622px;
  height: 60px;
  background: #8dce76;
  border-radius: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #ffffff;
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 27px;
  letter-spacing: 0.1em;
  margin-bottom: 5px;
}
.info-sector__sub-title__align-center {
  text-align: center;
}
.about-platform__images-sector {
}
.images-sector__online-trainer {
  display: flex;
  justify-content: space-between;
  max-width: 490px;
  position: relative;
  bottom: 260px;
  left: 360px;
}
.online-trainer__arrow {
  display: flex;
  padding-bottom: 40px;
  align-items: flex-end;
}
.online-trainer__arrow span {
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 24px;
  text-align: justify;
  letter-spacing: 0.1em;
  color: #353535;
  margin-right: 5px;
}
 
  
</style>