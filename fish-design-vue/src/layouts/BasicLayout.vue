<template>
  <div id="components-layout-demo-basic">
    <a-layout>
      <a-layout-header><Header></Header></a-layout-header>
      <a-layout>
        <a-layout-sider><SideMenu /></a-layout-sider>
        <a-layout-content
          ><MainPageContainer></MainPageContainer
        ></a-layout-content>
      </a-layout>
      <a-layout-footer><Foot /></a-layout-footer>
    </a-layout>
  </div>
</template>

<script>
import Header from "./Header";
import SideMenu from "./SideMenu";
import Foot from "./Foot";
import MainPageContainer from "./MainPageContainer";
export default {
  components: {
    Header,
    SideMenu,
    Foot,
    MainPageContainer
  }
};
</script>

<style>
#components-layout-demo-basic {
  text-align: center;
}
#components-layout-demo-basic .ant-layout-header,
#components-layout-demo-basic .ant-layout-footer {
  background: #7dbcea;
  color: #fff;
  padding-left: 0%;
}
#components-layout-demo-basic .ant-layout-footer {
  line-height: 1.5;
}
#components-layout-demo-basic .ant-layout-sider {
  background: #3ba0e9;
  color: #fff;
  line-height: 700px;
}
#components-layout-demo-basic .ant-layout-content {
  background: rgba(16, 142, 233, 1);
  color: #fff;
  min-height: 700px;
  line-height: 800px;
}
#components-layout-demo-basic > .ant-layout {
  margin-bottom: 48px;
}
#components-layout-demo-basic > .ant-layout:last-child {
  margin: 0;
}
</style>
