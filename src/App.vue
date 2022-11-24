<script>
import PageTitle from "./components/AppTitle.vue";
import HeroImg from "./components/AppHero.vue";

export default {
  components: {
    PageTitle,
    HeroImg,
  },
};
</script>

<template>
  <div>
    <PageTitle title="Rest In Power" />
    <HeroImg />
  </div>
</template>

<style scoped></style>
