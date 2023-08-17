<template>
  <header>
    <div class="header-container">
      <button class="hidden-btn">
        <svg width="24" height="24">
          <path
            class="three-line"
            d="M5 5v1.5h14V5H5zm0 7.8h14v-1.5H5v1.5zM5 19h14v-1.5H5V19z"
          ></path>
        </svg>
      </button>
      <a class="logo-link" href="">
        <img
          class="logo"
          src="https://demo.wpenjoy.com/visualmag-pro/wp-content/uploads/sites/55/2023/02/logo-1.png"
          alt=""
        />
      </a>
      <div class="right-side">
        <ul>
          <li>
            <a href="/visualmag-pro">Home</a>
          </li>
          <li>
            <a href="/visualmag-pro/category/Advertising/">Advertising</a>
          </li>
          <li>
            <a href="/visualmag-pro/category/Blogging">Blogging</a>
          </li>
          <li>
            <a href="/visualmag-pro/category/Marketing">Marketing</a>
          </li>
          <li>
            <a href="/visualmag-pro/category/Social">Social</a>
          </li>
          <li>
            <a href="/visualmag-pro/category/Seo">SEO</a>
          </li>
          <li>
            <a href="/visualmag-pro/category/Webdesign">Web Design</a>
          </li>
          <li>
            <a href="">Tech</a>
          </li>
        </ul>
        <div class="search-group">
          <input class="search-input" type="search" />

          <button class="search-btn" type="submit">
            <svg class="search-icon" width="24" height="24">
              <path
                d="M13.5 6C10.5 6 8 8.5 8 11.5c0 1.1.3 2.1.9 3l-3.4 3 1 1.1 3.4-2.9c1 .9 2.2 1.4 3.6 1.4 3 0 5.5-2.5 5.5-5.5C19 8.5 16.5 6 13.5 6zm0 9.5c-2.2 0-4-1.8-4-4s1.8-4 4-4 4 1.8 4 4-1.8 4-4 4z"
              ></path>
            </svg>
          </button>
        </div>
      </div>
    </div>
  </header>
</template>
<style scoped>
* {
  padding: 0;
  margin: 0;
  font-size: 16px;
  color: #222222;
  list-style: none;
  text-decoration: none;
  font-family: "Inter";
  font-weight: 500;
  box-sizing: border-box;
}
header {
  height: 77px;
  width: 100%;
  line-height: 77px;
  display: flex;
  justify-content: center;
  padding: 0 17px;
}
.header-container {
  width: 1180px;
}
/* HIDDEN BTN */
.hidden-btn {
  width: 35.6px;
  height: 35.6px;
  display: flex;
  justify-content: center;
  align-items: center;
  display: none;
  border: none;
  float: right;
  margin-top: 20px;
  align-items: center;
  border: 1px solid #E6E6E6;
  background-color: white;
}

.three-line {
  fill: #222222;
}
/* LOGO */
img.logo {
  width: 220px;
  height: 41.24px;
}
a:hover {
  color: #222222;
  text-decoration: none;
}
header ul {
  margin: 0;
}

header ul li {
  display: inline-block;
  margin-right: 19.8px;
}
a {
  font-weight: 400;
}
/* SEARCH */
.search-group {
  display: flex;
  align-items: center;
  margin-left: 12px;
}
.search-input {
  height: 36.1px;
  width: 162px;
  border: 1px solid #e9e9e9;
  background-color: #f0f0f0;
  border-radius: none;
}
input[type="search"] {
  border: 1px #0099e5;
}
path {
  fill: #f4f4f4;
}
.search-btn {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 38px;
  height: 36.1px;
  background-color: #0099e5;
  border: none;
}

.right-side {
  float: right;
  display: inline-flex;
}
@media only screen and (max-width: 1178px) {
  .search-group {
    display: none;
  }
}
@media only screen and (max-width: 955px) {
  ul {
    display: none;
  }
  .hidden-btn {
    display: inline-flex;
  }
}
</style>