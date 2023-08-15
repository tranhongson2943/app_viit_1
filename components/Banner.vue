<template>
  <div class="banner">
    <div class="img-grid">
      <BannerImg
          :disable_h1="true"
          class="feature blue-label big-h4"
          h1="ADVERTISING"
          h4="The Ultimate Guide To Joining or Hosting A Twitter Chat"
          url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/06/macbook-laptop.jpeg"
        />
        <BannerImg
          :disable_h1="true"
          class="green-label "
          h1="MARKETING"
          h4="The Ultimate Guide To Joining or Hosting A Twitter Chat"
          url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace-400x266.jpeg"
        />
        <BannerImg
          :disable_h1="true"
          class="orange-label "
          h1="WEB DESIGN"
          h4="The Ultimate Guide To Joining or Hosting A Twitter Chat"
          url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/business-working2-400x266.jpeg"
        />
        <BannerImg
          :disable_h1="true"
          class="weird-green-label "
          h1="MARKETING"
          h4="The Ultimate Guide To Joining or Hosting A Twitter Chat"
          url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-typing-400x266.jpeg"
        />
        <BannerImg
          :disable_h1="true"
          class="pink-label "
          h1="WEB DESIGN"
          h4="The Ultimate Guide To Joining or Hosting A Twitter Chat"
          url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/business-working3-400x266.jpeg"
        />
    </div>
   
  </div>
</template>
<script>
</script>
<style scoped>
* {
  padding: 0;
  margin: 0;
}
.banner {
  margin-top: 24px;
}
.img-grid{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 8px;
}
.feature{
  grid-row: span 2;
  grid-column: span 2;
  object-fit: cover;
}
.blue-label ::v-deep h1 {
  background-color: #0099e5;
}
.green-label ::v-deep h1 {
  background-color: #34bf49;
}
.orange-label ::v-deep h1 {
  background-color: #f90;
}
.weird-green-label ::v-deep h1 {
  background-color: #1cc7d0;
}
.pink-label ::v-deep h1 {
  background-color: #ff4f81;
}
.big-h4 ::v-deep h4 {
  font-size: 26px;
}
@media only screen and (max-width: 900px) {
.img-grid{
  grid-template-columns: 1fr 1fr ;
}
}
</style>