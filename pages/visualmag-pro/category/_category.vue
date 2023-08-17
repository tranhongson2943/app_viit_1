<template>
  <div>
    <div class="detail">
      <div class="detail-container">
        <div class="flex">
          <div class="left-container lg-66">
            <div class="title-container">
              <h1 class="h1-title">{{ this.$route.params.category }}</h1>
              <p>Category description here</p>
            </div>
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
            <TechnologyPost />
          </div>
          <div class="right-container lg-33">
            <RightBar />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
  <style scoped>
* {
  font-family: "Inter";
}
.lg-66 {
  width: 100%;
}
.lg-33 {
  width: 100%;
}
.detail {
  display: flex;
  justify-content: center;
  padding: 27px 17px;
}
.detail-container {
  width: 1180px;
}
.gray-stick-container {
  display: flex;
  margin: 32px 0 0;
}
.author {
  margin: 32px 0 0;
  padding: 24px;
  border: 1px solid #f4f4f4;
}
.post-comment-form-title {
  font-family: sans-serif;
  margin: 18px 0 0;
  font-size: 18px;
  font-weight: 700;
  line-height: 26px;
}
.author-name {
  font-weight: 700;
  font-size: 16px;
  line-height: 24px;
  color: #222222;
}
.post-comment-form {
}
/* FORM  */
.input-form {
  margin: 16px 0;
}
.input-lable {
  margin: 0 0 4px;
}
textarea {
  padding: 12.6px;
  width: 100%;
  border: 1px solid #f4f4f4;
  height: 120px;
}
input {
  height: 60px;
  padding: 12.6px;
  width: 100%;
  border: 1px solid #f4f4f4;
}
.post-btn {
  background-color: #0693e3;
  font-weight: 400;
  font-family: "Inter";
  line-height: 26px;
  padding: 10px 20px;
  border: none;
  color: white;
}

.author-detail {
  margin: 0;
  font-weight: 400;
  font-size: 15px;
  line-height: 26px;
  color: #222222;
}
.h1-title {
  font-family: sans-serif;
  font-weight: 700;
  line-height: 32px;
  font-size: 27px;
}
p {
  font-family: "Inter";
  font-weight: 400;
  font-size: 15px;
  color: #222222;
  line-height: 26px;
  margin: 10px 0 0;
}
.title-container{
    padding: 0 0 16px;
}
.gray-stick {
  max-width: 100%;
  font-family: "Inter";
  padding: 4px 10px;
  background-color: #34bf49;
  font-weight: 400;
  font-size: 12px;
  color: white;
  margin: 0px 5px 5px 0px;
}
p {
  margin: 16px 0;
}
.card-title {
  font-family: sans-serif;
  font-weight: 700;
  font-size: 27px;
  line-height: 32px;
  margin: 10px 0 0;
}
.phase {
  margin: 32px 0 0;
  font-weight: 400;
  font-size: 16px;
  line-height: 26px;
  color: #222222;
}
.name {
  font-weight: 400;
  font-size: 13px;
  line-height: 26px;
  color: #222222;
}
.stick-container {
  display: flex;
  margin: 0 0 24px;
}
.flex {
  /* display: flex;
    gap: 33px; */
}
.posted-by {
  font-weight: 400;
  font-size: 13px;
  line-height: 26px;
  color: #222222;
}
.name {
  font-weight: 700;
  font-size: 13px;
  line-height: 24px;
  color: #222222;
}
.date {
  font-weight: 400;
  font-size: 13px;
  line-height: 26px;
  color: #222222;
}
.name-date {
  margin: 10px 0 0;
}
@media only screen and (min-width: 768px) {
  .flex {
    display: flex;
    gap: 36px;
  }
  .lg-66 {
    width: 66%;
  }
  .lg-33 {
    width: 33%;
  }
}
</style>