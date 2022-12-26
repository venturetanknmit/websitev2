<template>
    <div id="sponsors" class="cf mp16">
     <HeadingText name="Sponsors"/>
    </div>
   <div class="box-cont">
     
        
          <div class="">
            <img
              src="./logo/newton.png"
              alt=""
              class="imgfix"
            />
        
        </div>

       
          <div class="">
            <img
              src="./logo/interview_buddy.png"
              alt=""
              class="imgfix"
            />
          </div>
        
    
          <div class="" >
            <img
              src="./logo/Givemycertificate.png"
              alt=""
              class="imgfix"
            />
          </div>
  

          <div class="">
            <img
              src="./logo/taskade-logo.png"
              alt=""
              class="imgfix"
            />
          </div>
  <div class="">
    <img
      src="./logo/interview-cake.png"
      alt="" class="imgfix"
    />
  </div>

  <div class="">
    <img
      src="./logo/wolfram.png"
      alt=""
      class="imgfix"
    />
  </div>

  <div class="">
    <img
      src="./logo/AoPS.png"
      alt=""
      class="imgfix"
    />
  </div>
</div>
</template>

<script>
import HeadingText from '../HeadingText.vue';

export default {
    name: "SponserSec",
    components: { HeadingText }
}
</script>

<style scoped>
.box-cont{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap:wrap; 
}
.imgfix{
    height: 72px;
    width:240px;
    object-fit: contain;
    padding: 8px;
    margin: 8px;
}


/* Responsive media queries */

@media screen and (max-width: 1000px) {
  .card {
    width: 50%;
  }
  .container {
    width: 70%;
  }
}
@media screen and (max-width: 543spx) {
  .card {
    width: 40%;
  }
  .container {
    width: 90%;
  }
}

@media screen and (max-width: 600px) {
  .container {
    width: 80%;
  }

  .card {
    width: 60%;
  }
}

</style>