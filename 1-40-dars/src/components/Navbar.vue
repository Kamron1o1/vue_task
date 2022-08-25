<template>
<div class="container">
    <div class="navbar">
        <div class="logo-navbar">
            <a href="#"><img src="@/assets/images/Frame.png" alt=""></a>
        </div>
        <div class="nav-navbar">
            <ul>
                <li>Home</li>
                <li>Contact</li>
                <li>Privacy</li>
            </ul>
        </div>
    </div>
</div>
    <button>Contact Us</button>
 <div class="container">
     <div class="scetion-1">
         <div class="for-title">
             <h1>Get Instant
                 Loans</h1>
             <p>Get instant loans with ease on your
                 smartphone.</p>
             <div class="wrap-app">
                 <div class="Appstore">
                     <a href="https://play.google.com/">
                         <img src="@/assets/images/gogle.png" alt="">
                     </a>
                 </div>
                 <div class="Appstore">
                     <a href="https://www.apple.com/">
                         <img src="@/assets/images/appstore.png" alt="">
                     </a>
                 </div>
             </div>
         </div>
         <div class="for-img">
             <img src="@/assets/images/Frame(1).png" alt="">
         </div>
     </div>
 </div>
</template>

<script>
    export default {
        name: "Navbar",
    }
</script>

<style>
    .container{
        width: 1200px;
        margin: 0 auto;
    }
    .navbar{
        display: flex;
        justify-content: start;
        align-items: center;
    }
    .nav-navbar{
        width: 60%;
        margin-left: 165px;

    }
    .nav-navbar ul{
        display: flex;
        justify-content: left;
        align-items: center;
        padding: 0;
    }
    .nav-navbar li{
        list-style: none;
        text-decoration: none;
        padding-right: 40px;
        box-sizing: border-box;
        font-family: 'Work Sans', sans-serif;
        font-style: normal;
        font-weight: 400;
        font-size: 15px;
        line-height: 10px;
    }
    .nav-navbar li:last-child{
        padding: 0;
    }
    button{
       position: absolute;
        top: 48px;
        left: 0;
        width: 108px;
        height: 36px;
        padding: 0;
        transform: rotate(90deg) ;
        transform-origin: 0 100%;
        background: #39CDCC;
        border: none;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        border-radius: 0 6px 6px 0;
        transition: none;
    }
    .scetion-1 {
        display: flex;
        justify-content: space-between;
    }
    .scetion-1 .for-title{
        margin: 160px 204px 0 112px;
    }
    .scetion-1 .for-title h1{

        font-family: 'Work Sans',sans-serif;
        font-style: normal;
        font-weight: 400;
        font-size: 55px;
        line-height: 60px;
        margin-right: 128px;
    }
    .scetion-1 .for-title p{
        font-family: 'Work Sans',sans-serif;
        font-style: normal;
        font-weight: 400;
        font-size: 24px;
        line-height: 35px;
        margin-top: 32px;
    }
    .wrap-app{
        display: flex;
        justify-content: start;
        align-items: center;
    }
     .Appstore {
         margin-top: 30px;
         margin-right: 8px;
     }


    .Appstore:last-child{
        margin-right: 0;
    }





</style>