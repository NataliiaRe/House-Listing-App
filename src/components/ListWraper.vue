<script>
import ListMain from "./ListMain.vue";
import ListFavourite from "./ListFavourite.vue";

export default {
  name: `ListWraper`,
  components: {
    ListMain,
    ListFavourite,
  },
  data() {},
};
</script>

<template>
  <div class="list-wraper">
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
