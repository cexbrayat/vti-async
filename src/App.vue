<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Suspense>
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
  </Suspense>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
