<script>
import Childcomp from './ChildComp.vue'

export default {
  components: {
    Childcomp
  },
  data() {
    return {
      msg: 'from parent'
    }
  }
}
</script>

<template>
  <ChildComp>Message: {{ msg }}</ChildComp>
</template>