<template>

  <footer>
    <!-- Linking  -->
    <div class="context">

      <div class="flex sm:space-x-4 flex-col bg-slate-900 text-white  items-center space-y-4  pb-4
      lg:flex-row space-x-4 justify-between pl-8 pr-8">
    
    <div>
      <h1 class="text-xl text-center md:mt-5">CONTACT US</h1>
      <div class="mt-4 flex flex-col space-y-2 text-slate-400 text-sm items-center">
        <h1>PHONE : 7578787832</h1>
        <h1>EMAIL : venturetank@gmail.com</h1>
      </div>
    </div>

    <div>
      <h1 class="text-xl text-center ">MENU</h1>
    <div class="flex flex-col pt-5 space-y-4  text-slate-400 text-sm md:flex-row space-x-4 justify-center md:space-y-0 ">
      <a href="#" class="text-center">HOME</a>
      <a >ABOUT US</a>                                  
      <a>TIMELINE</a>
      <a>PRIZES</a>
      <a class="pb-2">FAQ</a>
    </div>
    </div>
    

    <div class="">
      <h1 class="text-xl ">CONNECT WITH US</h1>
      <div class="flex mt-4 space-x-0">
        <a><img src="" alt="instagram" class="hver h-12 w-20 mx-0" /></a>
        <img src="" alt="linkedin" class="h-12 w-20" />
      </div>
    </div>

   </div>
   
   <div class="bg-slate-900 text-white text-xs flex flex-row justify-center pb-3 ">
     <h1>MADE WITH ❤️ BY TEAM VENTURE TANK</h1>
    </div>
  </div>
    </footer>

  

    <!-- ----------------------------------------------- -->
    <div>
      <div class="area">
        <ul class="circles">
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
  </div>

</template>

<script>



export default {

  name: "FooterSection",
  components: {

  }
}
</script>

<style scoped>


 .hoverr
 {
  color: #00aced;
    text-shadow: 0 0 15px #00aced;
    transition: all 0.5s ease;
 }

 a:hover{
  background-color: aqua;
 }

/*******************************************************/
.circles {
   position: absolute;
   top: 0;
   left: 0;
   width: 100%;
   height: 100%;
   overflow: hidden;
 }

 .circles li {
   position: absolute;
   display: block;
   list-style: none;
   width: 15px;
   height: 15px;
   background: rgba(255, 255, 255, 0.2);
   animation: animate 25s linear infinite;
   bottom: -150px;
 }

 .circles li:nth-child(1) {
   left: 25%;
   width: 15px;
   height: 15px;
   animation-delay: 0s;
 }

 .circles li:nth-child(2) {
   left: 10%;
   width: 15px;
   height: 15px;
   animation-delay: 2s;
   animation-duration: 12s;
 }

 .circles li:nth-child(3) {
   left: 70%;
   width: 15px;
   height: 15px;
   animation-delay: 4s;
 }

 .circles li:nth-child(4) {
   left: 40%;
   width: 15px;
   height: 15px;
   animation-delay: 0s;
   animation-duration: 18s;
 }

 .circles li:nth-child(5) {
   left: 65%;
   width: 15px;
   height: 15px;
   animation-delay: 0s;
 }

 .circles li:nth-child(6) {
   left: 75%;
   width: 15px;
   height: 15px;
   animation-delay: 3s;
 }

 .circles li:nth-child(7) {
   left: 35%;
   width: 15px;
   height: 15px;
   animation-delay: 7s;
 }

 .circles li:nth-child(8) {
   left: 50%;
   width: 15px;
   height: 15px;
   animation-delay: 15s;
   animation-duration: 45s;
 }

 .circles li:nth-child(9) {
   left: 20%;
   width: 15px;
   height: 15px;
   animation-delay: 2s;
   animation-duration: 35s;
 }

 .circles li:nth-child(10) {
   left: 85%;
   width: 15px;
   height: 15px;
   animation-delay: 0s;
   animation-duration: 11s;
 }

 @keyframes animate {
   0% {
     transform: translateY(0) rotate(0deg);
     opacity: 1;
     border-radius: 100%;
   }

   100% {
     transform: translateY(-1000px) rotate(720deg);
     opacity: 1;
     border-radius: 100%;
   }
 }
</style>