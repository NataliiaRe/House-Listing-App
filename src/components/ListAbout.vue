<template>
  <div class="list-about">
    {{ title }}
  </div>
</template>

<script>
export default {
  name: `ListAbout`,
  data() {
    return {
      title: `about list`,
    };
  },
  mounted() {
    console.log(`random sign`);
  },
};
</script>

<style></style>
