<template>
  <div class="index">
    <div class="index-container">
      <div class="flex m-45px">
        <Banner />
      </div>
      <div class="flex m-45px">
        <div class="right-container">
          <Advertising clase="m-45px" />
          <Blogging class="blogging" />
          <div class="flex-2">
            <Group-1b-3sm
              title="Web Design"
              p="How to Humanize AI-Generated Marketing Content"
              h5="5 Steps for Using Paid Internet Advertising to Drive Conversions"
              date="April 27, 2021"
              name="John Doe"
              url="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/business-working2-400x266.jpeg"
            />
            <Group-1b-3sm
              title="Marketing"
              p="How to Humanize AI-Generated Marketing Content"
              h5="5 Steps for Using Paid Internet Advertising to Drive Conversions"
              date="April 27, 2021"
              name="John Doe"
              url="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/facebook-social-400x266.jpeg"
            />
          </div>
        </div>

        <div class="left-container">
          <FollowUs />
          <Reviews class="m-45px" />
          <Group-2sm-2sm clase="m-45px" title="News" />
          <Group-4sm clase="m-45px" title="Fashion" />
        </div>
      </div>
      <div class="flex m-45px">
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
      <div class="flex">
        <div class="right-container">
          <SocialMedia style="margin-bottom: 45px" />
          <Technology />
        </div>
        <div class="left-container">
          <Group-4sm clase="m-45px" title="Lifestyle" />
          <Group-2sm-2sm clase="m-45px" title="Business" />
          <Group-4sm title="WordPress" />
          <FilterByTag clase="m-45px" />
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
.m-45px {
  margin-bottom: 45px;
}
.index-container {
  width: 1180px;
}
.index {
  display: flex;
  justify-content: center;
  padding: 0 17px;
}
.flex {
  display: flex;
  column-gap: 33px;
  margin-bottom: 45px;
}
.flex-2 {
  display: flex;
  column-gap: 32px;
}
.left-container {
  width: 33.33%;
}
.right-container {
  width: 66.66%;
  display: flex;
  flex-direction: column;
}
@media only screen and (max-width: 768px) {
  .left-container {
    width: 100%;
  }
  .flex-2 {
    display: block;
  }
  .flex {
    display: flex;
    flex-direction: column;
    gap: 22px;
  }
  .right-container {
    width: 100%;
  }
  .flex-2 {
    display: flex;
    flex-direction: column;
    gap: 45px;
  }
}
</style>