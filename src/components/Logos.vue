<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Logos Ipsum</h2>
    <div class="item-logos">
      <img class="logo" alt="transmart logo" src="../assets/transmart-carrefour-seeklogo.com-5.svg">
    </div>
    <div class="item-logos">
      <img class="logo" alt="transmart logo" src="../assets/auto2000.png">
    </div>
    <div class="item-logos">
      <img class="logo" alt="transmart logo" src="../assets/google-search-ads-360-seeklogo.com.svg">
    </div>
  </div>
</template>


<script>
export default {
  name:'Logos'
}
</script>

<style scoped>
.title-header{
  margin-bottom: 30px; 
}
  .logos-wrapper{
    width: 70%;
    overflow: hidden;
    margin: auto;
    /* background: red; */
  }

  .item-logos{
    float: left;
    margin-right: 20px;
    margin-top: 20px;
    width: 150px;
    height: 150px;
    /* background: red; */
  }

  .item-logos .logo{
    width: 150px;
    height: 150px;
  }

</style>