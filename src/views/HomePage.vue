<template>
  <div class="container">
    <HeaderBlock />
    <AlwaysReady />
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
  components: { HeaderBlock, AlwaysReady },
};
</script>
