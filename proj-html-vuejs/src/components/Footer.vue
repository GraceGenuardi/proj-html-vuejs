<template>
    <div class="footer">

    <div class="header-footer d-flex justify-content-center gap-3">
        <!-- ABOUT -->
      <div class="col-2 p-4 mt-4">
        <h5 class="mb-4">ABOUT</h5>
        <p>Sed nec felis pellentesque, lacinia dui sed, ultricies sapien. Pellentesque orci lectus, consectetur vel, rutrum eu ipsum. Mauris accumsan eros eget libero posuere vulputate.</p>

      </div>

      <!-- CONTACT -->
      <div class="col-2">
        <h5 class="mb-4">CONTACT</h5>
        <p>USA, Callifornia 20, First Avenue, Callifornia</p>

        <p>Tel.: +1 212 458 300 32</p>
        <p class="tel">Fax: +1 212 375 24 14</p>
        

        <p class="email">info@masterstudy.com</p>
      </div>

      <!-- SOCIAL NETWORK -->
      <div class="col-2">
        <h5 class="mb-4">Social network</h5>

        <div class="social">

         <ul class="d-flex gap-3">
             <li class="fb"><i class="fa-brands fa-facebook"></i></li>
             <li class="ig"><i class="fa-brands fa-instagram"></i></li>
             <li class="linkedin"><i class="fa-brands fa-linkedin"></i></li>
             <li class="pinterest"><i class="fa-brands fa-pinterest"></i></li>
         </ul>


           <ul class="d-flex gap-3">
              <li class="twitter"><i class="fa-brands fa-twitter"></i></li>
              <li class="dribbble"><i class="fa-brands fa-dribbble"></i></li>
              <li class="google"><i class="fa-brands fa-google-plus"></i></li>
              <li class="skype"><i class="fa-brands fa-skype"></i></li>
            </ul>

        </div>

      </div>

      <!-- UDEMY -->
      <div class="col-2">
        <img src="../assets/img/Top-udemy-courses-90-percent-off.jpg" alt="top-udemy">
      </div>
        
            
    </div>

    <div class="copy-footer">
        <img src="../assets/img/footer-logo2x-50x56.png" alt="footer-logo">
        <p>Copyright © 2022. <u>MasterStudy</u> Theme by <u>StylemixThemes</u></p>
    </div>
    
    
    </div>


</template>
  
<script>

</script>

  
  <style lang="scss" scoped>
  @use '../style/partials/variables' as *;

  .footer{
    background-color: #273044;
    margin-top: -55px;
    color: white;
  }


  /**HEADER FOOTER RULES */

.header-footer{
    border-bottom: 1px solid grey;
}
.col-2{
    padding-top: 50px;
}

.col-2 p{
    font-size: 13px;
}

.tel {
    margin-top: -15px;
}

.email{
    color: rgb(190, 188, 188);
}

h5{
    text-transform: uppercase;
}

/**SOCIAL RULES */
li{
    border-radius: 50%;
    width: 45px;
    height: 45px;
    text-align: center;
    padding-top: 8px;
    font-size: 19px;
}

.social{
    margin-left: -30px;
}

/**IMG RULES */

.col-2 IMG{
    width: 280px;
    height: 170px;
    margin-bottom: 30px;
}

/**ELENCO ICONE-COLORI */
.fb{
  background-color: #3B5998;
}

.ig{
 background-color:#C32AA3 ;
}

.linkedin{
    background-color: #0077B5;
}

.pinterest{
     background-color:#BD081C ;
}

.twitter{
    background-color: #1DA1F2;
}
.dribbble{
    background-color: #EA4C89;
}

.google{
    background-color: #DB4437;
}

.skype{
    background-color: #00AFF0;
}

/**COPYFOOTER RULES */

.copy-footer{
    font-size: 15px;
    padding-left: 300px;
    padding-top: 20px;
    padding-bottom: 20px;
    display: flex;
}

.copy-footer img{
    width: 25px;
    height: 25px;
    margin-right: 20px;
}

  </style>