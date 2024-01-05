<template>
  <div class="GetNow__section2">
    <div class="GetNow__title">Launch an example workspace</div>
    <div class="GetNow__info">Dive into one of our example workspaces</div>
    <div class="GetNow__sections">
    
      <div class="GetNow__TS section">
        <div class="GetNow__img img">
          <img src="@/assets/GetNow/ts.svg" alt="TS" />
        </div>
        <div class="GetNow__text text">Node or TypeScript</div>
        <LaunchWorkspace />
      </div>

      <div class="GetNow__Python section">
        <div class="GetNow__img img">
          <img src="@/assets/GetNow/p.svg" alt="Python" />
        </div>
        <div class="GetNow__text text">Python</div>
        <LaunchWorkspace />
      </div>

      <div class="GetNow__Go section">
        <div class="GetNow__img img">
          <img src="@/assets/GetNow/g.svg" alt="Go" />
        </div>
        <div class="GetNow__text text">Go</div>
        <LaunchWorkspace />
      </div>

      <div class="GetNow__Rust section">
        <div class="GetNow__img img">
          <img src="@/assets/GetNow/r.svg" alt="Rust" />
        </div>
        <div class="GetNow__text text">Rust</div>
        <LaunchWorkspace />
      </div>

      <div class="GetNow__Java section">
        <div class="GetNow__img img">
          <img src="@/assets/GetNow/j.svg" alt="Java" />
        </div>
        <div class="GetNow__text text">Java</div>
        <LaunchWorkspace />
      </div>

      <div class="GetNow__Svelte section">
        <div class="GetNow__img img">
          <img src="@/assets/GetNow/s.svg" alt="Svelte" />
        </div>
        <div class="GetNow__text text">Svelte</div>
        <LaunchWorkspace />
      </div>
    </div>
  </div>
</template>

<script>
import LaunchWorkspace from "@/ui/LaunchWorkspace.vue";
export default {
  components: {
    LaunchWorkspace,
  },
};
</script>

<style lang="scss" scoped>
.GetNow {
  &__section2 {
    display: flex;
    flex-direction: column;
    max-width: 642px;
    flex-shrink: 0;
    border-radius: 20px;
    background: $btn-3;
    padding: 56px;
    width: 100%;
  }
  &__title {
    color: $color-80;
    text-align: center;
    font: var(--Text-32);
    line-height: 40px;
    margin-bottom: 8px;
  }
  &__info {
    max-width: 471px;
    color: $color-23;
    text-align: center;
    margin-inline: auto;
    font: var(--Text-24);
    line-height: 31.92px;
    margin-bottom: 32px;
  }
  &__sections {
    display: flex;
    flex-direction: column;
    gap: 12px;
  }
  .section {
    padding: 12px;
    max-width: 530px;
    border-radius: 12px;
    flex-shrink: 0;
    background: $btn-4;
    display: flex;
    position: relative;
    align-items: center;
  }

  .img {
    margin-right: 16px;
    display: flex;
    align-items: center;
  }
  .text {
    color: $color-23;
    display: flex;
    align-items: center;
    font: var(--Text-20);
    line-height: 20px;
  }
}
</style>
