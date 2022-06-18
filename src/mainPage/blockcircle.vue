<template>
  <div class="container">
    <div class="coach-item" v-for="key in listCoaches" :key="key">
      <div class="coach__photo">
        <img :src="`${key.photo}`" alt="" />
      </div>
      <div class="coach__name">{{key.name}}</div>
      <div class="coach__services">{{key.services}}</div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      listCoaches: [
        {
          name: "Татьяна",
          photo: require('../../resources/tany.png'),
          services:
            "третчинг, силовой тренинг, функциональный тренинг, здоровая спина",
        },
        {
          name: "Ильмира",
          photo: require('../../resources/Ilia.png'),
          services: "Силовые и функциональные тренировки, стретчинг",
        },
        {
          name: "Илья",
          photo: require('../../resources/22-1.png'),
          services: "Силовой тренинг, TRX, здоровая спина",
        },
      ],
    };
  },
};
</script>
<style>
.container {
  display: flex;
  width: 50%;
}
.coach-item {
  width: 311px;
}
.coach__photo {
  width: 311px;
  height: 389px;
  border-radius: 20px;
}
.coach__photo img{
  width: 100%;
  height: 100%;
}
.coach__name,
.coach__services {
  font-family: "Inter", sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 24px;
  letter-spacing: 0.1em;
  color: #353535;
}
</style>