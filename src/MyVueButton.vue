<template>
  <div>
    <div>Provided by RemoteVueTs Project - {MyVueButton.vue}</div>
    <p>{{ num }}</p>
    <button @click="increment">click me!!</button>
  </div>
</template>

<script lang="ts">
import { ref } from 'vue';

export default {
  name: 'MyVueButton',
  setup() {
    const num = ref(0);

    const increment = () => {
      console.log('increment');
      num.value += 2;
    };

    return { num, increment };
  }
};
</script>

<style>

</style>
