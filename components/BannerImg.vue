<template>
  <a href="">
    <img class="h-100 w-100" :src="url_img" alt="" />
    <div class="text-overlay">
      <h1>{{ h1 }}</h1>
      <h4>{{ h4 }}</h4>
    </div>
  </a>
</template>
<script>
export default {
  props: ["url_img", "h1", "color", "h4", "disable_h1"],
};
</script>
<style scoped>
* {
  padding: 0;
  margin: 0;
  color: white;
  word-wrap: break-word;
}
.text-overlay {
  position: absolute;
  bottom: 22px;
  left: 22px;
  box-sizing: border-box;
}
.text-overlay:hover {
  color: white;
}
h1 {
  display: inline;
  font-family: "Inter";
  padding: 3px 6px 3px;
  background-color: #34bf49;
  font-weight: 400;
  font-size: 11px;
  margin-bottom: 16px;
}
h4 {
  font-family: sans-serif;
  font-weight: 700;
  margin: 0;
  overflow-wrap: break-word;
  word-wrap: break-word;
  word-break: break-word;
  font-size: 17px;
}
img {
  filter: brightness(80%);
  width: 100%;
}
</style>