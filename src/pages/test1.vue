<script lang='ts' setup>
const value1 = ref('')
</script>

<template>
  <div>init</div>
  <el-button type="primary">
    测试
  </el-button>
  <el-date-picker v-model="value1" type="date" placeholder="Pick a day" />
</template>

<style lang='scss' scoped></style>

<route lang="yaml">
meta:
  layout: admin
  title: 工作台
</route>
