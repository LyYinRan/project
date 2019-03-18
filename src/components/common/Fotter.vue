<template>
    <div>
        <mt-tabbar v-model="selected">
        <mt-tab-item id="home">
          <img slot="icon" src="../../assets/logo.png">
          外卖
        </mt-tab-item>
        <mt-tab-item id="member">
          <img slot="icon" src="../../assets/logo.png">
          订单
        </mt-tab-item>
        <mt-tab-item id="search">
         <img slot="icon" src="../../assets/logo.png">
          发现
        </mt-tab-item>
        <mt-tab-item id="shopcart">
          <img slot="icon" src="../../assets/logo.png">
          我的
        </mt-tab-item>
       </mt-tabbar>
    </div>
</template>

<script>
export default {
    data () {
      return {
        selected : 'home'
      }
  },
  watch : {
    selected(newValue, oldValue){
      console.log(newValue,oldValue)
       this.$router.push({name : this.selected})
    }
  }
}
</script>

<style>

</style>


