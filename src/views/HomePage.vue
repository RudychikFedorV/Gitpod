<template>
  <div class="containerOne">
    <HeaderBlock />
    <div class="containerTwo">
      <AlwaysReady />
      <SelectProject />
    </div>
  </div>
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import AlwaysReady from "@/components/AlwaysReady/AlwaysReady.vue";
import SelectProject from "@/components/SelectProject/SelectProject.vue";

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
    SelectProject,
  },
};
</script>
