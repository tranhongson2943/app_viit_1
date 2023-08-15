<template>
  <div>
    <h3>{{ title }}</h3>
    <hr />
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
  margin-bottom: 9px;
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
</style>