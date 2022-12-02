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
  </div>
</template>

<style scoped>

@font-face {
  font-family: Koulen;
  src: url('../../public/fonts/Koulen-Regular.ttf');
}
@font-face {
  font-family: Ubuntu;
  src: url('../../public/fonts/Ubuntu-Regular.ttf');
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
  animation: contentMedia alternate 8s linear infinite;
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
  filter: blur(30px);
  height: 200px;
  width: 200px;
  border-radius: 50%;
  background-color: rgba(0, 0, 0, 0.267);
  box-shadow: 2px 2px 2px 2px black;
  position: absolute;
  transform:rotateX(51deg) rotateZ(43deg) translate(90% -50%);
  transform-style: preserve-3d;
  


}
/* .main-header {
  background-image: url('../assets/3274387.jpg');
  height: 500px;
  width: 100%;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 5px;
  transform: ;
} */
</style>
