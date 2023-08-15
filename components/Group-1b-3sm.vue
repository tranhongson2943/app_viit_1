<template>
  <div>
    <h3>
      <label class="title">{{ title }}</label>
      <hr />
    </h3>

    <div class="block-container">
      <div class="verticalpost-col">
        <VerticalPost :p="p" :h5="h5" :date="date" :name="name" :url="url" style="margin-bottom: 35px;"/>
      </div>
      <div class="horizontalpost-col">
        <HorizontalPost />
        <HorizontalPost />
        <HorizontalPost />
        <HorizontalPost />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props:['title','p','h5','date','name','url']
}
</script>
<style scoped>
* {
  padding: 0;
  margin: 0;
  font-family: sans-serif;
}
h3 {
  display: block;
  font-weight: 700;
  font-size: 21px;
}
.block-container{
  gap: 36px;
}
.title {
  padding-bottom: 9px;
  border-bottom: 2px solid #0099e5;
}
hr {
  padding: 0;
  margin: 0;
  margin-bottom: 25px;
}
.horizontalpost-col {
  display: flex;
  flex-direction: column;
  gap: 22px;
}
@media only screen and (max-width: 768px) {
  .flex-container {
    display: block;
  }
  .verticalpost-col {
    width: 100%;
  }
  .horizontalpost-col {
    width: 100%;
  }
}
</style>