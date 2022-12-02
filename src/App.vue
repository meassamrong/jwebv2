<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
 <!-- <header>

     <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/login">Login</RouterLink>
      </nav>
    </div> 
    
  </header> -->
  <div class="content-header">
        <div class="container">
            <div class="row">
                <div class="logo col-4">
                  <RouterLink to="/"><img src="../src/assets/j-logo.png" alt=""></RouterLink>    
                </div>
                <div class="menu col-8 text">
                    <ul class="list-group list-group-horizontal">
                        <li class="list-group list-group-horizontal"><RouterLink to="/">Home</RouterLink></li>
                        <li class="list-group list-group-horizontal"><RouterLink to="/">Blog</RouterLink></li>
                        <li class="list-group list-group-horizontal"><RouterLink to="/">Project</RouterLink></li>
                        <li class="list-group list-group-horizontal"><RouterLink to="/">About</RouterLink></li>
                        <li class="list-group list-group-horizontal"><RouterLink to="/about">Support</RouterLink></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
  <RouterView />
</template>

<style scoped>
@font-face {
  font-family:AnekDevanagari ;
  src: url('../public/fonts/AnekDevanagari-VariableFont_wdth\,wght.ttf');
}
  .content-header {
    background-color: rgb(243, 243, 243);
  }
  .logo img {
    height: 55px;
    width: auto;
    padding-top: 10px;
  }
  .menu {
    color: rgb(24, 24, 24);
    font-family:AnekDevanagari ;
    padding: 0px !important;
  }
  .menu ul{
    font-size: 0px;
    float: right;
  }
  
  .menu ul li{
    text-align: center;
  }
  .menu ul li a{
    color: rgb(24, 24, 24);
    text-decoration: none;
    font-size: 25px;
    padding: 10px 10px;
    padding-top: 15px !important;
    transition: all 300ms !important;
    text-align: center;
    border-bottom: solid 1px rgba(6, 124, 187, 0);
  }
  .menu ul li a:hover{
    color: rgb(6, 124, 187);
    border-bottom: solid 1px rgb(6, 124, 187);
  }
</style>
