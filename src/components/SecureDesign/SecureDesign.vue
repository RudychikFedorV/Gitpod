<template>
  <div class="SecureDesign">
    <div class="SecureDesign__title">Remote-first. Secure by design.</div>
    <router-link to="/"
      ><div class="SecureDesign__img">
        <img src="@/assets/SecureDesign/img.png" alt="Foto" /></div
    ></router-link>

    <div class="SecureDesign__info">
      You no longer need an over-powered laptop to code, Gitpod works just as smoothly on
      a Chromebook or iPad. All you need is a browser. Gitpod centralizes all source code
      and never stores it on insecure machines and networks.
    </div>
    <div class="SecureDesign__section">
      <router-link to="/"
        ><div class="SecureDesign__сhrome">
          <img src="@/assets/SecureDesign/сhrome.svg" alt="Chrome" />
          <div class="SecureDesign__text">Chrome Extension</div>
        </div></router-link
      >

      <router-link to="/"
        ><div class="SecureDesign__fox">
          <img src="@/assets/SecureDesign/fox.svg" alt="Firefox Extension" />
          <div class="SecureDesign__text">Firefox Extension</div>
        </div></router-link
      >
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
@import "@/components/SecureDesign/SecureDesign.scss";
</style>
