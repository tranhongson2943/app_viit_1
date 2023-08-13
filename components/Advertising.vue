<template>
  <div >
    <h3>Advertising</h3>
    <hr />
    <div class="row">
      <div class="col-12 col-md-6" style="padding-right: 17px;">
        <VerticalPost />
      </div>
      <div class="col-12 col-md-6" style="padding-left: 17px;">
        <HorizontalPost />
        <HorizontalPost />
        <HorizontalPost />
        <HorizontalPost />
      </div>
    </div>
     
  </div>
</template>
<style scoped>
*{
  padding: 0;
  margin: 0;
  font-family: sans-serif;
}

h3{
  margin-bottom: 9px;
  font-weight: 700;
  font-size: 21px;
}
hr{
  padding: 0;
  margin: 0;
  margin-bottom: 25px;
}
</style>