<template>
    <div class="header">
        <div class="header-content"><h3>{{msg}}</h3></div>
    </div>
</template>


<script>
export default {
    name:'Header',
    props:{
        msg:String
    }
}
</script>


<style scoped>
    .tweet-container{
        width: 20vw;
        height: 15vh;
        border: solid 1px;
    }
    h3{
        color:red;
    }
</style>