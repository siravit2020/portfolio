<template>
  <div>
    <div class="topic">Skill</div>
    <v-row no-gutters>
      <v-col>
        <v-row no-gutters align="center">
          <div class="text-title">Flutter</div>
          <Star count="5"></Star>
        </v-row>
        <v-row no-gutters align="center">
          <div class="text-title">Android</div>
          <Star count="4"></Star>
        </v-row>
        <v-row no-gutters align="center">
          <div class="text-title">Kotlin</div>
          <Star count="4"></Star>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import Star from "./StarRating.vue";
export default {
  components: {
    Star,
  },
};
</script>

<style lang="scss" scoped>
.topic {
  font-size: 40px;
  font-weight: 500;
  margin-bottom: 40px;
  height: 50px;
  color: rgb(24, 24, 24);
}
.career {
  font-size: 20px;
  color: rgba(24, 24, 24, 0.76);
}
.text-body {
  font-size: 16px;
  color: rgba(70, 70, 70, 0.664);
}
.text-body2 {
  font-size: 20px;
  color: rgba(24, 24, 24, 0.76);
}
.text-title {
  font-size: 26px;
  width: 130px;

  color: rgb(24, 24, 24);
}
</style>
