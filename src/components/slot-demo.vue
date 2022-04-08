<template>
  <div>
    <slot>默认插槽</slot>
    <slot name="nameslot">name插槽</slot>
    <slot name="scope" data="data">作用域插槽</slot>
  </div>
</template>

<script>
export default {
  name: 'slotname',
  data() {
    return {}
  },
}
</script>
<style lang="scss" scoped></style>
