<template>
  <div class="container" style="font: bold">
    <div class="row my-4">
      <Banner />
    </div>
    <div class="row my-4">
      <div class="row p-0 m-0">
        <div class="col-12 col-md-8 p-0">
          <h3>Advertising</h3>
          <hr />
          <div class="row">
            <div class="col-12 col-md-6">
              <VerticalPost />
            </div>
            <div class="col-12 col-md-6">
              <HorizontalPost />
              <HorizontalPost />
              <HorizontalPost />
              <HorizontalPost />
            </div>
          </div>
          <div class="col">
            <div class="row">
              <h3>Blogging</h3>
              <hr />
            </div>
            <div class="row" style="display: flex;  gap: 60px; justify-content: space-between;">
              <div class="col-3 p-0">
                <SmallVerticalPost />
              </div>
              <div class="col-3 p-0">
                <SmallVerticalPost />
              </div>
              <div class="col-3 p-0">
                <SmallVerticalPost />
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <h3>Follow Us</h3>
          <hr />
          <div class="row">
            <div class="d-grid" style="display: inline">
              <a class="navbar-brand">
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Twitter_2012_logo.svg/640px-Twitter_2012_logo.svg.png"
                  alt="Logo"
                  width="30"
                  height="24"
                  class="d-inline-block align-text-top"
                />
                <lable style="">Twitter</lable>
              </a>
              <a class="navbar-brand">
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Twitter_2012_logo.svg/640px-Twitter_2012_logo.svg.png"
                  alt="Logo"
                  width="30"
                  height="24"
                  class="d-inline-block align-text-top"
                />
                <lable style="">Twitter</lable>
              </a>
              <a class="navbar-brand">
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Twitter_2012_logo.svg/640px-Twitter_2012_logo.svg.png"
                  alt="Logo"
                  width="30"
                  height="24"
                  class="d-inline-block align-text-top"
                />
                <lable style="">Twitter</lable>
              </a>
              <a class="navbar-brand">
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Twitter_2012_logo.svg/640px-Twitter_2012_logo.svg.png"
                  alt="Logo"
                  width="30"
                  height="24"
                  class="d-inline-block align-text-top"
                />
                <lable style="">Twitter</lable>
              </a>
              <a class="navbar-brand">
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Twitter_2012_logo.svg/640px-Twitter_2012_logo.svg.png"
                  alt="Logo"
                  width="30"
                  height="24"
                  class="d-inline-block align-text-top"
                />
                <lable style="">Twitter</lable>
              </a>
              <a class="navbar-brand">
                <img
                  src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Twitter_2012_logo.svg/640px-Twitter_2012_logo.svg.png"
                  alt="Logo"
                  width="30"
                  height="24"
                  class="d-inline-block align-text-top"
                />
                <lable style="">Twitter</lable>
              </a>
            </div>
          </div>
          <div class="row">
            <h3>Reviews</h3>
            <hr />

            <img
              class="h-100 w-100"
              src="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/office-graph2.jpeg"
              alt=""
            />
            <div class="list-link">
              <a href=""
                >How to Use Instagram Story Highlights on a Brand Account</a
              >
              <a href="">How to Use Thought Leadership Marketing </a>
              <a href="">How Does IaaS Affect Your e-Commerce Site</a>
              <a href="">What Are Influencer Engagement Marketplaces</a>
            </div>
          </div>
          <div class="row">
            <h3>News</h3>
            <hr />
          </div>
          <div class="row">
            <div class="col-6">
              <SmallVerticalPost2 />
              <SmallVerticalPost2 />
            </div>
            <div class="col-6">
              <SmallVerticalPost2 />
              <SmallVerticalPost2 />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style>
label {
  font-size: 14px;
}
.list-link {
  line-height: 200%;
  font-size: 17px;
}
.list-link a {
  color: black;
}
</style>