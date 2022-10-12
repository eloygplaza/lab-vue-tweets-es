<!-- START TEMPLATE -->
<template>

    <span class="timestamp">{{props.timestamp}}</span>

</template>
<!-- END TEMPLATE -->
<!-- START SCRIPT -->
<script setup>
    import { defineProps } from 'vue';

    const props = defineProps(['timestamp']);
</script>
<!-- END SCRIPT -->
<!-- START STYLE -->
<style scoped>
</style>
<!-- END STYLE -->