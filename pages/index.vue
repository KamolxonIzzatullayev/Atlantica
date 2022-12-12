<template>
  <div class="main">
    <MainPageHeader></MainPageHeader>

    <MainPageSearchBar></MainPageSearchBar>

    <EntertainmentBanner></EntertainmentBanner>

    <PopularProducts></PopularProducts>
  </div>
</template>

<script>
import MainPageHeader from "../components/Common/MainPageHeader/MainPageHeader.vue";
import MainPageSearchBar from "../components/Common/MainPageSearchBar/MainPageSearchBar.vue";
import EntertainmentBanner from "../components/Custom/EntertainmentBanner/EntertainmentBanner.vue";
import PopularProducts from "../Layouts/PopularProducts/PopularProducts.vue";
export default {
  components: {
    MainPageHeader,
    MainPageSearchBar,
    EntertainmentBanner,
    PopularProducts,
  },
  name: "IndexPage",
};
</script>

<style lang="scss" scoped>
.main {
  background: #fbfbfb;
}
</style>
