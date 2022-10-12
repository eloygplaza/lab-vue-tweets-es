<!-- START TEMPLATE -->
<template>

    <p class="message">
        {{props.text}}
    </p>

</template>
<!-- END TEMPLATE -->
<!-- START SCRIPT -->
<script setup>
    import { defineProps } from 'vue';

    const props = defineProps(['text']);
</script>
<!-- END SCRIPT -->
<!-- START STYLE -->
<style scoped>
</style>
<!-- END STYLE -->