<template>
  <div id="about" class="cf mp8">
    <HeadingText name="About"/>
    <div class="rf mp8 ">
      <div class="">
        <!-- <img class="mp8"  src="./aboutusBg.png" alt=""> -->
    </div>

    <div class="mp8 w64">
      Venture Tank is an initiative taken from the Computer Science Department to bring out ideas and real life implementation of ideas that students have. It is a multi-disciplinary event. All branches are invited to participate and show case their ideas and talents. They can turn their ideas into start-ups.
</div>
</div>
</div>
</template>

<script>
import HeadingText from '../HeadingText.vue';

  
export default {
    name: "AboutusVue",
    components: { HeadingText }
}

</script>


<style scoped>
.pic{
  width: 300px !important;
}
.w64{
  width: 64%;
}
.h88{
  height: 88vh;
}
  @media (max-width: 720px){
  .pic{
    display: none;
  }
  .w64{
    width: 88%;
  }
}
/* .picWrapper{
  width: 32%;
}




  .info{
    padding: 10px;
  }
}

  .main {
    background-color: #82C3EC;
  }

  

  .row{
    display: flex;
    align-items: center;
    padding-bottom: 5px;
  }

  .info {
      margin-right : 10px;
  } */

</style>