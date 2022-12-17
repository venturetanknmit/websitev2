<template>
    <div class="heading">
       <h1>Our Sponsers</h1>
    </div>
   <div class="box-cont">
     <div>
      <div class="row">
        <div class="card">
          <div class="card-header">
            <img
              src="./logo/newton.png"
              alt=""
            />
          </div>
        </div>

        <div class="card">
          <div class="card-header">
            <img
              src="./logo/interview_buddy.png"
              alt=""
            />
          </div>
        </div>
        <div class="card">
          <div class="card-header">
            <img
              src="./logo/Givemycertificate.png"
              alt=""
            />
          </div>
        </div>
       
    </div>
    
    <div class="row">

        

        <div class="card">
          <div class="card-header">
            <img
              src="./logo/taskade-logo.png"
              alt=""
            />
          </div>
        </div>  
    

<div class="card">
  <div class="card-header">
    <img
      src="./logo/interview-cake.png"
      alt=""
    />
  </div>
</div>

<div class="card">
  <div class="card-header">
    <img
      src="./logo/wolfram.png"
      alt=""
    />
  </div>
</div>  
</div>
</div>
</div>
</template>

<script>
export default {
    name: 'SponserSec',
}
</script>

<style scoped>
.box-cont{
  width: 95%;
    margin: 40px auto;
    
}
.row {
  display: flex;
  justify-content: space-evenly;
  flex-flow: wrap;

}
.card {
  width: 20%;
  margin-bottom: 50px;
  transition: 0.3s;
  border-radius: 20px;
  
}
.card-header {
  text-align: center;
    padding: 30px 5px;
    border-radius: 20px
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

img {
  width: 230px;
    height: 50px;
    border-radius: 10px;
}
</style>