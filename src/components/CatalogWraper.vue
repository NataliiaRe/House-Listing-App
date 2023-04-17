<script>
export default {
  name: `CatalogWraper`,

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
  <div class="catalog-wraper">
    {{ title }}
  </div>
</template>

<style>
.catalog-wraper {
  width: 900px;
  margine: 0 auto;
}
</style>
