<!-- START TEMPLATE -->
<template>
    
    <img :src="props.src" class="profile" alt="profile" tweet=""/>

</template>
<!-- END TEMPLATE -->
<!-- START SCRIPT -->
<script setup>
    import { defineProps } from 'vue';
    
    const props = defineProps(['src']);

</script>
<!-- END SCRIPT -->
<!-- START STYLE -->
<style scoped>
</style>
<!-- END STYLE -->