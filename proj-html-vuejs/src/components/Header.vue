<template>
    
    <header class="main-header">
     <div class="row d-flex justify-content-between">
        <!-- SELECT LINGUA  -->
        <div class="col-3 px-5 pt-3">
            <div class="select-wrapper">

               <select id="defaultSelect" class="border border-light text-secondary">
                 <option selected="" value="">English</option>
                 <option value="Value 1">Deutsch</option>
                 <option value="Value 2">Italian</option>
               </select>
               
            </div>
        </div>

        <!-- PRIMA NAVBAR -->
        <div class="col-4">
           <nav class="navbar navbar-expand-lg">
    <!-- Container wrapper -->
       <div class="container">
        
        <div class="collapse navbar-collapse" id="navbarButtonsExample">
            <!-- Menù links -->
            <ul class="navbar-nav  mb-2 mb-lg-0 text-secondary">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Pages</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Course Formats</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Courses</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Demos</a>
                </li>
            </ul>
            
             <!-- Social icons -->
            <ul class="navbar-nav d-flex flex-row text-secondary">
                <!-- Icons -->
                <li class="nav-item me-3 me-lg-0">
                    <a class="nav-link" href="#">
                        <i class="fa-brands fa-facebook"></i>
                    </a>
                </li>
                <li class="nav-item me-3 me-lg-0">
                    <a class="nav-link" href="#">
                        <i class="fab fa-twitter"></i>
                    </a>
                </li>
                <li class="nav-item me-3 me-lg-0">
                    <a class="nav-link" href="#">
                        <i class="fa-brands fa-instagram"></i>
                    </a>
                </li>
                <li class="nav-item me-3 me-lg-0">
                    <a class="nav-link" href="#">
                        <i class="fa-brands fa-linkedin"></i>
                    </a>
                </li>
                <li class="nav-item me-3 me-lg-0">
                    <a class="nav-link" href="#">
                        <i class="fa-brands fa-google-plus"></i>
                    </a>
                </li>
                <li class="nav-item me-3 me-lg-0">
                    <a class="nav-link" href="#">
                        <i class="fa-brands fa-youtube"></i>
                    </a>
                </li>
            </ul>
        </div>
        
    </div>
   
</nav>


        </div>

     </div>
     
    </header>



</template>
  
  <script>
  
</script>

  
  <style lang="scss" scoped>
  @use '../style/partials/variables' as *;
  .main-header {
    border-bottom: 1px solid grey;
    font-size: 15px;
    
  }

  a:hover{
    color:#457992 ;
  }

  
  </style>