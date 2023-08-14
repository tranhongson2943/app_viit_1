<template>
  <div class="index-container">
    <div class="index">
      <Banner style="margin-bottom: 45px"/>
      <div class="row ">
        <div class="col-12 col-md-8 " style="padding-right: 17px">
          <Advertising  style="margin-bottom: 45px" />
          <Blogging style="margin-bottom: 45px" />
          <div class="row">
            <div class="col-md-6" style="padding-right: 17px">
              <WebDesign />
            </div>
            <div class="col-md-6" style="padding-left: 17px">
              <Marketing />
            </div>
          </div>
        </div>
        <div class="col-md-4" style="padding-left: 17px">
          <FollowUs />
          <Reviews style="margin-top: 45px" />
          <News style="margin-top: 45px" />
          <Fashion style="margin-top: 45px" />
        </div>
      </div>
      <div class="row ">
        <div class="col-4" style="padding-right: 10px">
          <BannerImg
            class="green-label"
            h1="MARKETING"
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
          />
        </div>

        <div
          class="col-4"
          style="padding-bottom: 0px; padding-left: 10px; padding-right: 10px"
        >
          <BannerImg
            class="green-label"
            h1="MARKETING"
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
          />
        </div>
        <div class="col-4" style="padding-left: 10px">
          <BannerImg
            class="green-label"
            h1="MARKETING"
            h4="How to Use DaaS Tools in Your Marketing Analysis"
            url_img="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/top-workspace.jpeg"
          />
        </div>
      </div>
      <div class="row my-4">
        <div class="col-md-8 col-12" style="padding-right: 17px">
          <SocialMedia  style="margin-bottom: 45px"/>
          <Technology />
        </div>
        <div class="col-md-4" style="padding-left: 17px">
          <Fashion/>
          <Business style="margin-bottom: 45px"/>
          <WordPress style="margin-bottom: 45px"/>
          <FilterByTag style="margin-bottom: 45px"/>
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
}
.index {
  width: 1180px;
}
</style>