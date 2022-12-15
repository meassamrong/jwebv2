<script setup>
// import TheWelcome from "../components/header.vue";
</script>

<template>
  <div class="container">
    <div class="main-header">
      <div class="row">
        <div class="headers-left col-6">
          <div class="title">
          <h2>និយាយ និង ចែករំលែកពីបច្ចវិទ្យា <i class="bi bi-code-square"></i></h2>
          <h5><span><b>J'Corp</b></span> ជាឈ្មោះជាខ្ញុំដែលចូលចិត្ត និយាយ និង​ ចែករំលែកពីបច្ចវិទ្យា ភាសាកូដ សុវត្តិភាពអុីណធើណេត<br>
          បើអ្នកចូលចិត្តអាចចូលរួមជាមួយគ្នា​​ យើងនិងចែករំលែកទៅកាន់ សហគមន៍ <b>OPEN-SOURCE</b> ទាំងអស់គ្នា</h5> <br>
         <div class="btn btn-primary"><i class="bi bi-share-fill"></i> ចែករំលែក</div>
        </div>
        </div>
        <div class="headers-right col-6">
          <div class="content-headers">
            <img src="../assets/1_unOgBouwfDUig1BAd6wqqQ-768x603.png" alt="">
            <div class="shadow"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="main-2">
      <div class="project-section">
        <div class="project-sec-title">
          <h2><b>PROJECT Explain</b></h2>
        </div>
        <div class="project">
          <div class="project-name">
            <h3>WEBDEVELOPMENT <i class="bi bi-code-slash"></i></h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@font-face {
  font-family: Koulen;
  src: url('../src/fonts/Koulen-Regular.ttf');
}
@font-face {
  font-family: Ubuntu;
  src: url('../src/fonts/Ubuntu-Regular.ttf');
}
.main-header {
  font-family: Koulen;
  margin-top: 150px;
  color: rgb(6, 124, 187);
}
.main-header h5 {
  font-family: Ubuntu;
  color: rgb(24, 24, 24);
}
.content-headers img{
  height: 500px;
  width: auto;
  animation: contentMedia alternate 8s ease-out infinite;
}
@keyframes contentMedia {
  0%{
    transform: translateY(-10%);
  }
  50%{
    transform: translateY(0%);
  }
  100%{
    transform: translateY(-10%);
  }
}
.shadow {
  filter: blur(40px);
  height: 200px;
  width: 200px;
  border-radius: 50%;
  background-color: rgba(0, 0, 0, 0.548);
  box-shadow: 2px 2px 2px black;
  position: absolute;
  left: 50%;
  transform:rotateX(51deg) rotateZ(43deg) translate(-50%);
  transform-style: preserve-3d;
  animation-name: shadowheaser-Animation; 
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-duration: 8s;

  
}
@keyframes shadowheaser-Animation {
    0%{
      height: 100px;
       width: 100px;
    }
    50%{
      height: 200px;
      width: 200px;
    }
    100%{
      height: 100px;
      width: 100px;
    }
}
.main-2 {
  margin-top: 130px;
  border-top: solid 1px rgba(128, 128, 128, 0.425);
}
.project-sec-title h2{
  font-family: Koulen;
}
.project-name {
  text-decoration: underline;
  color: rgb(24, 24, 24);
}



/* // Small devices (landscape phones, 576px and up) */
@media only screen and (max-width: 768px) { 
.main-header{
    margin-top: 120px;
  }
.content-headers img {
    height: 290px;
}
.shadow {
  height: 80px;
  width: 80px;
  animation-name: shadowheaser-Animation-re; 
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-duration: 8s;
}
@keyframes shadowheaser-Animation-re {
    0%{
      height: 80px;
      width: 80px;
    }
    50%{
      height: 120px;
      width: 120px;
    }
    100%{
      height: 80px;
      width: 80px;
    }
}
}
</style>

