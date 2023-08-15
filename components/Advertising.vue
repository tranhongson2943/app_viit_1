<template>
  <div>
    <h3>Advertising</h3>
    <hr />
    <div class="flex-container">
      <div class="verticalpost-col">
        <VerticalPost />
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
<style scoped>
* {
  padding: 0;
  margin: 0;
  font-family: sans-serif;
}
.flex-container {
  display: flex;
  gap: 32px;
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
.verticalpost-col{
  width: 50%;
}
.horizontalpost-col{
  width: 50%;
}
@media only screen and (max-width: 768px) {
  .flex-container {
    display: block;
  }
  .verticalpost-col{
  width: 100%;
}
.horizontalpost-col{
  width: 100%;
}
}
</style>