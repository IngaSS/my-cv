<template>
    <v-card class="row about-me" id="aboutMe">
      <div class="inf">
        <div class="photo" style="border-radius: 125px;"></div>
        <span class="my-name">Инга Гулина</span>
      </div>
      <div class="my-inf">
        <span class="aboutme-span">Обо мне</span>
        <p class="my-inf-p">
          Я начинающий Front-end-разработчик,
          изучаю язык программирования JavaScript и фреймворк Vue.js.
          Также, планирую в ближайшее время начать осваивать React.js.
          Очень хочу развиваться в данной области, узнавать как можно больше нового,
          работать в команде сильных технических специалистов и набираться опыта.
        </p>
      </div>
      <div class="row info-div">
        <div class="first">
          <span class="info-span">Адрес</span>
          <p class="text">Москва, Немчиновка, ул. Связистов, д. 4</p>
          <span class="info-span">E-mail</span>
          <p class="text">guingg@inbox.ru</p>
          <span class="info-span">Телефон</span>
          <p class="text">+7-977-910-34-30</p>
        </div>
        <div class="second">
          <span class="info-span">Дата рождения</span>
          <p class="text">14.01.1996</p>
          <span class="info-span">Пол</span>
          <p class="text">Женский</p>
          <span class="info-span">Семейное положение</span>
          <p class="text">Не замужем</p>
        </div>
      </div>
    </v-card>
</template>

<script>
export default {
  name: "Aboutme",
  components: {},
  data() {
    return {};
  }
};
</script>

<style>
.about-me {
  background-color: white;
  max-width: 600px;
  min-height: 320px;
  margin: -150px auto;
  display: flex;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  border-radius: 10px;
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  justify-content: center;
}

.inf {
  text-align: center;
  width: 275px;
}

.my-name {
  font-family: "Anton", sans-serif;
  color: #379c96;
  font-size: large;
  font-weight: 900;
  line-height: 40px;
}

.photo {
  width: 250px;
  height: 250px;
  background-image: url(../img/pic.jpg);
  margin-top: 10px;
  margin-left: 10px;
  display: -webkit-box;
}

.my-inf {
  margin-top: 30px;
  width: 290px;
}

.aboutme-span {
  font-family: "Anton", sans-serif;
  font-size: large;
  font-weight: 900;
  letter-spacing: 1px;
  border-bottom: 1px solid #379c96;
}

.my-inf-p {
  margin-top: 10px;
  max-width: 280px;
  text-align: justify;
}

.info-div {
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}

.first,
.second {
  width: 260px;
}

.info-span {
  font-weight: bold;
  float: left;
  max-width: 125px;
  text-align: left;
}

.text {
  max-width: 135px;
  margin: 0;
  margin-left: 125px;
}

@media screen and (max-width: 770px) {
  .about-me {
    background-color: white;
    max-width: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: 0 auto;
    text-align: -webkit-center;
  }
}
</style>

