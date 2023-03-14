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

   <!-- PARTE RECENT COURSES -->

   <div class="main-courses mx-5">

    <div class="row">

        <h1 class="text-center mt-5 pt-5">Recent Courses</h1>
        <!-- navbar -->
        <nav>
         <ul class="d-flex gap-5 justify-content-center mt-5 navbar-course">
              <li v-for="(item, index) in menuItems" :key="index">
                 <a :href="item.url">{{ item.title }}</a>
              </li>
         </ul>
       </nav>
      

       <!-- CARD -->
       <div class="col-10 mt-5">

        <!-- PRIMA LISTA CARD -->
          <ul class="d-flex gap-4">
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/895786_7b4b_2-544x322.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">The Complete iOS 10 & Swift 3 Developer Course</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                   <strong>Free</strong> 
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/1561458_7f3b-544x322.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">CSS -The Complete Guide 2020 (incl. Flexbox, Grid & Sass)</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$199</del> 
                                   <strong>$100</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/246154_d8b0_3-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Web Design for Beginners: Real World Coding in HTML & CSS</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$129</del> 
                                   <strong>$65</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/1208228_d61c_4-544x322.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Digitally Painting Light and Color: Amateur to Master</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$139</del> 
                                   <strong>$70</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/186792_41e4_4-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Become an Arabic Calligraphy Artist from Scratch</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    
                                   <strong>$199</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/1776542_30b1-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Google Searching Ninja!</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$89</del> 
                                   <strong>$45</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
          </ul>


          <!-- SECONDA LISTA CARD -->
          <ul class="d-flex gap-4">
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/949316_2a64_11-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Foundations for Mastering Watercolor Painting</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$19</del> 
                                   <strong>$10</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/366802_6fcc-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text"> Get Wine-Smart</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$49</del> 
                                   <strong>$25</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/381588_2e6d_4-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">The Colored Pencil Drawing Course</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$129</del> 
                                   <strong>$65</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/838056_611a_3-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Paint Realistic Watercolor and Botanicals -STUDIO BASICS</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$69</del> 
                                   <strong>$35</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/1414956_d944_15-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Mastering Brushstrokes -Part 1</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$19</del> 
                                   <strong>$10</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
            <li>
                <div class="card" style="width: 17rem;">
                       <img class="card-img-top" src="../assets/img/1109398_4c13-272x161.jpg" alt="Card image cap">
                           <div class="card-body">
                              <p class="card-title text-secondary"> Development></p>
                              <p class="card-text">Paint Realistic Watercolour and Botanicals – MAGNOLIAS</p>
                              <hr>
                              <ul class="d-flex">
                                <li>
                                    <div class="stars">
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i class="fa-solid fa-star"></i>
                                     <i  class="far fa-star"></i>
                                   </div>
                                </li>

                                <li class="price">
                                    <del>$69</del> 
                                   <strong>$35</strong>
                                </li>

                              </ul>
                            </div>
                    </div>
            </li>
          </ul>

          <div class="col-12 d-flex justify-content-center">
            <button class="show-button">Show all</button>
          </div>




       </div>

    </div> 
   </div>


   <!-- SEARCHBAR AREA -->

   <div class=" row search-main d-flex gap-5 justify-content-center">
    <div class="col-4 ">
        <h4>Subscribe our newsletter</h4>
        <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words
        </p>
    </div>


    <div class="col-3">
        <p>YOUR E-MAIL ADDRESS</p>
        <form class="input-group input-secondnav text-secondary">
                <input type="search" class="form-control" placeholder="Enter your E-mail" aria-label="Search" />
                   <button class="btn button-search" type="button" data-mdb-ripple-color="dark" style="padding: .45rem 1.5rem .35rem;">
                    Subscribe
                    </button>
        </form>


    </div>
        

   </div>


</template>
  
<script>
  import axios from "axios";
export default {
data() {
  return {
    menuItems: [
      { title: 'All categories', url: '/' },
      { title: 'Business', url: '/about' },
      { title: 'Design', url: '/contact' },
      { title: 'Development', url: '/blog' },
      { title: 'IT & Software', url: '/blog' },
      { title: 'Lifestyle', url: '/blog' },
      { title: 'Marketing', url: '/blog' },
      { title: 'Office Productivity', url: '/blog' },
    ]
  }
}
}
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
  /**MAIN CURSES RULES */
  .navbar-course li{
    color: #457992;
  }

  .navbar-course li:hover{
    border: 1px solid #DDE6EB;
    border-radius: 50px;
    background-color:#DDE6EB ;
    padding: 10px;
  }

  /**CARD RULES */

  .card {
    border-radius: 0;
    height: 350px;
  }

  .card img{
    border-radius: 0;
  }
  .stars {
  position: absolute;
  left: 0;
  color: rgb(241, 197, 50);
  margin-left: 10px;
}

.price{
    margin-left: 165px;
    display: flex;
    flex-direction: column;
    
}

/**BUTTON RULES  */
.show-button{
    text-transform: uppercase;
    font-weight: bold;
    text-align: center;
    margin-top: 50px;
    margin-left: 300px;
    margin-bottom: 100px;
    background-color:#FF4550 ;
    border-radius: 40px;
    padding: 20px;
    color: white;
    width: 150px;
}

.show-button:hover{
    background-color: #457992;
}

/**SEARCH MAIN RULES */
.search-main{
    background-color: #FF4550;
}

.col-4 {
    padding: 30px;
    margin-left: 100px;
    color: white;
}

.col-3{
    color: white;
    padding-top: 30px;
}

.button-search{
    text-transform: uppercase;
    color: white;
    background-color: #457992;
    border-radius: 0;
}
  </style>