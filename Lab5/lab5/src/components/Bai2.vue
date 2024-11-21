<template>

        <input type="text" class="my-2" v-model="userInput" placeholder="Nhập dữ liệu vào đây"><br >

    
    <p>
       Giá trị bạn nhập là: {{ userInput }}
    </p>
</template>
<script setup>
    import {ref} from'vue';
    const userInput =ref('');


</script>