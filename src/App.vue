<template>
  <div id="app">
    <HeaderBox logo="/classic_shop_logo1x.png" />
  </div>
</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";

export default {
  name: "App",
  components: {
    HeaderBox,
  },
  data() {
    return {};
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
</style>
