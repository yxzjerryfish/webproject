<template>
  <div>
    <div class="headavatar">
      <a-avatar shape="square" :size="64" icon="user" />
    </div>
    my-header
    <div class="headdropdown">
      <a-dropdown>
        <a class="ant-dropdown-link" href="#">
          Hover me <a-icon type="down" />
        </a>
        <a-menu slot="overlay">
          <a-menu-item>
            <a href="javascript:;">1st menu item</a>
          </a-menu-item>
          <a-menu-item>
            <a href="javascript:;">2nd menu item</a>
          </a-menu-item>
          <a-menu-item>
            <a href="javascript:;">3rd menu item</a>
          </a-menu-item>
        </a-menu>
      </a-dropdown>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.headavatar {
  float: left;
}
.headdropdown {
  float: right;
}
</style>
