<template>
  <div >
    <h3>Advertising</h3>
    <hr />
    <div class="row">
      <div class="col-12 col-md-6 col1" >
        <VerticalPost />
      </div>
      <div class="col-12 col-md-6 col2" >
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
.col-12.col-md-6.col1{
  padding-right: 17px;
}
.col2{
  padding-left: 17px;
}
@media only screen and (max-width:900px) {
.col-12.col-md-6{
  padding: 0px;
}
.col2{
  padding-left: 0px;
}
.col-12.col-md-6.col1{
  padding-right: 0px;
}
}
</style>