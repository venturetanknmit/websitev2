<template>
    <div class="widthFix mb-4">
    <section class="bg-white ">
        <div class="container px-6 py-2 mx-auto">
            <div class="">
                <div class="p-8 bg-gray-100 rounded-lg text-align: left">
                    <button class="flex items-center text-right justify-between w-full " v-on:click="clicked=!clicked">
                        <h1 class="font-semibold text-left text-gray-700  " >{{question}}</h1>
     
                         <span class="text-gray-400 bg-gray-200 rounded-full">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="blue" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path v-if="!clicked" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"/>
                                <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 12H6" />
                            </svg>
                        </span> 
                    </button>
                    
                  
                    <Transition name="fade">
                        <p v-if="clicked" class="text-gray-500 mt-2 text-sm">
                          {{ answer }}
                        </p>

                        <!-- <p v-if="clicked" class="mt-2 text-sm text-gray-500" :class="clicked? 'hidden':'btnclick'"> -->
                            <!-- passing props for faqs -->
                            <!-- {{answer}} -->
                        <!-- </p> -->
                    </Transition>
                </div>
    
            </div>
        </div>
    </section>
    </div>
</template>

<script>

export default {
    name:"FaqsCode",
    props:{
        question:String,
        answer:String,
    },
    data(){ 
    return {
     clicked:false
    }
    }
}
</script>

<style lang="css" scoped>
/*From tailwind for fade*/
/* .fade-enter-active, */
.fade-enter-active{
@apply transition-all duration-100 ease-in;
}
.fade-leave-active {
  @apply transition-opacity duration-300 ease-out;
}
.fade-leave-active {
  @apply opacity-0;
}
.fade-enter-active {
  @apply opacity-5;
}

/*From tailwind for fade*/
.widthFix{
    width: 56%;
}

.bounce-enter-active {
    animation: bounce-in 0.5s;
}

.bounce-leave-active {
    animation: bounce-in 0.5s reverse;
}

@keyframes bounce-in {
    0% {
        transform: scale(0);
    }

    50% {
        transform: scale(1.25);
    }

    100% {
        transform: scale(1);
    }
}

.btnclick{
    display: block;
    transition: height 2s;
}
@media (max-width: 560px){
    .widthFix{
    width: 88%;
}
}
</style>