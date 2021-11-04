<template>
  <div>
    <v-row class="mb-6" justify="center" no-gutters>
      <v-avatar size="200">
        <img src="@/assets/images/mai.jpeg" alt="Mai" />
      </v-avatar>
      <v-col md="6" style="margin-left: 20px">
        <div class="name">Siravit Pichphol</div>
        <div class="career" style="margin-bottom: 20px">Software Enginear</div>
        <div class="text-body">
          สวัสดีครับผม " ใหม่ " เป็นนักศึกษาจบใหม่ ถนัดในการทำ Mobile
          Application และงานด้าน Frontend ปัจจุบันทำงานในตำแหน่ง Software
          Enginear ที่บริษัท SCB10X (SkinX)
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
.name {
  font-size: 40px;
  font-weight: 500;
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
</style>
