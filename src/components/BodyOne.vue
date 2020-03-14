<template>
    <div id="body-one" v-on:click="mouseclick"
    v-on:mouseleave="mouseleave">
        <!-- <p v-on:mouseover="mouseover"
    v-on:mouseleave="mouseleave">{{msg}}</p> -->
 
    <p>{{msg}}</p>
    <p>{{msg}}</p>
    <p>{{msg}}</p>
    <p>{{msg}}</p>
    <p>{{msg}}</p>
    <p>{{msg}}</p>

    
    </div>
</template>

<script>
export default {
    name:'BodyOne',
    props:{
        msg:String
    },
    methods:{
        mouseclick: function(){
            this.msg = "Who told you to click me! Now move out of the box so can can get back to what i was showing before"
        },
        mouseleave: function(){
            this.msg="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eaque totam, reiciendis praesentium et quod, temporibus, a ipsam expedita facilis nisi facere voluptatem. Nulla reiciendis quos fugit corrupti. Nostrum, reprehenderit eos."
        }

    }
};
</script>



<style scoped>
    #body-one{
        border:solid 1px;
        box-shadow: 2px 2px 3px 4px #ff26ff;
    }
</style>

