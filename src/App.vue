<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template lang="pug">
el-container
  el-header 排班助手
  el-container
    el-aside(width='200px') 
      el-menu.el-menu-vertical-demo(default-active='2', @open='handleOpen', @close='handleClose')
        el-menu-item(index='calendar') 值班表
        el-menu-item(index='user') 人员管理
        el-menu-item(index='rules') 排班规则
    el-main Main
</template>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
