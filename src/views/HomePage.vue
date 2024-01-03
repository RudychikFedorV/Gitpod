<template>
  <div class="containerOne">
    <HeaderBlock />
    <div class="containerTwo">
      <AlwaysReady />
    </div>
  </div>
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import AlwaysReady from "@/components/AlwaysReady/AlwaysReady.vue";

export default {
  name: "HomePage",
  data() {
    return {
      isChecked: false,
    };
  },
  methods: {},
  components: {
    HeaderBlock,
    AlwaysReady,
  },
};
</script>
