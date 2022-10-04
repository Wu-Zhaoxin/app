<template>
  <div id="app">
    <!-- 根組件 -->
    <!-- 使用組件 -->
    <Header></Header>
    <!-- 路由出口(路由組件展示位置) -->
    <router-view></router-view>
    <Footer></Footer>
  </div>
</template>

<script>
// 引入組件
import Header from './components/Header'
import Footer from './components/Footer'

export default {
  name: 'App',
  // 注冊組件
  components: {
    Header: Header,
    Footer: Footer
  }
}
</script>

<style>
#app {

}
</style>
