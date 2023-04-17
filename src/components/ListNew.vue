<template>
  <div class="list-new">
    {{ title }}
  </div>
</template>

<script>
export default {
  name: `ListNew`,
  data() {
    return {
      title: `new list`,
    };
  },
  mounted() {
    console.log(`random sign`);
  },
};
</script>

<style></style>
