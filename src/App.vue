<template>
  <div id="app">
    <toolbar></toolbar>
    <note-list></note-list>
    <!--<editor></editor>-->
  </div>
</template>

<script>
import Toolbar from './components/Toolbar'
import NoteList from './components/NoteList'
import Editor from './components/Editor'

export default {
  name: 'app',
  components: {
    Toolbar,
    NoteList,
    // Editor
  }
}
</script>

<style>
html, #app {
  height: 100%;
  background: url('http://pic.58pic.com/58pic/16/55/86/76H58PIC69p_1024.jpg');
  background-repeat: no-repeat;
  background-size: cover;
}

body {
  margin: 0;
  padding: 0;
  border: 0;
  height: 100%;
  max-height: 100%;
  position: relative;
}
</style>
