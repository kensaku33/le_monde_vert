<template>
<div class="footer">
  <div class="footer-wrap">
    <div class="footer-left">
    <img src="@/assets/logo.png" class="footer-logo">
    </div>
    <div class="footer-info">
      <h4>LE MONDE VERT</h4>
      <hr>
        モンドベール
        <br>
        大阪府堺市南区宮山台2-3-1
        <br>
        info@monde-vert.com
    </div>
  </div>
  <br>
  <hr>
  <p class="copylight">
    ©︎ le monde vert
  </p>

</div>
</template>


<style scaped >
  .footer{
    /* height: 300px; */
    width: 100%;
    background-color:#efeee8;
  }
  .footer-wrap{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -ms-flex-pack:distribute;
    justify-content:space-around;
  }
  .footer-logo{
    height:100px;
    margin: 60px 0 0 0px;
  }
  .footer-info{
    width: 220px;
    margin-top: 50px;
    text-align: right;
    float: right;
    /* background-color: yellow; */
  }
  .copylight{
    padding: 0 0 50px 0;
  }
</style>