<template>
  <div>
    <h3> <label class="title">Blogging</label>     <hr /></h3>
    <div class="blog-container">
      <SmallVerticalPost
      class="bold-h5"
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
      />
      <SmallVerticalPost
      class="bold-h5"
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
      />
      <SmallVerticalPost
      class="bold-h5"
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
      />
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
.title {
  padding-bottom: 9px;
  border-bottom: 2px solid #0099e5;
}
hr {
  padding: 0;
  margin: 0;
  margin-bottom: 25px;
}
.blog-container{
display: flex;
justify-content: space-between;
gap: 24px;
}
.bold-h5 ::v-deep h5{
  font-family: "Inter";
  font-weight: 700;
  margin: 0;
  overflow-wrap: break-word;
  word-wrap: break-word;
  word-break: break-word;
  font-size: 16px;   
  margin-top: 18px;
}
</style>