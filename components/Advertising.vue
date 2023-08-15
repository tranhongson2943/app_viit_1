<template>
  <div>
    <h3>
      <label class="title">Advertising</label>
      <hr />
    </h3>

    <div class="flex-container">
      <div class="verticalpost-col">
        <VerticalPost p="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer porta felis non nibh..." h5="5 Steps for Using Paid Internet Advertising to Drive Conversions" date="April 27, 2021" name="John Doe" url="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/finance-flat-400x266.jpeg"/>
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
  display: block;
  font-weight: 700;
  font-size: 21px;
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
.verticalpost-col {
  width: 50%;
}
.horizontalpost-col {
  width: 50%;
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