<template>
    <div id="body-container">
        <BodyOne msg="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eaque totam, reiciendis praesentium et quod, temporibus, a ipsam expedita facilis nisi facere voluptatem. Nulla reiciendis quos fugit corrupti. Nostrum, reprehenderit eos."/>
        <BodyTwo/>
        <BodyThree/>
    </div>
</template>

<script>

import BodyOne from "./BodyOne.vue";
import BodyTwo from "./BodyTwo.vue";
import BodyThree from "./BodyThree.vue";

export default {
    name : 'myBody',
    components:{
        BodyOne,
        BodyTwo,
        BodyThree
    }
    
}
</script>

<style scoped>
    div{
        margin: 25px;
    }

</style>