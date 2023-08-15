<template>
  <div class="card">
    <img
      :src="url"
      class="card-img"
    />
    <div class="card-body">
      <div class="name-date">
        <span>{{ name }}</span>
        <span class="date">{{ date }}</span>
      </div>

      <h5 class="card-title">
        {{ h5 }}
      </h5>
      <p class="card-text gray">
        {{ p }}
      </p>
    </div>
  </div>
</template>
    <script>
    export default {
      props:['p','h5','date','name','url']
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
.name-date {
  margin-bottom: 17px;
}
span {
  font-weight: 700;
}
.card-img {
  width: 100%;
  object-fit: cover;
}
.card {
  border: none;
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