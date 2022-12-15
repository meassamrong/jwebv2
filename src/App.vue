<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="contentm-headerm mobile">
    <div class="navbar">
      <div class="row col-12">
        <div class="logo col-6">
          <img src="../src/assets/j-logo.png" alt="">
        </div>
        <div class="nav-menu col-6">
          <ul class="list-group list-group-horizontal">
            <li><RouterLink to="/"><i class="bi bi-search"></i></RouterLink></li>
            <li><RouterLink to="/"><i class="bi bi-person-circle"></i></RouterLink></li>
          </ul>
        </div>
      </div>
      <div class="row col-12">
        <div class="menuM-group">
          <ul class="list-group list-group-horizontal">
            <li class="list-group list-group-horizontal"><RouterLink to="/"><i class="bi bi-house"></i></RouterLink></li>
            <li class="list-group list-group-horizontal"><RouterLink to="/"><i class="bi bi-newspaper"></i></RouterLink></li>
            <li class="list-group list-group-horizontal"><RouterLink to="/"><i class="bi bi-code-square"></i></RouterLink></li>
            <li class="list-group list-group-horizontal"><RouterLink to="/"><i class="bi bi-info-circle"></i></RouterLink></li>
            <li class="list-group list-group-horizontal"><RouterLink to="/"><i class="bi bi-currency-dollar"></i></RouterLink></li>
          </ul>
        </div>
      </div>
    </div>

  </div>
  <div class="content-header desktop">
        <div class="container">
            <div class="row">
                <div class="logo col-4">
                  <RouterLink to="/"><img src="../src/assets/j-logo.png" alt=""></RouterLink>
                </div>
                <div class="menu col-8">
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
  src: url('../src/fonts/AnekDevanagari-VariableFont_wdth\,wght.ttf');
}
.mobile {
  display: none;
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
    display: inline-block;
    padding-top: 10px;
  }
  .menu ul li a{
    color: rgb(24, 24, 24);
    text-decoration: none;
    font-size: 25px;
    padding: 0px 10px;
    transition: all 300ms !important;
    text-align: center;
    border-bottom: solid 1px rgba(6, 124, 187, 0);
  }
  .menu ul li a:hover{
    color: rgb(6, 124, 187);
    border-bottom: solid 1px rgb(6, 124, 187);
  }
</style>
