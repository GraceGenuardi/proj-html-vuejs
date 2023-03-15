<template>
    <div class="start d-flex justify-content-center gap-4 mt-5 pt-3 mb-5 pb-5">
       <div class="col-5 d-flex">
         <div class="immagine">
            <img src="../assets/img/image_box_1-221x231.png" alt="Instructor">
         </div>
         <div class="contenuto col-6 pt-3">
             <h2>Become an instructor</h2>
             <p class="fs-5  text-secondary">Teach what you love. Masterstudy gives you the tools to create a course.</p>
             <button class="button-start">Start teaching</button>
         </div> 
       </div>

       <div class="col-5 d-flex">
         <div class="immagine">
            <img src="../assets/img/image_box_2-234x231.png" alt="Business">
         </div>
         <div class="contenuto col-6 pt-3"> 
              <h2>Access For Business</h2>
              <p class="fs-5  text-secondary">Get unlimited access to 2,500 of top courses for your team.</p>
              <button class="button-start">Doing business</button>
         </div>   
       </div>
        
          
        
    </div>


</template>
  
<script>
</script>

  
  <style lang="scss" scoped>
  @use '../style/partials/variables' as *;
  .col-5 {
    border: 1px solid grey;
    padding-top: 100px;
    padding-left: 50px;
    padding-bottom: 50px;
  }
  .immagine {
    margin-right: 40px;
  }
  
  .button-start{
    background-color: #FF4450;
    color: white;
    border: 1px solid #FF4450;
    border-radius: 30px;
    width: 200px;
    padding: 15px;
    margin-top: 20px;
    text-transform: uppercase;
    font-weight: bold;
}
.button-start:hover{
    background-color: #31cea2;
    border: #31cea2;
   
}
  </style>