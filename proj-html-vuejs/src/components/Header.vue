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
                  <li v-for="item in items">{{ item.message }}</li>
                  <li v-for="item in items">{{ item.messagetwo }}</li>
                  <li v-for="item in items">{{ item.messagethree }}</li>
                  <li v-for="item in items">{{ item.messagefour }}</li>
                  <li v-for="item in items">{{ item.messagefive }}</li>
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

    <!-- SECONDA NAVBAR -->

    <div class="container-navbar">

        <div class="row p-4">
           
            <div class="col-2 logo">
                <img src="../assets/img/MasterStudy.svg" alt="logo">
            </div>

            <!-- Navbar brand -->
            <div class="col-4 d-flex navbar-search">
                
                <i class="fa-solid fa-bars pt-3"></i> <p class="text-uppercase text-secondary px-2 pt-3">Category</p>
                 <!-- Search form -->
             <form class="input-group input-secondnav">
                <input type="search" class="form-control" placeholder="Search courses" aria-label="Search" />
                   <button class="btn button-search" type="button" data-mdb-ripple-color="dark" style="padding: .45rem 1.5rem .35rem;">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
              </form>
            </div>

            <!-- Pulsanti -->
            <div class="col-5 d-flex">
                <ul class="d-flex button-list">
                    <li> <i class="fa-solid fa-bullhorn"></i> <a href=""> Become an Instructor</a></li>
                    <li> <i class="fa-solid fa-briefcase"></i>  <a href="">For Enterprise</a></li>
                </ul>
                <ul class="d-flex button-list-2">
                    <li><i class="fa-regular fa-user"></i>  Log In</li>
                    <li><button class="sign-up"><p> Sign up</p></button></li>
                    <li class="bookmark"><i class="fa-regular fa-bookmark"></i></li>
                </ul>
            </div>
        </div>
    
           

            

    </div>

    <!-- TERZA NAVBAR -->

    <div class=" blue-bar">
        <div class="row">
            <div class="col-11">
                <ul class="product-list">
                    <li> <i class="fa-solid fa-chart-line"></i><a href="">Business</a>   </li>
                    <li><i class="fa-solid fa-palette"></i><a href="">Design</a> </li>
                    <li><i class="fa-solid fa-gear"></i><a href="">Development</a> </li>
                    <li><i class="fa-solid fa-face-smile"></i><a href="">Lifestyle</a> </li>
                    <li><i class="fa-solid fa-print"></i><a href="">Office Productivity</a> </li>
                </ul>
            </div>
        </div>
    </div>
    



</template>
  
  <script>
  import axios from "axios";
export default {
  data() {
  return {
    items: [{ message: 'Home',messagetwo: 'Pages',messagetwo: 'Course Formats',messagethree: 'Courses',messagefour: 'Demos',messagefive: 'Pages' }]
  }
}
}
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

  .navbar-nav li {
    margin-right: 20px;
  }

  /**SEARCH NAVBAR RULES */
  .navbar-search P {
    font-size: 13px;
    
  }

  .form-control{
    background-color: #F0F2F5;
    border-radius: 0;
  }

  .button-search{
    color: white;
    border-radius: 0;
    background-color: #457992;
  }
  .button-search:hover{
    background-color: #457992;
  }

  .input-secondnav{
    height: 20px;
    width: 900px;
    margin-top: 10px;
  }

  .logo{
    margin-left: 40px;
    margin-top: 5px;
  }

  .button-list{
    display: flex;
    gap: 30px;
   padding-top: 20px;
  }

  .button-list-2{
    display: flex;
    gap: 30px;
   padding-top: 20px;
   margin-left: 80px;
  }

  .button-list i,.button-list-2 i {
    color: #457992;
    margin-right: 5px;
  }

  .bookmark i {
    font-size: 26px;
    margin-right: 20px;
  }

  .sign-up{
    background-color: #FF4450;
    color: white;
    border: 1px solid #FF4450;
    border-radius: 30px;
    width: 130px;
    margin-top: -20px;
  }
  .sign-up p{
    text-transform: uppercase;
    font-weight: bold;
    text-align: center;
    margin-top: 20px;
    
  }

  .sign-up:hover{
    background-color:#457992 ;
    border: 1px solid #457992;
  }

  /**Blue bar RULES */
  .blue-bar{
    background-color:#273044 ;
    color: white;
    margin-top: -10px;
 }

 .product-list{
    display: flex;
    justify-content: center;
    gap:50px;
    padding: 20px;
    padding-top: 30px;
 }
 
 .blue-bar i{
    margin-right: 10px;
 }
  </style>