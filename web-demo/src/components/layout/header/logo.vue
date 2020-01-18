<template>
  <div class="head-logo" >
            <img src="/favicon.ico" class="round_icon"  alt="" @click="hello()">
      </div>
</template>

<script>
export default {
  name: "Logo",
  methods: {
      hello() {
          alert('hello')
      }
  },
};
</script>

<style scoped>
.head-logo {
  float: left;
  padding-left: 18px;
}
.head-logo .round_icon{
  width: 34px;
  height: 34px;
  display: flex;
  border-radius: 50%;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin-top: 15px
}
</style>