
<template>
    <div id="app">
        <h1>Ứng dụng blog nhỏ với vue</h1>
        <CreatePost @add-post="addPost"/>
        <PostList :posts="posts" /> 
    </div>
</template>
<script setup>
    import {ref} from "vue";
    import CreatePost from "./components/createPost.vue";
    import PostList from "./components/postList.vue";
    const posts = ref([])
    function addPost(post){
        posts.value.push(post)
    }
</script>