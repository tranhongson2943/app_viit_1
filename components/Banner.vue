<template>
  <div class="banner">
    <div class="row" style="margin-top: 24px;">
      <div class="col-md-6 col-12" style=" padding-right: 4px;">
        <BannerImg
          class="blue-label big-h4"
          h1="ADVERTISING"
          h4="The Ultimate Guide To Joining or Hosting A Twitter Chat"
          url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/06/macbook-laptop.jpeg"
        />
      </div>
      <div class="col-md-6 col-12" style="padding-left: 4px;">
        <div class="row" style="padding-bottom: 4px;">
          <div class="col-6" style="padding-right: 4px;">
            <!-- 1 -->
            <BannerImg
              class="green-label"
              h1="MARKETING"
              h4="How to Use DaaS Tools in Your Marketing Analysis"
              url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
            />
          </div>
          <div class="col-6" style="padding-left: 4px;">
            <!-- 2 -->
            <BannerImg
              class="orange-label"
              h1="MARKETING"
              h4="How to Humanize AI-Generated Marketing Content"
              url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/business-working2.jpeg"
            />
          </div>
        </div>
        <div class="row" style="padding-top: 4px; ">
          <div class="col-6" style="padding-right: 4px; padding-bottom: -8px;">
            <!-- 3 -->
            <BannerImg
              class="weird-green-label"
              h1="WEB DESIGN"
              h4="How to Run an E-Commerce Marketing Campaign"
              url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-typing.jpeg"
            />
          </div>
          <div class="col-6" style="padding-left: 4px; ">
            <!-- 4 -->
            <BannerImg
              class="pink-label"
              h1="WEB DESIGN"
              h4="The Best Project Management Software for Beginners"
              url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/business-working3.jpeg"
            />
          </div>
        </div>
      </div>
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
  display: flex;
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
</style>