<script>
import ipcRenderer from Electron
export default {
  methods:{
    close(){
      ipcRenderer( )
    }
  }
}
</script>
<template>
  <div id="menu">
    <div class="left">玄冰是仓鼠</div>
    <div class="centre">搜索框</div>
    <div class="right">
      <div id="min" @click="min">
        <i class="fa fa-window-minimize"></i>
      </div>
      <div id="max" @click="max">
        <i class="fa fa-window-restore"></i>
      </div>
      <div id="close" @click="close">
        <i class="fa fa-window-close-o"></i>
      </div>
    </div>
  </div>
</template>



<style>
@import './menu.css';
</style>
