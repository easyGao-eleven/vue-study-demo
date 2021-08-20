<template>
  <div>
    <button :disabled="disabled">click me</button>
  </div>
</template>

<script>
export default {
  name: 'MButton',
  // 是否继承标签上定义的其他html属性，默认值为false
  inheritAttrs: false,
  props: {
    disabled: {
      type: Boolean,
      default: false
    }
  },
  methods: {
    test() {
      console.log(123)
    }
  }
}
</script>

<style>
</style>
