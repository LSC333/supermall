<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home">
        <img slot="item-icon" src="~assets/img/home/earth-outline.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/home/earth.svg" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <img slot="item-icon" src="~assets/img/category/apps-outline.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/category/apps.svg" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <img slot="item-icon" src="~assets/img/cart/cart-outline.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/cart/cart.svg" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <img slot="item-icon" src="~assets/img/profile/person-outline.svg" alt="">
        <img slot="item-icon-active" src="~assets/img/profile/person.svg" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>

  import TabBar from "components/common/tabbar/TabBar";
  import TabBarItem from "components/common/tabbar/TabBarItem";

  export default {
    name: "MainTarBar",
    components:{
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>
