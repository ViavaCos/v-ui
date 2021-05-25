<template>
  <div class="hello">
    <v-button>按钮</v-button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  components:{
    'v-button': () => import('./button')
  }
}
</script>

<style scoped>

</style>
