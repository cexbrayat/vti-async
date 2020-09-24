<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Suspense>
    <HelloWorld :user="user" />
  </Suspense>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import { UserModel } from './models/user.model'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  },
  setup() {
    return { user: { name: 'Cédric' } };
  }
})
</script>
