<template >
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos dolores dolorem magni itaque, praesentium harum illum pariatur ullam, totam reprehenderit, excepturi omnis aspernatur maxime eligendi corporis obcaecati beatae illo blanditiis.</p>
        <PostButtom/>
    </div>
</template>

<script lang="ts" setup>
import PostButtom from './PostButton.vue'
</script>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>