<template>
  <div id="app">
    <!-- 插槽demo -->
    <!-- <slot-demo>
      <template #default>默认插槽赋值</template>
      <br />
      <template #nameslot>name插槽赋值</template>
      <br />
      <template #scope="scopedata">scope插槽{{ scopedata.data }}</template>
    </slot-demo> -->
    <element-demo></element-demo>
  </div>
</template>

<script>
import SlotDemo from './components/slot-demo.vue'
import ElementDemo from './components/elementui-demo.vue'
export default {
  name: 'App',
  components: { SlotDemo, ElementDemo },
}
</script>

<style lang="less"></style>
