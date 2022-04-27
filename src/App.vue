<template>
  <div id="app">
    <HeaderBox :navbar="navbar" />
    <HeroBox />
    <FeaturedProducts />
    <CollectionBox />
    <BestSeller />
  </div>
</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";
import HeroBox from "./components/HeroBox.vue";
import FeaturedProducts from "./components/FeaturedProducts.vue";
import CollectionBox from "./components/CollectionBox.vue";
import BestSeller from "./components/BestSeller.vue";

export default {
  name: "App",
  components: {
    HeaderBox,
    HeroBox,
    FeaturedProducts,
    CollectionBox,
    BestSeller,
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
