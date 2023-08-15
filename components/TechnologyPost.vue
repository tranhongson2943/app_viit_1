<template>
  <div class="post-container">
    <div class="content">
      <img
        src="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2021/05/thumbs-up.jpeg"
        alt=""
      />

      <div class="text">
        <h5 class="card-title">
          5 Steps for Using Paid Internet Advertising to Drive Conversions
        </h5>
        <div class="name-date">
          <span>John Doe</span>
          <span class="date">April 27, 2021</span>
        </div>
        <p class="card-text gray">
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
}

img {
  float: left;
  max-width: 240px;
  height: auto;
  margin-right: 26px;
}
.post-container{
  margin-bottom: 33px;
}
.date {
  color: #888888;
  font-weight: 400;
  font-family: "Inter";
  font-size: 14px;
}
.name-date {
  margin-bottom: 17px;
}
.card-title {
  font-family: sans-serif;
  font-weight: 700;
  font-size: 2.5vw;
}
span {
  font-weight: 700;
}
h5 {
  font-weight: 700;
  font-size: 22px;
  margin-bottom: 17px;
}
p {
  color: #888888;
  font-weight: 400;
  font-family: "Inter";
  font-size: 16px;
  line-height: 26px;
}
@media screen and (min-width: 1200px) {
  .card-title {
    font-size: 22px;
  }
}
@media only screen and (max-width: 768px) {
  img {
    float: left;
    max-width: 120px;
    height: auto;
    margin-right: 26px;
  }
  .card-text {
    display: block;
  }
  .card-title {
    font-size: 16px;
  }
}
@media only screen and (max-width: 476px) {
  img {
    float: left;
    max-width: 120px;
    height: auto;
    margin-right: 26px;
  }
  .card-text {
    display: none;
  }

}
</style>