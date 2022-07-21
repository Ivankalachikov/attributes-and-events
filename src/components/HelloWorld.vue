<template>
  <div class="hello">
    <h1>Attributes and events</h1>
    <WrapperComponent :rows="10" :cols="40"/>
  </div>
</template>

<script>
import WrapperComponent from './WrapperComponent'

export default {
  components: { 
    WrapperComponent
  },
  name: 'HelloWorld',
}
</script>

<style scoped>

</style>
