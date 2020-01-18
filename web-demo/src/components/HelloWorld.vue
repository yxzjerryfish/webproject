<template>
<el-container>
  <el-header>
    <my-head></my-head>
  </el-header>
  <el-container>
    <el-aside width="250px"><aside-menu /></el-aside>
    <el-container>
      <el-main>Main</el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </el-container>
</el-container>
</template>

<script>
import MyHead from "../components/layout/MyHead"
import AsideMenu from "../components/aside/AsideMenu"

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    MyHead,
    AsideMenu
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
