<template>
  <div class="coaches">
    <div class="coaches__content">
      <div class="coaches__info">
        <div class="info-block">
          <div class="coaches__title">Почему тренеры крутые</div>
          <div class="coaches__subtitle">
            Персональный тренер сконцентрирован только на вас, покажет
            упражнения, проконтролирует технику выполнения, расскажет какой
            тренировочный процесс подойдет именно вам
          </div>
        </div>
        <div class="info-block__w800">
          <div class="coaches__title">Вместе с нами вы сможете:</div>
          <div class="coaches__list-opportunities">
            <ul>
              <li>✓ Сбросить лишний вес</li>
              <li>✓ Привести тело в тонус</li>
            </ul>
            <ul>
              <li>✓ Избавиться от болей в спине и шее</li>
              <li>✓ Регулярно заниматься спортом</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="coaches__title coaches__title__mb10">Наши тренеры</div>
      <div class="coaches__subtitle coaches__subtitle_mb50">
        Подберем для вас идеального тренера на основе ваших целей и
        предпочтений.
      </div>
      <div class="coaches__main-info">
        <div class="coaches__trains-block">
          <div
            class="coaches__types-training"
            v-for="key in listTrains"
            :key="key"
          >
            <div class="pointer">
              <div class="pointer__circle"></div>
              <div class="pointer__line"></div>
            </div>
            <div class="types-training">
              {{ key.title }}
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template> 
<script>
export default {
  data() {
    return {
      listTrains: [
        {
          title: "Все",
        },
        {
          title: "Функциональные тренировки",
        },
        {
          title: "Силовые тренировки",
        },
        {
          title: " Стретчинг",
        },
        {
          title: "Снижение веса",
        },
        {
          title: "Здоровая спина",
        },
        {
          title: "Пилатес",
        },
        {
          title: "Йога",
        },
        {
          title: "Танцы",
        },
        {
          title: "Медитация",
        },
        {
          title: "Нутрициология",
        },
      ],
    };
  },
};
</script>
<style>
.coaches {
  width: 100%;
  height: 100%;
  font-family: "Inter", sans-serif;
  font-style: normal;
}
.coaches__content {
  width: 90%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  margin: 0 auto;
  height: 100%;
}
.coaches__info {
  display: flex;
  justify-content: space-between;
  width: 100%;
}
.info-block__w800 {
  width: 750px;
}
.info-block {
  width: 700px;
}
.coaches__title {
  font-weight: 500;
  font-size: 36px;
  line-height: 44px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #353535;
  margin-bottom: 19px;
}
.coaches__title__mb10 {
  margin-bottom: 10px;
}
.coaches__subtitle {
  font-weight: 400;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: 0.1em;
  color: #353535;
}
.coaches__list-opportunities {
  display: flex;
  width: 100%;
  justify-content: space-between;
  font-weight: 400;
  font-size: 20px;
  line-height: 24px;
  text-align: justify;
  letter-spacing: 0.1em;
  color: #353535;
  flex-wrap: wrap;
}
ul {
  list-style: none;
}
.coaches__info {
  margin-bottom: 134px;
}
.coaches__subtitle_mb50{
  margin-bottom: 50px;
}
.coaches__main-info {
  display: flex;
  width: 100%;
}
.coaches__types-training {
  display: flex;
  width: 450px;
  margin-left: 5px;
}
.pointer {
  display: flex;
  margin-right: 15px;
  width: 15px;
  position: relative;
}
.pointer__circle {
  width: 10px;
  height: 10px;
  border: 1px solid #52a336;
  border-radius: 50%;
}
.pointer__line {
  width: 1px;
  height: 40px;
  background: #52a336;
  position: relative;
  bottom: 2.5px;
  right: 7px;
}
.types-training {
  font-family: "Inter", sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}
</style>