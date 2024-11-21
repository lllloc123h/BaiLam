<template>
    <div class="container">
        <p class="card-text text-start" >
        {{ Message }}
        </p>
        <a class="btn btn-info d-block"  @click="updateMessage">click me</a>
    </div>
    
    
    
</template>
<script setup>
   import {ref} from 'vue';
    const Message = ref('dữ liệu ban đầu');
    let flag = 0;
    const updateMessage =()=>{
        if(flag===0){
            Message.value='Thông điệp đã được thay đổi';
            flag=1
        }else{
            Message.value='dữ liệu ban đầu';
            flag=0
        }
    }
</script>