<template>
 <div class="cf" id="myContent">
  <div>
   <HeadingText name="Prizes"/>
  </div>
  <div class="box-cont">
     <div>
      <div class="row">
        <div class="mp16 card">
          <div class="card-header">
            <img
              src="./logo/1stprize-removebg-preview.png"
              alt=""
            />
          </div>
          <div class="card-body">
            <h2>₹10,000</h2>
          </div>
        </div>
     </div>
     </div>
     <div>
      <div class="row">
        <div class="mp16 card">
          <div class="card-header">
            <img
              src="./logo/2ndprize-removebg-preview.png"
              alt=""
            />
          </div>
          <div class="card-body">
            <h2>₹7,000</h2>
          </div>
        </div>
        <div class=" mp16 card">
          <div class="card-header">
            <img
              src="./logo/3rdprize-removebg-preview.png" alt=""/>
          </div>
          <div class="card-body">
            <h2>₹5,000</h2>
          </div>
        </div>
      </div>
     </div> 

 </div>
 </div>
</template>

<script>
import HeadingText from "../HeadingText.vue";

export default {
  name: 'PrizeVue',
  components:{
    HeadingText
  }

}
</script>

<style scoped>
.cf {
  /* width: 95%; */
    /* margin: 40px auto; */
  
}
.row {
  display: flex;
  justify-content: space-evenly;
  flex-flow: wrap;
  /* margin-block-end: 20px; */
}
.card {
  background-color: var(--logoTextInSvg);
  width: 240px;
  /* margin-bottom: 50px; */
  transition: 0.3s;
  border-radius: 16px;
  
}
.card-header {
  text-align: center;
    /* padding: 16px 8px; */
    /* border-radius: 8px; */
}
.card-body {
  text-align: center;
  color: rgb(255, 255, 255);
  font-size: x-large;
  /* border-radius: 5px; */
}

@media screen and (max-width: 1000px) {
  /* .cf {
    width: 80%;
  } */

  .card {
    /* width: 60%; */
  }
}

img {
  /* width: 230px; */
    /* height: 50px; */
    /* border-radius: 10px; */
    /* object-fit: cover; */
}

/* #myVid {
  
  position: fixed; z-index: 1;
  top: 0; left: 0;
  opacity: 0.9;

  width: 100vw; height: 100vh;
  object-fit: cover;
}
#myContent {

  position: absolute; z-index: 2;
  top: 0; width: 0;
 

  width: 99vw; 
}  */

/* h1{
  color: rgb(0, 0, 0);
  padding-left: 30px;
  font-weight: 700;
} */
h2{
  font-weight: 400;
  font-weight: 400;
    margin-top: 0px;
    margin-bottom: 16px;
}
</style>