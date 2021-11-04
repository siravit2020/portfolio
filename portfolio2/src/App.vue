<template>
  <v-app>
    <v-container>
      <AboutMe></AboutMe>
      <div class="space"></div>
      <Experience></Experience>
      <div class="space"></div>
      <Education></Education>
      <div class="space"></div>
      <Skill></Skill>
      <div class="space"></div>
    </v-container>
  </v-app>
</template>

<script>
import AboutMe from "./components/AboutMe.vue";
import Education from "./components/Education.vue";
import Experience from "./components/Experience.vue";
import Skill from "./components/Skill.vue";
export default {
  name: "App",
  components: {
    AboutMe,
    Education,
    Experience,
    Skill,
  },

  data: () => ({}),
};
</script>
<style lang="scss" scoped>
.space {
  margin-top: 80px;
}
</style>
