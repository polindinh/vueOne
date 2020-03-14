<template>
    <div class="header">
        <div class="header-content"><h3>{{msg}}</h3></div>
    </div>
</template>


<script>
export default {
    name:'myHeader',
    props:{
        msg:String
    },
   
};
</script>


<style scoped>
    .header{
        width: 100vw;
        border: solid 1px;
    }
    h3{
        color:red;
    }
</style>