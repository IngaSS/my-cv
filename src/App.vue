<template>
  <v-app data-spy="scroll" data-target="#navbar">
    <v-container style="padding: 0;">
      <Header></Header>
      <v-content>
        <Aboutme></Aboutme>
        <Skills></Skills>
        <Experience></Experience>
        <Education></Education>
        <Other></Other>
      </v-content>
    </v-container>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import Aboutme from "./components/Aboutme";
import Skills from "./components/Skills";
import Experience from "./components/Experience";
import Education from './components/Education';
import Other from "./components/Other";

export default {
  name: "App",
  components: {
    Header,
    Aboutme,
    Skills,
    Experience,
    Education,
    Other
  },
  data() {
    return {};
  }
};
</script>

<style>
</style>

