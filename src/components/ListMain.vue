<script>
import ListItem from "./ListItem.vue";
export default {
  name: `ListMain`,
  components: { ListItem },
  data() {
    return {
      title: `main list`,
    };
  },
};
</script>

<template>
  <div class="list-main">
    <h1>List of houses</h1>
    <ListItem />
    <ListItem />
    <ListItem />
    <ListItem />
  </div>
</template>

<style></style>
