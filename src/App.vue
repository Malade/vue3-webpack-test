<template>
  <h1>{{ msg }}</h1>
  <HelloWorld />
</template>

<script>
import HelloWorld from '~/components/HelloWorld'

export default {
  components: {
    HelloWorld
  },
  data() {
    return {
      msg: 'Hello Vue!!!'
    }
  }
}
</script>