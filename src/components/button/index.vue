<template>
  <div class="v-button" @click="$emit('click')" :style="{ '--color': 'skyblue' }">
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

@color: var(--color);
.v-button {
  border: 1px solid @color;
}
</style>