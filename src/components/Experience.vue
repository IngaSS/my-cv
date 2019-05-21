<template>
  <v-card class="row experience" id="experience">
    <span class="exp-title">Опыт работы - 1 год 11 месяцев</span>
    <div class="exp-div">
      <div class="period">
        <span class="period-span">Июль 2017 — по настоящее время</span>
      </div>
      <div class="organisation">
        <span class="exp-name">ГБОУ СОШ 806</span>
        <span class="position">Преподаватель иностранных языков</span>
        <p>
          Преподавание английского языка учащимся средней образовательной школы, исполнение обязанностей
          классного руководителя, координация сотрудничества между школой и колледжами
        </p>
      </div>
    </div>
  </v-card>
</template>

<script>
export default {
  name: "Experience",
  components: {},
  data() {
    return {};
  }
};
</script>

<style>
.experience {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  background-color: white;
  flex-direction: column;
  border-radius: 10px;
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  text-align: center;
}

.exp-title {
  font-family: "Anton", sans-serif;
  font-size: large;
  font-weight: 500;
  letter-spacing: 1px;
  border-bottom: 1px solid lightgray;
  color: lightgray;
  margin-top: 20px;
  display: inline-block;
}

.exp-div {
  display: flex;
  justify-content: space-around;
  margin-top: 15px;
}

.period {
  margin-top: 10px;
  max-width: 115px;
}

.organisation {
  margin-top: 10px;
  max-width: 440px;
  text-align: justify;
}

.exp-name {
  font-weight: 700;
}

.position {
  font-weight: 300;
  border-bottom: 0.5px solid black;
  line-height: 30px;
}
</style>


