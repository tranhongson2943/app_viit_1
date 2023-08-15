<template>
  <div>
    <h3>
      <label class="title">{{ title }}</label>
      <hr />
    </h3>
    <div class="business-container">
      <SmallVerticalPost
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
        style="padding-bottom: 10px"
      />
      <SmallVerticalPost
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
        style="padding-bottom: 10px"
      />
      <SmallVerticalPost
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
        style="padding-bottom: 10px"
      />
      <SmallVerticalPost
        h5="SEO is Turning into a Questions and Answers Game
  "
        url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-electronic-400x266.jpeg"
        style="padding-bottom: 10px"
      />
    </div>
  </div>
</template>
<script>
export default {
  props :['title']
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
.business-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
}
.title {
  padding-bottom: 9px;
  border-bottom: 2px solid #0099e5;
}
</style>