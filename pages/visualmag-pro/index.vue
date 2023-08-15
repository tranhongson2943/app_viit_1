<template>
  <div class="index-container">
    <div class="index">
      <Banner style="margin-bottom: 45px" />
      <div class="flex-1" style="margin-bottom: 45px">
        <div class="right-container">
          <Advertising style="margin-bottom: 45px" />
          <Blogging class="blogging" style="margin-bottom: 45px" />
          <div class="flex-1-1">
              <Group-1b-3sm title="Web Design" p="How to Humanize AI-Generated Marketing Content" h5="5 Steps for Using Paid Internet Advertising to Drive Conversions" date="April 27, 2021" name="John Doe" url="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/business-working2-400x266.jpeg"/>
              <Group-1b-3sm title="Marketing" p="How to Humanize AI-Generated Marketing Content" h5="5 Steps for Using Paid Internet Advertising to Drive Conversions" date="April 27, 2021" name="John Doe" url="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/facebook-social-400x266.jpeg"/>
          </div>
        </div>

        <div class="left-container">
          <FollowUs />
          <Reviews style="margin-top: 45px" />
          <Group2-2 title="News" style="margin-top: 45px" />
          <Group-4sm title="Fashion" style="margin-top: 45px" />
        </div>
      </div>
      <div class="flex-2" style="margin-bottom: 45px">
        <BannerImg
            h4="How to Use Amazon Posts to Promote Your Products"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/desk-office-400x266.jpeg"
          />
          <BannerImg
            h4="The Definitive Guide to Online Reputation Management"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/laptop-work-400x266.jpeg"
          />
          <BannerImg
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/04/education-business-400x266.jpeg"
          />
      </div>
      <div class="flex-3">
        <div class="social-col">
          <SocialMedia style="margin-bottom: 45px" />
          <Technology />
        </div>
        <div class="fashion-col">
          <Group-4sm title="Lifestyle" style="margin-bottom: 45px"/>
          <Group2-2 title="Business" style="margin-bottom: 45px" />
          <Group-4sm title="WordPress" style="margin-bottom: 45px" />
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
  column-gap: 33px;
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
  column-gap: 33px;
}
.left-container {
  width: 33.33%;
}
.right-container{
  width: 66.66%;
}
.social-col{
  width: 66.66%;
}
.fashion-col{
  width: 33.33%;
}
@media only screen and (max-width: 768px) {
.left-container{
  width: 100%;
}
.flex-1-1{
  display: block;

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
.right-container{
  width: 100%;
}
.flex-1-1{
  display: flex;
  flex-direction: column;
  gap: 45px;
}
}
</style>