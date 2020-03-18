<template>
  <div class="row">
    <div v-for="quote in quotes">{{ quote }}</div>
  </div>
</template>

<script>
export default {
  name: "QuoteGrid",
  props: ["quotes"]
};
</script>

<style></style>
