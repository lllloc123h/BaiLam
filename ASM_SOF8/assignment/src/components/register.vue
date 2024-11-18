<template>
    <h2 class="title mb-2">form đăng ký thông tin</h2>
    <form class="border rounded p-4 text-start">
        <label for="" class="form-label">Họ và tên</label>
        <input type="text" class="form-control mb-3" placeholder="Nhập họ và tên">

        <label for="" class="form-label">Email</label>
        <input type="text" class="form-control mb-3" placeholder="Nhập Email">

        <label for="" class="form-label">Số điện thoại</label>
        <input type="text" class="form-control mb-3" placeholder="Nhập số điện thoại">

        <label for="" class="form-label">Nhập mật khẩu</label>
        <input type="text" class="form-control mb-3" placeholder="Nhập mật khẩu">

        <label for="" class="form-label">Xác nhập mật khẩu</label>
        <input type="text" class="form-control mb-3" placeholder="Xác nhận mật khẩu">

        <div>
            <label for="" class="form-label">Giới tính</label>
            <input type="radio" value="Nam" name="giới tính" class="mx-1">Nam
            <input type="radio" value="Nữ" name="giới tính" class="mx-1">Nữ
        </div>
                    
        <label for="" class="form-label">Ngôn ngữ</label>
        <div >
            <select name="" id="" class="form-select">
                <option value="Tiếng Việt">Tiếng Việt</option>
                <option value="Tiếng Hàn">Tiếng Hàn</option>
                <option value="Tiếng Thái">Tiếng Thái</option>
            </select>
            </div>
            <input type="checkbox" name="" id=""  class="my-3">Tôi đồng ý
            <div>
                <button class="btn btn-primary">Đăng Ký</button>
            </div>
    </form>
</template>