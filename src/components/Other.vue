<template>
  <v-card class="row other">
    <span class="other-title">Другое</span>
    <div class="otehr-div">
      <p class="other-text">
        Занимаюсь программированием на протяжении полугода. На данный момент обучаюсь на курсах Frent-end-разработчика организации GeekBrains.
        Помимо обучения на курсах, стараюсь создавать свои проекты, что помогает мне дополнительно практиковаться. Закончила лингвистический университет, однако,
        начав изучать программирование, поняла, что эта сфера мне гораздо ближе. Увлекаюсь спортом и рисованием. Стремлюсь развиваться и учиться чему-то новому.
      </p>
    </div>
  </v-card>
</template>

<script>
export default {
  name: "Other",
  components: {},
  data() {
    return {};
  }
};
</script>

<style>
.other {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  background-color: white;
  flex-direction: column;
  border-radius: 10px;
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  text-align: center;
}

.other-title {
  font-family: "Anton", sans-serif;
  font-size: large;
  font-weight: 500;
  letter-spacing: 1px;
  border-bottom: 1px solid lightgray;
  color: lightgray;
  margin-top: 20px;
  display: inline-block;
}

.other-div {
  display: flex;
  justify-content: space-around;
  margin-top: 15px;
}

.other-text {
  margin: 0 30px;
  text-align: justify;
}
</style>

