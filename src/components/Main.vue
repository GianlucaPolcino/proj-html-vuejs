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

              <div class="col-6">
                  <div class="gp-courses shadow-lg rounded-3">
                    <img src="../assets/img/new-corner.jpg" alt="">
                    <div class="text-center container">
                        <h2 class="pb-5">Courses</h2>
                        <p class="text-secondary gp-text pb-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nihil vitae illo perferendis recusandae nam voluptate quia ad quam totam, tempore voluptates suscipit magnam ipsum maiores eveniet voluptas ea voluptatem vero.</p>
                        <button class="btn btn-success gp-button mb-5">COURSE INFORMATION</button>
                    </div>
                  </div>
              </div>

              <div class="col-6 pt-5 gp-course-choice">
                  <div v-for="course in courses" :key="course.id" class="d-inline-block text-center p-2">
                      <img class="gp-course-img pb-3" :src="course.img" alt="course.img">
                      <h4 class="pb-3">{{course.title}}</h4>
                      <button class="btn btn-outline-primary">LEARN MORE</button>
                  </div>
              </div>
          </div>
         </div>
      </div>

      <!-- FOURTH SECTION -->

      <div>
          <svg class="fusion-big-triangle-candy" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="100" viewBox="0 0 100 100" preserveAspectRatio="none" style="fill:#e4eaed;padding:0;"><path d="M-1 -1 L50 99 L101 -1 Z"></path></svg>
      </div>
  </div>
</template>

<script>

import courses from "../assets/js/courses";
export default {
    name: 'Main',

    data(){
        return{
            courses,
        }
    }

}
</script>

<style lang="scss">
    
    @import "~@fortawesome/fontawesome-free/css/all.min.css";

    .gp-text{
        line-height: 30px;
    }

    .gp-button{
        background-color: #79b27b !important;
        border: 1px solid #79b27b !important;
        border-radius: 20px !important;
    }

    .gp-lesson{
        margin-top: -40px;
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
        // background-attachment: fixed;
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
    
</style>