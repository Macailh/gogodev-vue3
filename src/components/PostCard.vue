<template>
<div class="post-card">
    <h3>Title</h3>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quia veniam labore nisi? Iste fugit porro harum necessitatibus molestiae pariatur, id impedit et reiciendis magni aspernatur consequuntur consectetur provident, modi voluptatem.</p>
    <PostButton />
</div>
</template>

<script setup>
import PostButton from './PostButton.vue'
</script>

<style scoped>
.post-card {
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>