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
  </div>
</template>

<script>
export default {
    name: 'Main',

}
</script>

<style lang="scss">
    
    @import "~@fortawesome/fontawesome-free/css/all.min.css";

    .gp-text{
        line-height: 30px;
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
        
        .gp-button{
            background-color: #79b27b !important;
            border: 1px solid #79b27b !important;
            border-radius: 18px;
        }
    }

    .gp-vertical{
        height: 260px;
        color: white;
        background-image: url(../assets/img/horizontal-cta-background.jpg);
    }
</style>