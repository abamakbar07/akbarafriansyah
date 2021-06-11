<template>
  <img src="../assets/logo.png" alt="Profile" />
  <div class="text-center">
    <HoverText text="AKBAR" colorCss="akbar" />
    <HoverText text="MUHAMAD" colorCss="muhamad" />
    <HoverText text="AFRIANSYAH" colorCss="afriansyah" />
  </div>
</template>

<script>
import HoverText from "./HoverText";
export default {
  name: "MainContent",
  components: {
    HoverText: HoverText,
  },
};
</script>

<style scoped>
img {
  width: 100px;
  height: 100%;
  border: solid 5px #0f0;
  border-radius: 50%;
}
</style>>