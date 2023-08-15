<template>
  <div class="index-container">
    <div class="index">
      <Banner style="margin-bottom: 45px" />
      <div class="flex-1">
        <div class="block-1">
          <Advertising style="margin-bottom: 45px" />
          <Blogging class="blogging" style="margin-bottom: 45px" />
          <div class="flex-1-1">
              <WebDesign />
              <Marketing />
          </div>
        </div>

        <div class="block-2">
          <FollowUs />
          <Reviews style="margin-top: 45px" />
          <Group2-2 title="News" style="margin-top: 45px" />
          <Fashion style="margin-top: 45px" />
        </div>
      </div>
      <div class="flex-2">
        <BannerImg
            class="green-label"
            h1="MARKETING"
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
          />
          <BannerImg
            class="green-label"
            h1="MARKETING"
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
          />
          <BannerImg
            class="green-label"
            h1="MARKETING"
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
          />
      </div>
      <div class="flex-3">
        <div class="social-col">
          <SocialMedia style="margin-bottom: 45px" />
          <Technology />
        </div>
        <div class="fashion-col">
          <Fashion />
          <Group2-2 title="Business" style="margin-bottom: 45px" />
          <WordPress style="margin-bottom: 45px" />
          <FilterByTag style="margin-bottom: 45px" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
  font-family: sans-serif;
  padding: 0;
  margin: 0;
}

.index-container {
  display: flex;
  justify-content: center;
  padding: 0 17px;
}
.index {
  width: 1180px;
  row-gap: 45px;
}
.flex-1 {
  display: flex;
  column-gap: 45px;
}
.flex-1-1{
  display: flex;
  column-gap: 32px;
}
.flex-2{
  display: flex;
  column-gap: 22px;
}
.flex-3{
  display: flex;
  column-gap: 45px;
}
.block-2 {
  width: 33.33%;
}
.block-1{
  width: 66.66%;
}
.social-col{
  width: 66.66%;
}
.fashion-col{
  width: 33.33%;
}
@media only screen and (max-width: 768px) {
.block-2{
  width: 100%;
}
.social-col{
  width: 100%;
}
.fashion-col{
  width: 100%;
}
.flex-1{
  display: block;
}
.flex-3{
  display: block;
}
.block-1{
  width: 100%;
}
}
</style>