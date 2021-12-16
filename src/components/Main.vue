<template>
  <div>

      <!-- FIRST SECTION -->

      <div class="container">
          <div class="row">
              <div class="col-6 py-5">
                  <h2 class="fw-bold py-5">Get Behind The Wheel</h2>
                  <h5 class="text-secondary pb-5 gp-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus asperiores labore ad, voluptatum pariatur alias ab laborum culpa id obcaecati aliquam nobis voluptates optio quod assumenda quasi ipsam a? Suscipit.</h5>
                  <h6 class="text-secondary gp-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi eos minima repellendus voluptas quibusdam nihil blanditiis quis, placeat magnam consequuntur vitae illo molestias porro magni error commodi, dolorum id libero.</h6>
              </div>

              <div class="col-6">
                  <div class="gp-lesson p-5 text-center shadow-lg rounded-3">
                      <h2>First Lesson Free!</h2>
                      <h5 class="text-secondary p-5">When you make a block booking with us your first lesson is included free.</h5>

                       <div class="mb-3">
                            <input type="name" class="form-control p-3 gp-form" aria-describedby="nameHelp" placeholder="Your name*">
                        </div>

                        <div class="mb-3">
                            <input type="email" class="form-control p-3 gp-form" aria-describedby="emailHelp" placeholder="Email*">
                        </div>
                        
                        <div class="mb-3">
                            <input type="telephone" class="form-control p-3 gp-form" aria-describedby="telephoneHelp" placeholder="Telephone">
                        </div>
                        <div class="mb-5">
                            <input type="location" class="form-control p-3 gp-form" aria-describedby="locationHelp" placeholder="Location">
                        </div>

                        <button class="btn btn-success gp-button px-4 py-2">REQUEST A CALLBACK</button>
                  </div>
              </div>
          </div>
      </div>

     <!-- SECOND SECTION -->

      <div class="mt-5 gp-vertical">
          <div class="container h-100">
              <div class="row h-100 align-items-center justify-content-center">
                  <div class="col">
                      <h2 class="fw-bold">Start Learning to Drive Today!</h2>
                      <h4 class="fw-bold pt-2">Give us a call to schedule your first driving lesson</h4>
                  </div>
                  
                  <div class="col text-end">
                      <h2 class="fw-bold"><i class="fas fa-phone me-3"></i> 1-800-555-555</h2>
                  </div>
              </div>
          </div>
      </div>

      <!-- THIRD SECTION -->
      
      <div class="gp-third-section">
          <div class="container">
            <div class="row">

              <div class="col-lg-6 col-md-12">
                  <div class="gp-courses shadow-lg rounded-3">
                    <img src="../assets/img/new-corner.jpg" alt="">
                    <div class="text-center container">
                        <h2 class="pb-5">Courses</h2>
                        <p class="text-secondary gp-text pb-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil vitae illo perferendis recusandae nam voluptate quia ad quam totam, tempore voluptates suscipit magnam ipsum maiores eveniet voluptas ea voluptatem vero.</p>
                        <button class="btn btn-success gp-button mb-5">COURSE INFORMATION</button>
                    </div>
                  </div>
              </div>

              <div class="col-lg-6 col-md-12 pt-5 gp-course-choice">
                  <div v-for="course in courses" :key="course.id" class="d-inline-block text-center p-2">
                      <img class="gp-course-img pb-3" :src="course.img" alt="course.img">
                      <h4 class="pb-3">{{course.title}}</h4>
                      <button class="btn btn-outline-primary">LEARN MORE</button>
                  </div>
              </div>
          </div>
         </div>
      </div>

      <!-- INTERLUDE BACKGROUND -->

      <div>
          <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#e4eaed;padding:0;"><path d="M-1 -1 L50 99 L101 -1 Z"></path></svg>
      </div>

      <!-- FOURTH SECTION -->

      <div class="gp-wrapper p-5">
          <div class="container">
            <div class="row">
              <div class="col gp-border py-5 mx-3 shadow-lg text-center">
                    <div class="circle-border-1">
                        <div class="circle-1 d-flex align-items-center justify-content-center">
                            <h4 class="fw-bold">95%</h4>
                        </div>
                    </div>
                    <h6 class="pt-5 fw-bold text-secondary">PASS RATE</h6>
              </div>

              <div class="col gp-border py-5 mx-3 shadow-lg text-center">
                    <div class="circle-border-2">
                        <div class="circle-2 d-flex align-items-center justify-content-center">
                            <h4 class="fw-bold">100%</h4>
                        </div>
                    </div>
                    <h6 class="pt-5 fw-bold text-secondary">REFERRAL RATE</h6>
              </div>

              <div class="col gp-border py-5 mx-3 shadow-lg text-center">
                    <div class="circle-border-3">
                        <div class="circle-3 d-flex align-items-center justify-content-center">
                            <h4 class="fw-bold">0%</h4>
                        </div>
                    </div>
                    <h6 class="pt-5 fw-bold text-secondary">ACCIDENT RATE</h6>
              </div>
          </div>
         </div>
      </div>

      <!-- FIFTH SECTION -->

      <div class="container pt-5">
          <div class="row">
              <div class="col-12">
                  <h2 class="fw-bold">Your Instructors</h2>
              </div>

              <div class="col-9 pt-3">
                  <h6 class="text-secondary gp-text">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. A corrupti eius id repellat natus earum necessitatibus, voluptatibus pariatur veniam atque rerum illo praesentium libero odio officiis repudiandae quae itaque voluptas.
                  </h6>
              </div>

              <div class="col pt-3">
                  <button class="btn btn-success gp-button px-5">
                      MORE ABOUT US
                  </button>
              </div>
          </div>

            <!-- CARDS SECTION -->

          <div class="row pt-5">
              <div class="col gp-border py-5 mx-3 shadow-lg text-center"
              v-for="instructor in instructors" :key="instructor.id">
                    <img class="w-100 pb-5" :src="instructor.img" alt="">
                    <h3 class="fw-bold">{{instructor.name}}</h3>
                    <i class="fab fa-facebook-f pe-3 text-secondary"></i>
                    <i class="fab fa-twitter pe-3 text-secondary"></i>
                    <i class="fab fa-instagram text-secondary"></i>
                    <p class="pt-3 text-secondary">{{instructor.description}}</p>
              </div>
          </div>
      </div>

      <!-- TESTIMONIALS SECTION -->

      <div class="gp-testimonials">
          
      </div>

  </div>
</template>

<script>

import courses from "../assets/js/courses";
import instructors from "../assets/js/instructors";
export default {
    name: 'Main',

    data(){
        return{
            courses,
            instructors,
        }
    }

}
</script>

<style lang="scss">
    
    @import "~@fortawesome/fontawesome-free/css/all.css";

    .gp-text{
        line-height: 40px;
    }

    .gp-button{
        background-color: #79b27b !important;
        border: 1px solid #79b27b !important;
        border-radius: 20px !important;
    }

    .gp-lesson{
        margin-top: -90px;
        background-color: white;

        h2{
            color: #79b27b;
        }

        .gp-form{
            background-color: #e5e8eb;
        }
        
    }

    .gp-vertical{
        height: 260px;
        color: white;
        background-image: url(../assets/img/horizontal-cta-background.jpg);
    }

    .gp-third-section{


        height: 500px;
        background-image: url(../assets/img/promise-background.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: 100% 99%;
    }

    .gp-courses{
        margin-top: -40px;
        background-color: white;
        overflow: hidden;

        img{
            width: 80px;
        }
    }
    
    .gp-course-choice{
        img{
            width: 160px;
        }

        h4{
            color: #7f9ea8;
        }

        button{
            color: #7f9ea8;
            border: 1px solid #7f9ea8 !important;
            border-radius: 20px !important;

            &:hover{
                background-color: #7f9ea8 !important;
            }
        }

        
    }

    .gp-border{
        background-color: white;
        border-top: 4px solid #79b27b;
        border-radius: 4px;
            
    }

   .gp-wrapper{

    margin-top: -90px;
    
        .circle-1 {
            position: relative;
            top: 5px;
            left: 5px;
            text-align: center;
            width: 100px;
            height: 100px;
            border-radius: 100%;
            background-color: #ffffff;
        }

        .circle-border-1 {
            position: relative;
            text-align: center;
            width: 110px;
            height: 110px;
            margin-left: 33%;
            border-radius: 100%;
            background-color: #E53B3B;
            background: linear-gradient(270deg, #79b27b 50%, transparent 50%), linear-gradient(60deg, #79b27b 50%, lightgray 50%)
        }

        .circle-2 {
            position: relative;
            top: 5px;
            left: 5px;
            text-align: center;
            width: 100px;
            height: 100px;
            border-radius: 100%;
            background-color: #ffffff;
        }

        .circle-border-2 {
            position: relative;
            text-align: center;
            width: 110px;
            height: 110px;
            margin-left: 33%;
            border-radius: 100%;
            background-color: #E53B3B;
            background: linear-gradient(270deg, #79b27b 50%, transparent 50%), linear-gradient(90deg, #79b27b 50%, lightgray 50%)
        }

        .circle-3 {
            position: relative;
            top: 5px;
            left: 5px;
            text-align: center;
            width: 100px;
            height: 100px;
            border-radius: 100%;
            background-color: #ffffff;
        }

        .circle-border-3 {
            position: relative;
            text-align: center;
            width: 110px;
            height: 110px;
            margin-left: 33%;
            border-radius: 100%;
            background-color: #E53B3B;
            background: linear-gradient(0deg, lightgray 50%, transparent 50%), linear-gradient(360deg, transparent 50%, lightgray 50%)
        }

        
   }
    
</style>