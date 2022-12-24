<template>
   
    <div class="card2" v-on:mouseenter="flip2()" v-on:mouseleave="flip2()">
		<div class="card__inner2">
			<div class="card__face2 card__face--front2">
				<img
              src="./logo/2ndprize-removebg-preview.png"
              alt=""
            />
			</div>
            
			<div class="card__face2 card__face--back2">
				<div class="card__content2">
					<div class="card__header2">
						<h2>₹7,000</h2>
					</div>
				</div>
			</div>
		</div>
	</div>

</template>

<script scoped>

export default {
  name: 'FlipCard2',
  methods:{
     flip2(){
    var card2 = document.querySelector(".card__inner2");
    card2.classList.toggle('is-flipped2');

     }
  }
}

</script>  

<style scoped>
:root {
  --primary: #FFCE00;
  --secondary: #FE4880;
  --dark: #212121;
  --light: #F3F3F3;
}
.card2 {
  margin: 100px auto 0;
  width: 240px;
  height: 240px;
  perspective: 1000px;
}

.card__inner2 {
  width: 100%;
  height: 100%;
  transition: transform 1s;
  transform-style: preserve-3d;
  cursor: pointer;
  position: relative;
}

.card__inner2.is-flipped2 {
  transform: rotateY(180deg);
}
 
.card__face2 {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  overflow: hidden;
  border-radius: 16px;
  box-shadow: 0px 0px 4px 2px rgba(0, 0, 0, 0.2);
  /* Change this to see the front of the card's color change */
  background-color:var(--footerBg);
}


.card__face--front2 {
  background-image: linear-gradient(to bottom right, var(--primary), var(--secondary));
  display: flex;
  align-items: center;
  justify-content: center;
}

.card__face--front2 h2 {
  color: rgb(9, 9, 9);
  font-size: 32px;
}

.card__face--back2 {
  background-color: var(--dark);
  transform: rotateY(180deg);
}

.card__content2 {
  width: 100%;
  height: 100%;
}

.card__header2 {
  
  background-color: #C0C0C0;
  padding: 88px 30px;
}

.card__header2:after {
  content: '';
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-image: linear-gradient(to bottom left, var(--primary) 10%, var(--secondary) 115%);
  z-index: -1;
  border-radius: 0px 0px 50% 0px;
}

.pp {
  display: block;
  width: 128px;
  height: 128px;
  margin: 0 auto 30px;
  border-radius: 50%;
  background-color: #FFF;
  border: 5px solid #FFF;
  object-fit: cover;
}

.card__header2 h2 {
  color: rgb(4, 4, 4);
  font-size: 45px;
  font-weight: 900;
  text-transform: uppercase;
  text-align: center;
}





</style> 

