<template>
  <div class="d-flex hover-container">
    <p
      v-for="(alphabet, i) in data"
      v-bind:key="i"
      :class="['hover-text', colorCss]"
    >
      {{ alphabet }}
    </p>
  </div>
</template>

<script>
export default {
  name: "HoverText",
  data() {
    return {
      data: this.text.split(""),
    };
  },
  props: {
    text: String,
    colorCss: String,
  },
};
</script>

<style scoped>
</style>