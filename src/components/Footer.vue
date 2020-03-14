<template>
  <div id="footer-container">
    <h3 id="footer"><p>This is the footer</p></h3>
  </div>
</template>

<script>
export default {
  name: "myFooter"
};
</script>


<style scoped>
    #footer-container{
        background-color:blue;
        width:100vw;
        position: fixed;
        bottom:0;
        text-align: center;
        border: solid 1px;
    }
    p{
        color:red;
    }
</style>
