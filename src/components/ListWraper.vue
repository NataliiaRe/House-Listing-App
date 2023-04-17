<template>
  <div class="list-wraper">
    {{ title }}
    <ListMain />
    <ListFavourite />
  </div>
</template>

<script>
import ListMainVue from "./ListMain.vue";
import ListFavouriteVue from "./ListFavourite.vue";

export default {
  name: `ListWraper`,
  components: {
    ListMainVue,
    ListFavouriteVue,
  },
  data() {
    return {
      title: `Main wraper`,
    };
  },
  mounted() {
    console.log(`random sign`);
  },
};
</script>

<style>
.list-wraper {
  width: 900px;
  margin: 0 auto;
}
</style>
