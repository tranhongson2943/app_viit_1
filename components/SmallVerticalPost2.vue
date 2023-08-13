<template>   
    <div class="card">
<img :src="url_img" class="card-img-top" >
<div class="card-body p-0">
    <h5 href="" style="font-size: 17px;">{{ h5 }}</h5>
</div>
</div>
     
 </template>
<script>
export default {
    props:['url_img', 'h5']

}
</script>
 <style scoped>
 .card{
     border: none;
     color: black;
 }
 h5 {
  font-size: 17px;
  margin-top: 21px;
  color: black;
}
 </style>