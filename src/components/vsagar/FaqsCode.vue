<template>
    <div class="widthFix">
    <section class="bg-white ">
        <div class="container px-6 py-2 mx-auto">
            <div class="">
                <div class="p-8 bg-gray-100 rounded-lg text-align: left">
                    <button class="flex items-center text-right justify-between w-full " v-on:click="clicked=!clicked">
                        <h1 class="font-semibold text-left text-gray-700  " >{{question}}</h1>
     
                        <!-- <span class="text-gray-400 bg-gray-200 rounded-full">
                            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="blue" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="dminus"/>
                            </svg>
                        </span> -->   
                    </button>
    
                    <p class="mt-2 text-sm text-gray-500" :class="clicked? 'hidden':'block'">
                        <!-- passing props for faqs -->
                        {{answer}}
                    </p>
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
    }
}
</script>

<style lang="css" scoped>
.widthFix{
    width: 56%;
}
@media (max-width: 560px){
    .widthFix{
    width: 88%;
}
}

</style>