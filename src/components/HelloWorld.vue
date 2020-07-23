<template>
  <div>{{ users }}</div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'App',

  async setup() {
    const users = ref<Array<string>>(await Promise.resolve(['Cédric']));
    return { users };
  }
});
</script>