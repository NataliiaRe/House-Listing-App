<template>
  <div class="list-main">
    <h1>List of houses</h1>
    <ListItem />
  </div>
</template>

<script>
export default {
  name: `ListMain`,

  data() {
    return {
      title: `main list`,
    };
  },
  mounted() {
    console.log(`random sign`);
  },
};
</script>

<style></style>
