<template>
  <div>
    <h3>
      <label class="title">Social Media</label>
      <hr />
    </h3>
    <div class="socialmedia-container">
      <VerticalPost />
      <VerticalPost />
      <VerticalPost />
      <VerticalPost />
    </div>
  </div>
</template>
<style scoped>
* {
  padding: 0;
  margin: 0;
  font-family: sans-serif;
}
h3 {
  font-weight: 700;
  font-size: 21px;
}
hr {
  padding: 0;
  margin: 0;
  margin-bottom: 25px;
}
.socialmedia-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
}
.title {
  padding-bottom: 9px;
  border-bottom: 2px solid #0099e5;
}
</style>