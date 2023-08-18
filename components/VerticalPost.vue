<template>
  <div class="post">
    <img
      :src="url"
      class="image"
    />
    <div class="card-body">
      <div class="name-date">
        <span>{{ name }}</span>
        <span class="date">{{ date }}</span>

      </div>

      <h5 class="card-title">
        <nuxt-link  :to="'visualmag-pro/'+h5">  {{ h5 }}</nuxt-link>
     
      </h5>
      <p class="card-text gray">
        {{ p }}
      </p>
    </div>
  </div>
</template>
    <script>
    export default {
      props:['p','h5','date','name','url'],
      method:{
      }
    }
    </script>
    <style scoped>
* {
  font-family: sans-serif;
}
.date {
  color: #888888;
  font-weight: 400;
  font-family: "Inter";
  font-size: 14px;
}
a{
  color: black;
}
.name-date {
  margin-bottom: 17px;
}
span {
  font-weight: 700;
}
.image {
  width: 100%;
  min-width: 100%;
}
.post {
}
.card-body {
  padding-bottom: 0;
  padding-left: 0;
  padding-right: 0;
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
</style>