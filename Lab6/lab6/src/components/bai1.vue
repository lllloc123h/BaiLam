<template>
    <h1 class="card-title">Nhập điểm của bạn</h1>
    <input type="number" v-model="Score" min="0" max="10" >
    <p v-if="Score>=9">xuất sắc</p>
    <p v-else-if="Score>=8">giỏi</p>
    <p v-else-if="Score>=6.5">Khá</p>
    <p v-else-if="Score>=5">Trung bình</p>
    <p v-else>yếu</p>
</template>
<script setup>
    import { ref } from "vue";
    const Score = ref(0)
        
</script>