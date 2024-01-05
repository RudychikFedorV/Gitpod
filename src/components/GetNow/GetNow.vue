<template>
  <div class="GetNow">
    <div class="GetNow__title">Get started now</div>
    <div class="GetNow__sections">
      <GetNowSection1 />
      <GetNowSection2 />
    </div>
  </div>
</template>

<script>
import GetNowSection1 from "@/ui/GetNowSection1.vue";
import GetNowSection2 from "@/ui/GetNowSection2.vue";

export default {
  components: {
    GetNowSection1,
    GetNowSection2,
  },
};
</script>

<style lang="scss" scoped>
@import "@/components/GetNow/GetNow.scss";
</style>
