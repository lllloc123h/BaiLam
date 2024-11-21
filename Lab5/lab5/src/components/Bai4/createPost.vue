<template>
    <div class="container border rounded ">
        <h2>Tạo bài viết mới</h2>
    <div class="container border rounded ">
        <input type="text" v-model="Title" placeholder="Nhập tiêu đề" class="form-control my-3">
        <input type="text" v-model="Name" placeholder="Nhập tên người đăng" class="form-control my-3">
        <textarea v-model="Content" class="form-control my-3"></textarea>
        <button type="button" class="btn btn-primary my-3" @click="submitPost">Đăng bài</button>
    </div>
    </div>
    
</template>
<script setup>
    import {ref} from 'vue'
    const emit = defineEmits(['add-post'])
    const Title =ref('');
    const Name = ref('');
    const Content= ref('');
    function submitPost(){
        if(Title.value && Name.value && Content.value){
            const newPost ={
                title: Title.value,
                name: Name.value,
                content: Content.value
            }
            emit('add-post',newPost)
            Title.value = '';
            Name.value ='';
            Content.value='';
        }
        
    }
</script>