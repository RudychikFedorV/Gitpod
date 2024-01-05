<template>
  <div class="containerOne">
    <HeaderBlock />
    <div class="containerTwo">
      <AlwaysReady />
      <SelectProject />
      <CiCd />
      <SecureDesign />
      <UsedDevelopers />
      <GetNow />
    </div>
    <ContactsPage />
  </div>
</template>

<script>
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import AlwaysReady from "@/components/AlwaysReady/AlwaysReady.vue";
import SelectProject from "@/components/SelectProject/SelectProject.vue";
import CiCd from "@/components/CiCd/CiCd.vue";
import SecureDesign from "@/components/SecureDesign/SecureDesign.vue";
import UsedDevelopers from "@/components/UsedDevelopers/UsedDevelopers.vue";
import GetNow from "@/components/GetNow/GetNow.vue";
import ContactsPage from "@/components/ContactsPage/ContactsPage.vue";

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
    UsedDevelopers,
    GetNow,
    ContactsPage,
},
};
</script>

<style lang="scss" scoped>

</style>
