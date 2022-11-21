<template>
    <div>
        <p> Esse é o meu primeiro componente em Vue</p>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: "TestFirstComponent"
});

</script>

<style scoped>
 div {
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>