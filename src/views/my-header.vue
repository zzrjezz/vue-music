<template>
  <div class="my-header">
    <div class="div2">
    
    <h1>网易云音乐</h1>
    </div>
    <div class="div3">
      <Button class="header-button">下载app</Button>
      </div>
    
  </div>
</template>
<script>

export default {
  name:'my-header'
}
</script>
<style scoped>
div.my-header{
  background-color:#D43C33;
  height: 10vh;
}
div.my-header div.div2{
  /* border: 1px solid #000; */
  width: 30vw;
  float: left;
}
div.my-header div.div3{
  margin-top: 2.5vh;
  /* background-color: violet; */
  /* border: 1px solid #000; */
  width: 20vw;
  float: right;
}
div.my-header .div3 button{
  color: #D43C33;
  border-radius: 15px;
  width: 100%;
  /* height: 5vh; */
  margin-top: 1vh;
}
div.my-header div.div2 h1{
  color: aliceblue;
  font-size: 20px;
}

</style>