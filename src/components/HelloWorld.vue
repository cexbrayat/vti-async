<template>
  <div>{{ user.name }}</div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';
import { UserModel } from '../models/user.model';

export default defineComponent({
  name: 'HelloWorld',
  props: {
    user: {
      type: Object as PropType<UserModel>
    }
  }
});
</script>