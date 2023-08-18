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
            <ul>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
              <li class="li-post">   <TechnologyPost /> <hr></li>
            </ul>
            <!-- PAGINATION -->
            <Pagination/>
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
.li-post{
  margin: 0 0 32px;
}
.h1-title {
  font-family: sans-serif;
  font-weight: 700;
  line-height: 32px;
  font-size: 27px;
}
ul{
  text-decoration: none;
  list-style: none;
  padding: 0;
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
.flex {
  /* display: flex;
    gap: 33px; */
}
/* Pagination */
.pagination-number{
display: block;
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