<template>
  <div id="toolbar">
    <i  class="glyphicon glyphicon-plus"></i>
    <i  class="glyphicon glyphicon-star"></i>
    <i  class="glyphicon glyphicon-remove"></i>
  </div>
</template>


<script>
export default {
  name: 'toolbar',
  data () {
    return {
      // msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#toolbar {
  /*float: left;*/
  width: 100%;
  height: 60px;
  /*background-color: #30414D;*/
  color: 'black';
  position: fixed;
  top:0;
  text-align: right;
  line-height: 60px;
  padding: 20px 50px;
  
}
#toolbar i {
  font-size: 30px;
  cursor: pointer;
  /*opacity: 0.6;*/
  opacity: 1;
  /*transition: opacity 0.5s ease;*/
  margin-right: 10px
}

/*#toolbar i:hover {
  opacity: 1;
}
.starred {
  color: #F7AE4F;
}*/
</style>
