<template>
  <div class="content">
    <TimeRangePicker format="HH"/>
  </div>
</template>

<script>
import { TimeRangePicker } from 'ant-design-vue'
export default {
  name: 'App',
  components: {
    TimeRangePicker
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.content {
  width: 50%;
}
</style>
