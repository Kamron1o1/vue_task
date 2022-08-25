<template>
    <div class="header">
        <h1>The #1 way college students get hired</h1>
        <h3>Find the right job. Get hired.</h3>
      <div class="input">
          <input type="text" placeholder="Enter your .edu email address ">
          <button>Sign up</button>
      </div>
    </div>
</template>

<script>
    export default {
        name: "header"
    }
</script>

<style>
    .header{
        background-image: url("../assets/images/Rectangle.png");
        background-size: cover;
        height: 584px;
        padding: 33px 0 41px 0;




    }
    .header h1{
        width: 488px;
        font-weight: 700;
        font-size: 40px;
        line-height: 48px;
        text-align: center;
        margin: 0 auto 12px auto;
    }
    .header h3{
        font-weight: 400;
        font-size: 27px;
        line-height: 40px;
        text-align: center;
    }
    .header input{
        width: 340px;
        height: 46px;
        background: #FFFFFF;
        border: 2px solid #FFFFFF;
        border-radius: 3px;
        font-weight: 400;
        font-size: 16px;
        padding-left: 22px ;
        margin-right: 32px;

        line-height: 20px;
        color: rgba(0, 0, 0, 0.2);
    }
    .input{
        display: flex;
        justify-content: center;
        margin-top: 316px;
    }
    .header button{
        width: 108px;
        height: 46px;
        background: #190083;
        border-radius: 3px;
        border: none;
        color: white;
        cursor: pointer;
    }

</style>