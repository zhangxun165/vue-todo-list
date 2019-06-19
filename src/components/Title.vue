<template>
  <div>
    <p class="title">{{title}}</p>
    <p class="subTitle">{{subTitle}}</p>
  </div>
</template>

<script>
export default {
  // 接受来自父组件的参数
  props: ["title", "subTitle"]
};
</script>

<style scoped>
.title {
  text-align: center;
  color: red;
  font-size: 30px;
}

.subTitle {
  text-align: center;
  color: orange;
  font-size: 15px;
}
</style>
