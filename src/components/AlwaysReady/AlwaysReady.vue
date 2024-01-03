<template>
  <div class="alwaysReady">
    <div class="alwaysReady__sections">
      <div class="alwaysReady__block">
        <div class="alwaysReady__title">
          Always
          <div>Ready to Code.</div>
        </div>
        <div class="alwaysReady__info">
          Spin up fresh, automated dev environments
          <div>for each task, in the cloud, in seconds.</div>
        </div>
        <div class="alwaysReady__section">
          <div class="alwaysReady__icons">
            <router-link to="/"
              ><div class="alwaysReady__button btn">Try Now</div></router-link
            >

            <div class="alwaysReady__icon">
              <router-link to="/"
                ><div class="alwaysReady__gitlab">
                  <img src="@/assets/AlwaysReady/gitlab.svg" alt="Gitlab" title="Gitlab" /></div
              ></router-link>

              <router-link to="/"
                ><div class="alwaysReady__gitHub">
                  <img src="@/assets/AlwaysReady/gitHub.svg" alt="GitHub" title="GitHub" /></div
              ></router-link>

              <router-link to="/"
                ><div class="alwaysReady__bitbucket">
                  <img src="@/assets/AlwaysReady/bitbucket.svg" alt="Bitbucket" title="Bitbucket" /></div
              ></router-link>
            </div>
          </div>
          <div class="alwaysReady__text">
            Open a workspace.
            <div>Start from any Git context.</div>
          </div>
        </div>
      </div>
      <router-link to="/"
        ><div class="alwaysReady__foto">
          <img src="@/assets/AlwaysReady/foto.png" alt="Logo" /></div
      ></router-link>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "@/components/AlwaysReady/AlwaysReady.scss";
</style>
