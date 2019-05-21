<template>
  <v-card class="row skills">
    <span class="skills-title">Ключевые навыки</span>
    <div class="skills-div">
      <v-chip>HTML</v-chip>
      <v-chip>CSS</v-chip>
      <v-chip>Bootstrap</v-chip>
      <v-chip>JavaScript</v-chip>
      <v-chip>Git</v-chip>
      <v-chip>XML</v-chip>
      <v-chip>Adobe Photoshop</v-chip>
      <v-chip>Vue.js</v-chip>
    </div>
  </v-card>
</template>

<script>
export default {
  name: "Skills",
  components: {},
  data() {
    return {};
  }
};
</script>

<style>
.skills {
  background-color: white;
  flex-direction: column;
  position: sticky;
  top: 0;
  margin-top: 150px;
  text-align: center;
}

.skills-title {
  font-family: "Anton", sans-serif;
  font-size: large;
  font-weight: 500;
  letter-spacing: 1px;
  border-bottom: 1px solid lightgray;
  color: lightgray;
  margin-top: 20px;
  display: inline-block;
}

.skills-div {
  margin-top: 15px;
  text-align: center;
}

.v-chip {
  display: inline-flex;
  margin-top: 10px;
  margin-left: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}
</style>

