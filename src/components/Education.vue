<template>
  <v-card class="row education" id="education">
    <span class="ed-title">Образование</span>
    <div class="ed-div">
      <div class="first-ed">
        <div class="period">
          <span class="period-span">2018 - 2019 гг.</span>
        </div>
        <div class="place">
          <span class="org-name">GeekBrains</span>
          <p>Frontend- разработчик</p>
        </div>
      </div>
      <div class="second-ed">
        <div class="period">
          <span class="period-span">2013 - 2017 гг.</span>
        </div>
        <div class="organisation">
          <span class="org-name">Московский государственный лингвистический университет, Москва</span>
          <p>Факультет английского языка, Теория и методика преподавания иностранных языков и культур</p>
        </div>
      </div>
    </div>
  </v-card>
</template>

<script>
export default {
  name: "Education",
  components: {},
  data() {
    return {};
  }
};
</script>

<style>
.education {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  background-color: white;
  flex-direction: column;
  border-radius: 10px;
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  text-align: center;
}

.ed-title {
  font-family: "Anton", sans-serif;
  font-size: large;
  font-weight: 500;
  letter-spacing: 1px;
  border-bottom: 1px solid lightgray;
  color: lightgray;
  margin-top: 20px;
  display: inline-block;
}

.first-ed,
.second-ed {
  display: flex;
  justify-content: space-around;
  margin-top: 15px;
}

.period {
  margin-top: 10px;
  max-width: 115px;
}

.place {
  width: 440px;
}

.org-name {
  font-weight: 700;
}

.organisation {
  margin-top: 10px;
  max-width: 440px;
  text-align: justify;
}
</style>

