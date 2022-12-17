<template>

<div id="prizes" class="cf">
  <HeadingText name="Prizes"/>
</div>
  <div class="contain">
   <FlipCard1/>
   <FlipCard2/>
   <FlipCard3/>
</div>
  
        
      
</template>
    
    
<script scoped>
import HeadingText from "../HeadingText.vue";
import FlipCard1 from "./flipping1.vue"   
import FlipCard2 from "./flipping2.vue" 
import FlipCard3 from "./flipping3.vue"       

export default {
  name: 'FlipMain',
  components: {
    FlipCard1,
    FlipCard2,
    FlipCard3,
    HeadingText
}
}
</script>
    

<style scoped>
    
    .contain{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    /* flex-flow: wrap; */
    }

</style>
    