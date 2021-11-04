<template>
  <div>
    <v-row no-gutters>
      <div v-for="(item, index) in 5" :key="index">
        <img src="@/assets/images/star.png" class="star" v-if="index < count" />
        <img src="@/assets/images/star-out.png" class="star" v-else />
      </div>
    </v-row>
  </div>
</template>
<script>
export default {
  name: "star",
  props: ["count"],
};
</script>

<style lang="scss" scoped>
.star {
  width: 24px;
  height: 24px;
  margin-right: 4px;
}
</style>
