<template>
  <div class="gp-jumbo-bg">
      <div class="gp-jumbo-top">
          <div class="container h-100">
              <div class="row align-items-center justify-content-lg-between justify-content-md-center h-100">
                  <div class="col-md-12 col-lg-2 text-center">
                        <a href="#">
                            <img class="gp-logo" src="../assets/img/avada-drivers-logo-2x.png" alt="">
                        </a>
                  </div>

                  <div class="col-md-12 col-lg text-md-start text-lg-end">
                      <ul class="gp-nav-menu">
                          <li class="pe-3" v-for="menuVoice in menuVoices" :key="menuVoice.id"><a href="menuVoice.url" :class="{'gp-active': menuVoice.active}" @click="menuVoice.active = !menuVoice.active">{{menuVoice.menuVoice}}</a> <span v-if="menuVoice.isNew" class="gp-new">{{menuVoice.isNew}}</span></li>
                          <li><button class="btn btn-success gp-button">BOOK NOW</button></li>
                      </ul>
                  </div>
              </div>
          </div>
      </div>

      <div class="gp-jumbo-bottom h-75">
          <div class="container h-100">
              <div class="row align-items-center h-100 ">
                  <div class="col">
                      <h1>Drive with Avada</h1>
                      <h3>We offer the finest driving tuition money can buy</h3>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
import menuVoices from "../assets/js/menu.js";

export default {
name: 'Jumbotron',

data(){
    return{
        menuVoices,
    }
},

methods:{

}
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
                width: 240px;
            }

            .gp-nav-menu li{
                display: inline-block;
                font-size: 16px;
                font-weight: bold;
                color: white;

                a{
                    color: white;
                    text-decoration: none;

                    :hover{
                        border-bottom: 4px solid #79b27b;
                    }
                }

                .gp-new{
                    font-size: 10px;
                    padding: 2px 4px;
                    vertical-align: middle;
                    background-color: #79b27b;
                    border-radius: 4px;
                }

                .gp-button{
                    background-color: #79b27b !important;
                    border: 1px solid #79b27b !important;
                }

                .gp-active{
                    color: #79b27b;
                    padding-bottom: 6px;
                    border-bottom: 4px solid #79b27b;
                }
            }
            
        }

        .gp-jumbo-bottom{
            font-weight: bold;
            color: white;
        }
    }
</style>