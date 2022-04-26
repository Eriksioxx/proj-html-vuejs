<template>
  <div id="app">
    <HeaderBox :navbar="navbar" />
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
    return {
      // HeaderBox: Navbar Menu
      navbar: [
        {
          id: "1",
          label: "Home",
          url: "#",
        },
        {
          id: "2",
          label: "Shop",
          url: "#",
        },
        {
          id: "3",
          label: "Products",
          url: "#",
        },
        {
          id: "4",
          label: "Categories",
          url: "#",
        },
        {
          id: "5",
          label: "News",
          url: "#",
        },
        {
          id: "6",
          label: "Elements",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
</style>
