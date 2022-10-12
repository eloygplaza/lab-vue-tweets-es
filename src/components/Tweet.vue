<template>
    <div class="tweet">

        <ProfileImage :src="props.tweet.user.image"></ProfileImage>

        <div class="body">
            <div class="top">
                <User :username="props.tweet.user.name" :handle="props.tweet.user.handle"></User>
                <Timestamp :timestamp="props.tweet.timestamp"></Timestamp>
            </div>

            <Message :text="props.tweet.message"></Message>

            <Actions></Actions>
        </div>

        <i class="fas fa-ellipsis-h"></i>
    </div>
</template>

<script setup>
    import { defineProps } from 'vue';
    import ProfileImage from './ProfileImage.vue';
    import User from './User.vue';
    import Timestamp from './Timestamp.vue';
    import Message from './Message.vue';
    import Actions from './Actions.vue';

    const props = defineProps(['tweet']);
    
</script>

<style scoped>
a {
    color: #42b983;
}
</style>