<template>
    <div class="container border rounded">
        <h1 class="text-title">Thông tin cá nhân</h1>
        <div class="container">
            <label for="" class="form-label">Họ và tên:</label><br>
            <input type="text" v-model="userInfo.fullName" placeholder="Nhập họ và tên" class="form-control"><br>
            <label for="" class="form-label">Tuổi của bạn:</label><br>
            <input type="number" min="0" v-model="userInfo.Age" placeholder="Nhập tuổi" class="form-control"><br>
            <label for="" class="form-label">Nhập Email:</label><br>
            <input type="Email" v-model="userInfo.Email" placeholder="Nhập Email" class="form-control"><br>
        </div>
        <div class="container bg-dark text-white border rounded m-2">
            <h2>Thông tin đăng nhập</h2>
            <p class="card-text m-3">
            Tên của bạn là:   {{ userInfo.fullName }} <br>
            Tuổi {{ userInfo.Age }} <br>
            Email: {{ userInfo.Email }}
            </p>
        </div>
    </div>
</template>
<script setup>
    import {reactive} from 'vue'
    const userInfo = reactive({
        fullName:'',
        Age: null,
        Email:''
    })
</script>