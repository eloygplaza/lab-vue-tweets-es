<!-- START TEMPLATE -->
<template>
    <span class="user">
        <span class="name">{{props.username}}</span>
        <span class="handle">{{props.handle}}</span>
    </span>

</template>
<!-- END TEMPLATE -->
<!-- START SCRIPT -->
<script setup>

    const props = defineProps(['username','handle']);
    
</script>
<!-- END SCRIPT -->
<!-- START STYLE -->
<style scoped>
</style>
<!-- END STYLE -->