<template>
    <div class="container">
        <div class="row">
            <div class="col-sm-4 border rounded ms-4">
                <div class="container">
                    <form @submit.prevent="submitForm">
                        <h3>Thêm học sinh</h3>
                        <div class="mb-3 mt-3">
                            <label for="name" class="form-label">Họ và tên:</label>
                            <input type="text" class="form-control" v-model="student.name" id="name" required />
                        </div>
                        <div class="mb-3">
                            <label for="score" class="form-label">Điểm:</label>
                            <input type="number" max="10" min="0" class="form-control" v-model="student.score" id="score" required />
                        </div>
                        <div class="mb-3">
                            <label for="dob" class="form-label">Ngày sinh:</label>
                            <input type="date" class="form-control" v-model="student.dob" id="dob" required />
                        </div>
                        <button type="submit" class="btn btn-success">{{ isEditing ? 'Cập nhật' : 'Thêm' }}</button>
                        <button type="button" @click="resetForm" class="btn btn-danger ms-5">Làm mới</button>
                    </form>
                </div>
            </div>
            <div class="col-sm-7 border rounded ms-5">
                <div class="container">
                    <h3>Danh sách học sinh</h3>
                    <table class="table table-hover">
                        <thead>
                            <tr>
                                <th>Họ và tên</th>
                                <th>Điểm</th>
                                <th>Ngày sinh</th>
                                <th></th>
                                <th></th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr v-for="(st, index) in listStudent" :key="index">
                                <td>{{ st.name }}</td>
                                <td>{{ st.score }}</td>
                                <td>{{ st.dob }}</td>
                                <td><button @click="editStudent(index)" class="btn btn-warning">Sửa</button></td>
                                <td><button @click="deleteStudent(index)" class="btn btn-danger">Xóa</button></td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ref, reactive } from "vue";

// Danh sách học sinh
const listStudent = reactive([
    { name: 'Bùi Hữu Lộc', score: 10, dob: '2024-11-24' },
    { name: 'Lê Đinh Phúc Hậu', score: 9, dob: '2024-11-24' },
]);

// Dữ liệu học sinh hiện tại
const student = ref({
    name: '',
    score: null,
    dob: '',
});


let isEditing = ref(false);
let editingIndex = ref(null);


function submitForm() {
    if (isEditing.value) {
        listStudent[editingIndex.value] = { ...student.value };
        isEditing.value = false;
        editingIndex.value = null;
    } else {
        listStudent.push({ ...student.value });
    }


}

// Hàm chỉnh sửa học sinh
function editStudent(index) {
    student.value.name = listStudent[index].name;
    student.value.score = listStudent[index].score;
    student.value.dob = listStudent[index].dob;
    isEditing.value = true;
    editingIndex.value = index;
}

// Hàm xóa học sinh
function deleteStudent(index) {
    listStudent.splice(index, 1);
}

// Hàm làm mới form
function resetForm() {
    student.value.name = '';
    student.value.score = null;
    student.value.dob = '';
    isEditing.value = false; // Đảm bảo không ở chế độ chỉnh sửa
    editingIndex.value = null; // Đặt lại chỉ số chỉnh sửa
}
</script>
