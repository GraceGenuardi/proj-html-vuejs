<template>
   <div class="main">
    <div class="row">
        <div class="col-5">
            <ul>
                <li><h1>Limitless learning,more possibilities</h1></li>
                <li><p class="mt-4">Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.</p></li>
                <li><button class="read-more"> <strong>Read More</strong></button></li>
            </ul>
        </div>
    </div>
   </div>


</template>
  
<script>

</script>

  
  <style lang="scss" scoped>
  @use '../style/partials/variables' as *;

  .main {
    background-image: url(../assets/img/bg.png);
    padding: 90px;
  }

  .col-5{
    margin-left: 150px;
    margin-top: 70px;
    
  }

  .read-more{
    background-color: #FF4450;
    color: white;
    border: 1px solid #FF4450;
    border-radius: 30px;
    width: 150px;
    padding: 15px;
    margin-top: 20px;
    text-transform: uppercase;
}
  
  </style>