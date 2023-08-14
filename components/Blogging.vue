<template>
  <div>
    <h3>Blogging</h3>
    <hr />
    <div class="container-fluid">
      <SmallVerticalPost style="margin-right: 24px;" />
      <SmallVerticalPost   style="margin-right: 24px;"/>
      <SmallVerticalPost  />
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
.container-fluid{
display: flex;
flex-direction: row;
justify-content: space-between;
}
</style>