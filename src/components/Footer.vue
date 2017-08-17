<template>
  <tabbar>
    <tabbar-item>
      <img slot="icon" src="../assets/message.png">
      <span slot="label">我的消息</span>
    </tabbar-item>
    <tabbar-item>
      <img slot="icon" src="../assets/home.png">
      <span slot="label">首页</span>
    </tabbar-item>
    <tabbar-item>
      <img slot="icon" src="../assets/cart.png">
      <span slot="label">购物车</span>
    </tabbar-item>
  </tabbar>
</template>

<script>
import { Tab, TabItem } from 'vux'
    export default{
       name: 'm-footer',
       components: {
         Tabbar,
         TabbarItem,
       },
       data(){
         return{
            msg:''
         }
       },

    }
</script>
<style>

</style>