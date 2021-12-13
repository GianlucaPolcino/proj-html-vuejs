<template>
  <div class="gp-jumbo-bg">
      <div class="gp-jumbo-top">
          <div class="container h-100">
              <div class="row align-items-center justify-content-between h-100">
                  <div class="col">
                        <a href="#">
                            <img class="gp-logo" src="../assets/img/avada-drivers-logo-2x.png" alt="">
                        </a>
                  </div>

                  <div class="col text-end">
                      <ul class="gp-nav-menu">
                          <li><a href="">HOME</a></li>
                          <li><a href="">ABOUT</a></li>
                          <li><a href="">PRICES</a></li>
                          <li><a href="">COURSES</a></li>                          
                      </ul>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
name: 'Jumbotron',
}
</script>

<style lang="scss">
    .gp-jumbo-bg{
        height: 600px;
        background-image: url(../assets/img/homepage-hero-background.jpg);
        background-repeat:  no-repeat;
        background-size: cover;

        .gp-jumbo-top{
            height: 120px;
            background-color: #48484849;

            .gp-logo{
                width: 320px;
            }

            .gp-nav-menu li{
                display: inline-block;
                font-size: 24px;
                font-weight: bold;
                color: white;

                a{
                    color: white;
                    text-decoration: none;
                }
            }
            
        }
    }
</style>