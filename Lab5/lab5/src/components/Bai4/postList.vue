<template>
    <div class="container">
        <div v-for="(post,index) in posts" :key="index" :class="{'highlighted': post.title.lenght >20}"
            :style="{backgroundColor, color: post.textColor}" class="post">
            <h3 class="text-success">{{ post.title }}</h3>
            <h4 class="text-danger">{{ post.name }}</h4>
            <p>{{ post.content }}</p>

        </div>
    </div>
</template>
<script>
    export default{
        name:"PostList",
        props:{
            posts:{
                type: Array,
                Required: true
            }
        }
    }
</script>