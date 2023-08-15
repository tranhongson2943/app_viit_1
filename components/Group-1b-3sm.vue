<template>
  <div>
    <h3>
      <label class="title">{{ title }}</label>
      <hr />
    </h3>
    <VerticalPost style="margin-bottom: 35px;"/>
    <HorizontalPost/>
    <HorizontalPost/>
    <HorizontalPost/>
  </div>
</template>
<script>
export default {
  props:['title']
}
</script>
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
.title {
  padding-bottom: 9px;
  border-bottom: 2px solid #0099e5;
}
</style>