<template>
    <div class="about">
        <h1>This is an about page</h1>
        <HelloWorld></HelloWorld>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue";
export default defineComponent({
    components: { HelloWorld },
});
</script>
