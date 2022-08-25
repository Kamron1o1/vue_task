<template>
    <div class="Full-time">
        <h1>Full-time. Part-time. Paid internships.</h1>
        <p>Handshake has the latest jobs from employers hiring at your school</p>\
    </div>
  <div class="card-boss">
      <div class="card">
      <div class="card-header">
          <img src="../assets/images/Frame(3).png" alt="">
      </div>
      <div class="card-body">
          <h3>Find jobs for you</h3>
          <p>Receive personalized job recommendations</p>
      </div>
  </div>
      <div class="card">
          <div class="card-header">
              <img src="../assets/images/Frame(4).png" alt="">
          </div>
          <div class="card-body">
              <h3>Attend virtual recruiting events</h3>
              <p>Stand out to employers during virtual fairs and events</p>
          </div>
      </div>
      <div class="card">
          <div class="card-header">
              <img src="../assets/images/Frame(5).png" alt="">
          </div>
          <div class="card-body">
              <h3>Get hired</h3>
              <p>Apply to jobs meant for students like you</p>
          </div>
      </div></div>
   <div class="btn">
       <button>How it works</button>
   </div>
</template>

<script>
    export default {
        name: "main"
    }
</script>

<style >
    .Full-time h1{
        font-weight: 700;
        font-size: 40px;
        line-height: 48px;
        width: 422px;
        text-align: center;
        margin: 92px auto 53px auto;
    }
    .Full-time p{
        font-weight: 400;
        font-size: 22px;
        line-height: 32px;
        text-align: center;
    }
    .card-boss{
        display: flex;
        justify-content: space-between;
        width: 1200px;
        margin: 0 auto;

    }
    .card-header {
        margin-top: 90px;
        text-align: center;


    }
     .card-body h3{
        font-weight: 700;
        font-size: 22px;
        line-height: 24px;
        text-align: center;
        margin-top: 51px;
    }
    .card-body p{
        font-weight: 400;
        font-size: 18px;
        line-height: 28px;
        text-align: center;
        margin-top: 22px;
    }
    .btn{
        margin: 78px 0 0 0;
        text-align: center;
    }
    .btn button{
        background: #190083;
        border-radius: 3px;
        height: 52px;
        width: 148px;
        border: none;
        color: white;
        font-weight: 700;
        font-size: 16px;
        line-height: 20px;
    }


</style>