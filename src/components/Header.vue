<template>
  <v-layout class="header" style="min-height: 300px;" justify-space-around row wrap>
    <div class="name">
      <span class="my-name">Гулина Инга</span>
      <p>Front-end-разработчик</p>
    </div>
    <v-toolbar-items class="nav-items" id="navbar">
      <v-btn
        flat
        class="nav-btn"
        style="color: #379c96; margin: 10px 10px 0 0; height: 40px;"
      href="#aboutMe">Обо мне</v-btn>
      <v-btn flat 
      class="nav-btn" 
      style="color: #379c96;  margin: 10px 10px 0 0; height: 40px;"
      href="#experience">Опыт</v-btn>
      <v-btn
        flat
        class="nav-btn"
        style="color: #379c96;  margin: 10px 10px 0 0; height: 40px;"
      href="#education">Образование</v-btn>
    </v-toolbar-items>
  </v-layout>
</template>

<script>


export default {
   name: "Header",
  components: {

  },
  data() {
    return {};
  }
};
</script>

<style>
.header {
  min-height: 300px;
  border-radius: 10px;
  flex-wrap: wrap;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  background-color: #404a54;
  border: 1px solid #379c96;
}

.name {
  max-width: 130px;
  padding-top: 40px;
}

.my-name {
  font-family: "Anton", sans-serif;
  font-size: large;
  font-weight: 900;
  color: #379c96;
  letter-spacing: 1px;
}

.name p {
  font-family: "Slabo 27px", serif;
  font-size: small;
  color: #379c96;
}

.nav-items {
  padding-top: 40px;
  display: inline-block;
}

.nav-btn {
  text-transform: none;
  width: 130px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  text-align: center;
}

.nav-btn:hover {
  color: black;
}

.v-btn:hover {
  background-color: lightgray;
}
</style>

