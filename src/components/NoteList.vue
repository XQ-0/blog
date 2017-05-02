<template>
  <div id="notes-list">
    <h3>3333333</h3>
  qfffff
  </div>

  </div>
</template>

<script>
export default {
//   data(){
//     return {
//       show:'all'
//     }
//   },
//   computed:{
//     notes(){
//       if (this.show=='all'){
//         return this.$store.getters.notes
//       }else if(this.show=='favorites'){
//         return this.$store.getters.notes.filter(note=>note.favorite)
//       }
//     },
//     activeNote(){
//       return this.$store.getters.activeNote
//     }
//   },
//   methods:{
//     updateActiveNote(note){
//       console.log(note)
//       this.$store.dispatch('updateActiveNote',note)
//     }
//   }
}
</script>
<style type="text/css">
#notes-list {
    width: 50%;
    height: 200px;
    background-color: #F5F5F5;
    margin: 60px auto;
    font-family: 'Raleway', sans-serif;
    font-weight: 400;
    padding: 3px 20px;
    border-radius: 10px;
}

#list-header {
  padding: 5px 25px 25px 25px;
}

#list-header h2 {
  font-weight: 300;
  text-transform: uppercase;
  text-align: center;
  font-size: 22px;
  padding-bottom: 8px;
}

#notes-list .container {
  height: calc(100% - 137px);
  max-height: calc(100% - 137px);
  overflow: auto;
  width: 100%;
  padding: 0;
}

#notes-list .container .list-group-item {
  border: 0;
  border-radius: 0;
}
.list-group-item-heading {
  font-weight: 300;
  font-size: 15px;
}
</style>