<template>
  <div :class="[{'header':true}, theme, {'radius-md':true}]">
    <slot></slot>
  </div>
</template>

<script>
// import axios from 'axios'

export default {
  name: "header",
  data(){
    return {
      theme:""
    }
  },
  methods:{
  },
  mounted(){
    this.theme = global_theme;
  }
}
</script>
<style media="screen">
  .header{
    color: white;
    top: 0px;
    position: fixed;
    margin: 0px;
    box-shadow: 0px 0 8px rgba(100, 100, 100, 0.2);
    height: 13%;
    padding-left: 20px;
    width: 100%;
    padding-top: 6%;
    font-size: 1.6em;
    z-index: 3;
  }
  .header .icon{
    width: 100%;
    position: fixed;
    float: top;
    left: 0px;
  }
  .header .icon *{
    /* align-content: right; */
    /* margin-right: 0; */
    position: relative;
    display: block;
    margin-right: 15px;
    margin-top: 5px;
    float: right;
    vertical-align: top;
    /* right: 0px; */
    /* margin-right: 0px; */
    color: #ffffff;
    z-index: 4;
    /* position: fixed; */
    /* right: 0; */
  }
</style>
