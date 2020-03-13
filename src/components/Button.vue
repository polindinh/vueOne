<template>
    <div id="change-color">
        <button v-on:click="changeColor">Click to change Background color</button>
    </div>
</template>

<script>
export default {
    name: 'Button',
    methods: {
        changeColor: function(){
            function randomColor(){
                let index = Math.floor(Math.random()*3);
                let colors = ['red','green','blue'];
                return colors[index];
            }
            setInterval(function(){
                document.getElementById('change-color').style.backgroundColor =randomColor();

            },100);
        }
  }  

};


</script>