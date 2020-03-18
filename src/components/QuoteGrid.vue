<template>
  <div class="row">
    <div v-for="quote in quotes">
      <Quote>
        {{ quote }}
      </Quote>
    </div>
  </div>
</template>

<script>
import Quote from "./Quote.vue";
export default {
  name: "QuoteGrid",
  props: ["quotes"],
  components: {
    Quote
  }
};
</script>

<style></style>
