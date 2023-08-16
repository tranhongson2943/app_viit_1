<template>
  <div class="b-container-fluid">
    <Header class="shadow-sm" />
    <NuxtChild />
    <Footer />
    <div  >
<button class="button-scroll"></button>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style>
.button-scroll{
  background-color: #007AB7;
  position: fixed;
  width: 30px;
  height: 30px;
  bottom: 10px;
  right: 10px;
border: none;
}
</style>