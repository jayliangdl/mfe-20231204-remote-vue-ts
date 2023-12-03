<template>
  <div class="{{CONTAINER}}">
    <MyVueButton />
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue'
  import MyVueButton from './MyVueButton.vue';
  export default defineComponent({
    components:{
      MyVueButton
    }
  });
</script>
