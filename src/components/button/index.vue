<template>
  <div class="v-button" @click="$emit('click')">
      <slot></slot>
  </div>
</template>

<script>
export default {
    name: 'v-button',
    props: {
        
    },
    methods:{

    }
}
</script>

<style lang="less" scoped>
@import './index.less';
</style>