<template>
  <div class="SwiperSlide1">
    <div class="SwiperSlide1__text1">GitPod is incredibly cool.</div>
    <div class="SwiperSlide1__text2">
      In my opinion, this is a big step in open source software contribution. I'm excited
      to see where we go from here.
    </div>
    <div class="SwiperSlide1__block">
      <div class="SwiperSlide1__img">
        <img src="@/assets/UsedDevelopers/img1.png" alt="Foto" />
      </div>
      <div class="SwiperSlide1__texts">
        <div class="SwiperSlide1__text3">Ben Halpern</div>
        <div class="SwiperSlide1__text4">Creator and Co-founder</div>
        <div class="SwiperSlide1__text5">@ThePracticalDev</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.SwiperSlide1,
.SwiperSlide2,
.SwiperSlide3,
.SwiperSlide4,
.SwiperSlide5 {
  padding: 24px;
  max-width: 384px;
  flex-shrink: 0;
  border-radius: 16px;
  background: $btn-4;

  &__text1 {
    color: $color-80;
    font: var(--Text-16);
    line-height: 24px;
    margin-bottom: 10px;
  }
  &__text2 {
    color: $color-80;
    font: var(--Text-16);
    line-height: 24px;
    margin-bottom: 14px;
  }
  &__block {
    display: flex;
    gap: 12px;
  }
  &__text3 {
    color: $color-80;
    font: var(--Text-16-7);
    line-height: 24px;
    margin-bottom: 8px;
  }
  &__text4 {
    color: $color-80;
    font: var(--Text-16);
    line-height: 24px;
  }
  &__text5 {
    color: $color-80;
    font: var(--Text-16-7);
    line-height: 24px;
  }
}
</style>
