<template>
   <div class=" main cf">
    <div class="rf w64">

      <div class="picWrapper">
        <img class="pic mp8" src="./aboutusBg.jpg" alt="Loading...">
      </div>

    <!-- <div class=""> -->
      <div class="content mp8">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate deleniti qui, modi exercitationem alias, ratione vel aperiam maiores mollitia aut officiis cupiditate hic. Ex consequuntur laborum optio odit molestiae enim?
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laudantium praesentium ea consequatur magnam cum illo eum voluptatem omnis, corporis ad assumenda aliquam cupiditate earum saepe dicta est perferendis vitae quasi.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. In, quo officia unde atque eos similique at repudiandae temporibus esse necessitatibus quia quod? Minus fugiat iusto nobis ratione obcaecati. Temporibus, corporis?
      </div>
    <!-- </div> -->
    </div>
   </div>
</template>

<script>
  
export default {
  name: 'AboutusVue'
}

</script>


<style scoped>
.w64{
  width: 80%;
}
.pic{
  width: 40vw !important;
  }

  @media (max-width: 720px){
  .pic{
    display: none;
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