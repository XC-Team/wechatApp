<template>
    <div>个人信息中心</div>
</template>
<script>
export default {
  async created() {
    console.log("小程序启动了");
  }
};
</script>
<style>
.text-footer {
  text-align: center;
  font-size: 0.75rem;
  margin-bottom: 0.3125rem;
}
.text-primary {
  color: #ea5149;
}
.btn {
  color: white;
  background: #ea5149;
  margin-bottom: 0.625rem;
  padding-left: 0.9375rem;
  border-radius: 0.125rem;
  font-size: 1rem;
  line-height: 2.5rem;
  height: 2.5rem;
  width: 100%;
}
.btn:active {
  background: #fa5a49;
}
</style>
