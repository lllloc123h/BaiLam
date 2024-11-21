<template>
    <div id="app" class="container">
        <h1>Ứng dụng blog nhỏ với vue</h1>
        <div>
            <CreatePost @add-post="addPost"/>
            <PostList :posts="posts" /> 
        </div>
        
    </div>
</template>
<script setup>
    import {ref} from "vue";
    import CreatePost from "./components/Bai4/createPost.vue";
    import PostList from "./components/Bai4/postList.vue";
    const posts = ref([])
    function addPost(post){
        posts.value.push(post)
    }
</script>