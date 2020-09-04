<template>
  <div>
    {{ fo }}
    <TestComponent />
  </div>
</template>

<script>
import TestComponent from './test_component.vue'
import * as _ from 'lodash'
import Vue from 'vue'

export default Vue.extend({
  components: {
    TestComponent
  }
    
})
</script>