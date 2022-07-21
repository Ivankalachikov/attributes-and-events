<template>
  <div class="wrapper-component">
    <TargetComponent v-bind="$attrs"/>
  </div>
</template>

<script>
import TargetComponent from './TargetComponent'

export default {
  components: { 
    TargetComponent
  },
  inheritAttrs: false,
  // props: {
  //   cols: {
  //     type: String,
  //   }
  // },
  name: 'WrapperComponent',
}
</script>
