<template>
<h1 class="card-title">Nhập mùa mà bạn muốn</h1>
<input type="number" v-model.number="month">
<p v-if="month<1 || month>12" class="text-danger">Dui lòng nhập tháng từ 1 đến 12</p>
<p v-else-if="month>=1 && month<=3">Mùa Xuân</p>
<p v-else-if="month>=4 && month<=6">Mùa Hạ</p>
<p v-else-if="month>=7 && month<=9">Mùa Thu</p>
<p v-else-if="month>=10 && month<=12">Mùa Đông</p>
</template>
<script setup>
import { ref } from "vue";
const month =ref(1);
</script>