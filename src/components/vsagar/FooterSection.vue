<template>
  
  
    <svg class="svgWave" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#0f172a" class="waveAnim" fill-opacity="1" d="M0,256L34.3,224C68.6,192,137,128,206,101.3C274.3,75,343,85,411,117.3C480,149,549,203,617,213.3C685.7,224,754,192,823,170.7C891.4,149,960,139,1029,160C1097.1,181,1166,235,1234,218.7C1302.9,203,1371,117,1406,74.7L1440,32L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z"></path></svg>
  <footer id="contactus" class="">
    <!-- Linking  -->
    <!-- <div class="context"> -->

      <div class="flex sm:space-x-4 flex-col bg-slate-900 text-white  items-center space-y-4  pb-4
      lg:flex-row space-x-4 justify-between pl-8 pr-8">
    
    <div>
      <h1 class="text-xl text-center mt-8 md:mt-5">CONTACT US</h1>
      <div class="mt-4 flex flex-col space-y-2 text-slate-400 text-sm items-center">
        
        <a href="tel: +91 7676426879">
          <h1>PHONE : 7676426879</h1>
        </a>

        <a href="mailto:venturetank@gmail.com">
          <h1> EMAIL : venturetanknmit@gmail.com </h1>
        </a>
      </div>
    </div>

    <div>
    
    <!-- <h1 class="text-xl text-center ">MENU</h1> -->
    <!-- <div class="flex flex-col pt-5 text-center space-y-4 text-slate-400 text-sm md:flex-row lg:space-x-4 justify-center align-center items-center md:space-y-0 "> -->

    <div class="m-4 flex flex-col text-slate-400 text-sm md:flex-row justify-items-center align-middle lg:mr-10">
      <a class="m-2" href="#">HOME</a>
      <a class="m-2" href="#about">ABOUT US</a>                                  
      <a class="m-2" href="#timeline">TIMELINE</a>
      <a class="m-2" href="#prizes">PRIZES</a>
      <a class="m-2" href="#faqs">FAQs</a>

    </div>
    </div>
    

    <div class="">
      <h1 class="text-xl">CONNECT WITH US</h1>
      <div class="flex mt-4 space-x-0">
        <a target="_blank" href="https://www.instagram.com/venture_tank/">
          <img src="../../assets/icons/iconInstagram.svg" alt="instagram" class="hver h-12 w-20 mx-0" />
        </a>
        <a target="_blank" href="https://linkedin.com/company/venture-tank/">
          <img src="../../assets/icons/iconLinkedin.svg" alt="linkedin" class="h-12 w-20" />
        </a>
      </div>
    </div>

   </div>
   
   <div class="bg-slate-900 text-white text-xs flex flex-row justify-center pb-3 lg:pl-9">
     <h1>MADE WITH ❤️ BY TEAM VENTURE TANK</h1>
    </div>
  <!-- </div> -->
    </footer>

  

    <!-- ----------------------------------------------- -->
    <!-- <div>
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
  </div> -->

</template>

<script>



export default {

  name: "FooterSection",
  components: {

  }
}
</script>

<style scoped>
.svgWave{
  margin-bottom: -2px;
}
@media (min-width:720px){
  .svgWave{
    display: none;
  }
}
.waveAnim{
animation: keyWaveAnim 16s infinite linear;
}
@keyframes keyWaveAnim{
  
  0% {
  d:path("M0,256L34.3,224C68.6,192,137,128,206,101.3C274.3,75,343,85,411,117.3C480,149,549,203,617,213.3C685.7,224,754,192,823,170.7C891.4,149,960,139,1029,160C1097.1,181,1166,235,1234,218.7C1302.9,203,1371,117,1406,74.7L1440,32L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z")
    }
  
  40% {
  d:path("M0,64L34.3,64C68.6,64,137,64,206,74.7C274.3,85,343,107,411,133.3C480,160,549,192,617,218.7C685.7,245,754,267,823,240C891.4,213,960,139,1029,117.3C1097.1,96,1166,128,1234,154.7C1302.9,181,1371,203,1406,213.3L1440,224L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z")
    }
    
    60%{
      d:path("M0,128L34.3,112C68.6,96,137,64,206,74.7C274.3,85,343,139,411,144C480,149,549,107,617,96C685.7,85,754,107,823,133.3C891.4,160,960,192,1029,197.3C1097.1,203,1166,181,1234,170.7C1302.9,160,1371,160,1406,160L1440,160L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z")  
    }
    80% {
    d:path("M0,64L34.3,64C68.6,64,137,64,206,74.7C274.3,85,343,107,411,133.3C480,160,549,192,617,218.7C685.7,245,754,267,823,240C891.4,213,960,139,1029,117.3C1097.1,96,1166,128,1234,154.7C1302.9,181,1371,203,1406,213.3L1440,224L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z")
      }

  100% {
  d:path("M0,256L34.3,224C68.6,192,137,128,206,101.3C274.3,75,343,85,411,117.3C480,149,549,203,617,213.3C685.7,224,754,192,823,170.7C891.4,149,960,139,1029,160C1097.1,181,1166,235,1234,218.7C1302.9,203,1371,117,1406,74.7L1440,32L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z")
    }
}
/* For margins between footer and faqs */
.mpFix{
  margin-top: 64px;
}
 a:hover{
  /* background-color: aqua; */
  color: #fff;
 }

/*******************************************************/
/* .circles {
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
 } */
</style>