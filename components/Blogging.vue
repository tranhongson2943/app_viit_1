<template>
  <div >
    <h3>Blogging</h3>
    <hr />
      <div class="box">
        <SmallVerticalPost />
        <SmallVerticalPost />
        <SmallVerticalPost />
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
  margin-bottom: 9px;
  font-weight: 700;
  font-size: 21px;
}
hr {
  padding: 0;
  margin: 0;
  margin-bottom: 25px;
}
.box{
  display: flex;
  justify-content: space-between;
}
</style>