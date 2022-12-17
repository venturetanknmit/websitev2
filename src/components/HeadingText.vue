<template>

    <h2 class="txt"> {{name}} </h2>

</template>

<script>
    export default {
        name: "HeadingText",
        props:{
            name:String
        }
    }
</script>

<style scoped>
.txt{
    
    font-size: 64px;
    background: linear-gradient(180deg, #2491D2 10.39%, rgba(0, 0, 0, 0.34) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-fill-color: transparent;
}


</style>