<template>
  <div class="containerOne">
    <HeaderBlock />
    <div class="containerTwo">
      <AlwaysReady />
      <SelectProject />
      <CiCd />
      <SecureDesign />
    </div>
  </div>
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import AlwaysReady from "@/components/AlwaysReady/AlwaysReady.vue";
import SelectProject from "@/components/SelectProject/SelectProject.vue";
import CiCd from "@/components/CiCd/CiCd.vue";
import SecureDesign from "@/components/SecureDesign/SecureDesign.vue";

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
    CiCd,
    SecureDesign,
  },
};
</script>
