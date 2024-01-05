<template>
  <div class="GetNow__section1">
    <div class="GetNow__text">Connect Git repository</div>
    <div class="GetNow__info">
      Select a Git provider to start with an existing project from any Git context.
    </div>
    <div class="GetNow__icons">
      <router-link to="/"
        ><div class="GetNow__gitlab btn">
          <div class="GetNow__gitlab-img">
            <img src="@/assets/AlwaysReady/gitlab2.svg" alt="Gitlab" />
          </div>
          <div class="GetNow__gitlab-p texts">Continue with GitLab</div>
        </div>
      </router-link>

      <router-link to="/"
        ><div class="GetNow__gitHub btn">
          <div class="GetNow__gitHub-img">
            <img src="@/assets/AlwaysReady/gitHub2.svg" alt="GitHub" />
          </div>
          <div class="GetNow__gitHub-p texts">Continue with GitHub</div>
        </div>
      </router-link>

      <router-link to="/"
        ><div class="GetNow__bitbucket btn">
          <div class="GetNow__bitbucket-img">
            <img src="@/assets/AlwaysReady/bitbucket2.svg" alt="Bitbucket" />
          </div>
          <div class="GetNow__bitbucket-p texts">Continue with Bitbucket</div>
        </div>
      </router-link>
    </div>
    <div class="GetNow__informations">
      Or prefix any GitLab, GitHub or Bitbucket URL with
    </div>
    <div class="GetNow__inform">gitpod.io/#</div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.GetNow {
  &__section1 {
    display: flex;
    flex-direction: column;
   width: 642px;
    flex-shrink: 0;
    border-radius: 20px;
    background: $btn-3;
    padding: 56px;
  }
  &__text {
    color: $color-80;
    text-align: center;
    font: var(--Text-32);
    line-height: 40px;
    margin-bottom: 8px;
  }
  &__info {
    max-width: 471px;
    color: $color-23;
    display: flex;
    justify-content: center;
    text-align: center;
    font: var(--Text-24);
    line-height: 31.92px;
    margin-bottom: 62px;
  }
  &__icons {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 16px;
    margin-bottom: 64px;
  }
  .btn {
    border-radius: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
  }
  &__gitlab {
    background: $btn-1;
    padding: 9px 53px 9px 33px;
    &:hover {
      background: lighten($btn-1, 5%);
    }
  }
  &__gitHub {
    background: $color-81;
    padding: 9px 50px 9px 33px;
    &:hover {
      background: lighten($color-81, 5%);
    }
  }
  &__bitbucket {
    background: $color-82;
    padding: 9px 33px;
    &:hover {
      background: lighten($color-82, 5%);
    }
  }
  .texts {
    color: $btn-3;
    text-align: center;
    font: var(--Text-14);
    line-height: 16px;
  }
  &__informations {
    color: $color-23;
    text-align: center;
    font: var(--Text-24);
    line-height: 31.92px;
    margin-bottom: 5px;
  }
  &__inform {
    color: $color-23;
    text-align: center;
    font: var(--Text-24);
    line-height: 31.92px;
    padding: 1px 15px;
    border-radius: 12px;
    background: $color-53;
    max-width: 151px;
    margin-inline: auto;
    margin-bottom: 86px;
  }
}
</style>
