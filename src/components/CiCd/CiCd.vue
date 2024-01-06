<template>
  <div class="CiCd">
    <div class="CiCd__block">
      <div class="CiCd__title">Think CI/CD for dev environments</div>
      <div class="CiCd__info">
        We invented prebuilds so application code, configuration and infrastructure can
        all be stored as machine-executable code in your git repositories and applied to
        dev environments automatically and continuously.
      </div>
      <div class="CiCd__buttons">
        <router-link to="/">
          <div class="CiCd__button1 btn">More on prebuilds</div></router-link
        >

        <router-link to="/">
          <div class="CiCd__button2 btn">Documentation</div></router-link
        >
      </div>
    </div>
    <div class="CiCd__img">
      <router-link to="/"><img src="@/assets/CiCd/img.png" alt="Logo" /></router-link>
    </div>
  </div>
</template>
<script></script>
<style lang="scss" scoped>
@import "@/components/CiCd/CiCd.scss";
</style>
