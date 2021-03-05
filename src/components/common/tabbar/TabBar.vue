<template>
  <div id="tab-bar">
     <slot></slot>
  </div>
</template>

<script>
  export default {
    name: "TabBar"
  }
</script>

<style scoped>

    /*css引用加@*/
  @import "~assets/css/base.css";

  #tab-bar {
    display: flex;
    background-color: #f6f6f6;
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    box-shadow: 0px -1px 5px rgba(10,10,10,0.1);
  }


</style>
