<template>
    <div class="x-button">
        <div>我是一个大大的按钮</div>
    </div>
</template>
<script>
export default {
  name: 'x-button',
  props: {
    type: String
  }
}
</script>
<style scoped>
    .x-button {
      display: inline-block;
      padding: 3px 6px;
      background: green;
      color: #fff;
    }
</style>