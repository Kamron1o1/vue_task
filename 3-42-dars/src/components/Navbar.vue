<template>
    <div class="blue">
     <ul>
         <li>Students</li>
         <li>Employers</li>
         <li>Career Centers</li>
     </ul>
        <a href="#"><button>Log in</button></a>
    </div>
    <div class="navbar">
        <div class="navbar-logo">
            <img src="@/assets/images/logo.png" alt="">
        </div>
        <ul>
            <li>Overview</li>
            <li>How it works</li>
            <li>Who's hiring</li>
            <li>Career tips</li>
        </ul>

    </div>
    <div class="light-green">
        <p><b>Handshake is hiring! Join us to make a big impact.</b>View current roles. <a href="#"><img src="../assets/images/strelka.png"></a></p>
    </div>
</template>

<script>
    export default {
        name: "navbar"
    }
</script>

<style >
  .blue{
      height: 57px;
      width: 100%;
      background: #0F1035;
      border-radius: 0;
     display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 80px 0 80px;

  }
  .blue ul{
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 20%;
  }
    .blue li{
        color: white;
        font-family: 'Roboto',sans-serif;
        font-weight: 700;
        font-size: 14px;
        line-height: 18px;

    }
    a button{
        font-family: 'Roboto',sans-serif;
        font-style: normal;
        font-weight: 700;
        font-size: 14px;
        line-height: 18px;
        color: white;
        background: #0F1035;
        border: none;
        cursor: pointer;


    }
    .navbar{
        height: 73px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .navbar-logo{
        margin-left: 80px;
    }
    .navbar ul {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 30%;
        margin-right: 210px;
    }
    .light-green{
        background: #D3F1F3;
        height: 62px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .light-green p b{
        font-weight: 700;
        font-size: 16px;
        line-height: 20px;
    }
    .light-green p{
        font-weight: 400;
        font-size: 16px;
        line-height: 20px;
    }
  .light-green img{
      margin-left: 8px;
  }
</style>