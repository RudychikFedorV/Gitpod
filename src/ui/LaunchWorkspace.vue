<template>
  <router-link to="/"><div class="GetNow__btn btn">Launch workspace</div></router-link>
</template>
<script></script>
<style lang="scss" scoped>
.GetNow {
  &__btn {
    position: absolute;
    top: 10px;
    right: 10px;
    color: $btn-3;
    text-align: center;
    font: var(--Text-14);
    line-height: 16px;
  }

  .btn {
    display: flex;
    justify-content: end;
    border-radius: 12px;
    background: $color-80;
    box-shadow: $-box-shadow;
    padding: 8px 12px;
    transition: var(--transition);
    &:hover {
      background: lighten($color-80, 15%);
    }
  }
}
</style>
