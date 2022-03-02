<template>
  <div class="nav-bar">
    <div class="nav-bar__content">
      <div class="nav-bar__logo">
        NEW FIT
      </div>
      <div class="nav-bar__menu">
        <div class="nav-bar__menu-item">Типы тренировок</div>
        <div class="nav-bar__menu-item">ТРЕНЕРЫ</div>
        <div class="nav-bar__menu-item">ЦЕНЫ</div>
        <div class="nav-bar__menu-item nav-bar__menu-item__button">Войти</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "main-nav-bar",
};
</script>
<style>
.nav-bar {
  width: 100%;
  height: 80px;
}
@font-face {
  font-family: "San Francisco Pro";
  src: url("../../resources/SFPRODISPLAYMEDIUM.OTF");
}
.nav-bar__content {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.nav-bar__logo {
  display: flex;
  justify-content: center;
  font-family: "San Francisco Pro", sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 30px;
  line-height: 36px;
  letter-spacing: 0.095em;
  color: #353535;
  margin-left: 70px;
  align-items: center;
  background-image:url('../../resources/Vector 1 (1).png');
  background-position: center;
  width: 182.35px;
}

.nav-bar__menu {
  display: flex;
  justify-content: space-between;
  width: 50%;
  align-items: center;
  padding-right: 85px;
  height: 100%;
}
.nav-bar__menu-item {
  font-family: "San Francisco Pro", sans-serif;
  font-style: 400;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #353535;
}
.nav-bar__menu-item__button {
  width: 150px;
  height: 40px;
  background: #8dce76;
  color: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>