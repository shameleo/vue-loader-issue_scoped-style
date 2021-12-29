<template>
    <div>Powered by...</div>
    <div>...Vue {{ ver }}!</div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        data: () => ({
            ver: 3
        })
    });
</script>

<style scoped>
    .whatever {}
</style>