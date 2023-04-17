<script>
import ListMain from "./ListMain.vue";
import ListFavourite from "./ListFavourite.vue";

export default {
  name: `ListWraper`,
  components: {
    ListMain,
    ListFavourite,
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

<template>
  <div class="list-wraper">
    {{ title }}
    <ListMain />
    <ListFavourite />
  </div>
</template>

<style>
.list-wraper {
  width: 900px;
  margin: 0 auto;
}
</style>
