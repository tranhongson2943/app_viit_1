<template>
  <div>
    <h3>{{ title }}</h3>
    <hr />
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
  margin-bottom: 9px;
  font-weight: 700;
  font-size: 21px;
}
hr {
  padding: 0;
  margin: 0;
  margin-bottom: 25px;
}
</style>