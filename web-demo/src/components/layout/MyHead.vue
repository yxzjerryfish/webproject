<template>
  <div class="my-header">
    <el-row>
      <el-col :span="24">
        <!-- Logo 显示-->
        <Logo />
        <!-- 右侧工具栏（包含用户登录信息） -->
        <Tools />
        <div class="head-font">
            这是主要显示内容
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import Logo from "@/components/layout/header/Logo.vue";
import Tools from "@/components/layout/header/Tools.vue";

export default {
  name: "MyHead",
  components: {
    Logo,
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
.my-header .head-font{
    width: 50%;
    text-align:center
}
</style>