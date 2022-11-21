<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Primeiro projeto em vue!
    </p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: "HelloWord",
  props:{
    msg: String
  }
})
</script>

<style scoped>
h1 {
  color: red;
}
p {
  color: #42b983;
}
</style>
