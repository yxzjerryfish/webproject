<template>
  <div class="my-header">
    <el-row>
      <el-col :span="24">
          1234
        <!-- Logo 显示-->
        <Logo />
        <!--一级主菜单区域-->
        <MainMenu >123</MainMenu>
        <!-- 右侧工具栏（包含用户登录信息） -->
        <Tools />
      </el-col>
    </el-row>
  </div>
</template>

<script>
import Logo from "@/components/layout/header/Logo.vue";
import MainMenu from "@/components/layout/header/MainMenu.vue";
import Tools from "@/components/layout/header/Tools.vue";

export default {
  name: "MyHead",
  components: {
    Logo,
    MainMenu,
    Tools
  }
};
</script>

<style scoped>
.my-header {
  height: 60px;
  width: 100%;
  text-align: left;
  padding: 0px;
  line-height: 60px;
  background-color: rgb(84, 92, 100);
  color: #ffffff;
}
</style>