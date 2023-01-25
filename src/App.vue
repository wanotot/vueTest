<script>
import Childcomp from './ChildComp.vue'

export default {
  components: {
    Childcomp
  },
  data() {
    return {
      msg: 'who are you???'
    }
  }
}
</script>

<template>
  <ChildComp>Message: {{ msg }}</ChildComp>
</template>