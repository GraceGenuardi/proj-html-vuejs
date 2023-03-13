<template>
    <div class="sales">

        
            <div class="col-6 sales-title">
                  <h1>Udemy Affiliate Sales</h1>
                  <h3>Monetize your audience and attract new costumers with Udemy!</h3>
            </div>
            <div class="col-6">
                <img src="../assets/img/slide-1.jpg" alt="Our Sales">

            </div>
        
    </div>


</template>
  
<script>

</script>

  
  <style lang="scss" scoped>
  @use '../style/partials/variables' as *;

  .sales{
    background-color: #FF4450;
    margin-top: 30px;
    color: white;
    display: flex;
  }
  
  .sales-title{
    padding-top: 100px;
    padding-left: 300px;
  }
  
  .col-6 img {
    clip-path: polygon(0 0, 100% 0, 100% 100%, 20% 100%);
  }

  
  </style>