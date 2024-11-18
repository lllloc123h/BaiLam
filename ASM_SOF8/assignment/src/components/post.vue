<template>
    <div class="container">
        <nav class="navbar navbar-expand-sm navbar-light bg-light">
            <div class="container">
                <a href="/Lab3/index.html"><img src="../assets/images/logo-energy-pilates.png" alt="" style="width: 150px;"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="collapsibleNavbar">
                    <ul class="navbar-nav me-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#" ><i class="fa-solid fa-blog"></i> Bài viết</a>
                        </li>
                        <li>
                            <a href="#" class="nav-link"><i class="fa-solid fa-video"></i> video</a>
                        </li>
                        <li>
                            <a href="#" class="nav-link"><i class="fa-solid fa-info"></i> Giới Thiệu</a>
                        </li>
                        <li>
                            <a href="#" class="nav-link"><i class="fa-solid fa-regular fa-calendar-days"></i> Sự Kiện</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a href="#" class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown"> 
                                <i class="fa-solid fa-user"></i> Tài khoản
                            </a>
                            <ul class="dropdown-menu">
                                <li><a href="#" class="dropdown-item">Đăng Nhập</a></li>
                                <li><a href="#" class="dropdown-item">Đăng Ký Thành Viên</a></li>
                                <li><a href="#" class="dropdown-item">Quên Mật Khẩu</a></li>
                            </ul>
                        </li>
                    </ul>
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item">
                            <a href="#" class="nav-link">Tiếng Việt</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link">Tiếng Anh</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <div class="carousel slide" id="slide">
            <div class="carousel-indicators">
                <button type="button" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1" data-bs-target="#slide"></button>
                <button type="button" data-bs-slide-to="1"  aria-label="Slide 2" data-bs-target="#slide"></button>
                <button type="button" data-bs-slide-to="2"  aria-label="Slide 3" data-bs-target="#slide"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/images/banner1.jpg" class="d-block w-100" alt="">
                </div>
                <div class="carousel-item">
                    <img src="../assets/images/banner2.jpg" class="d-block w-100" alt="">
                </div>
                <div class="carousel-item">
                    <img src="../assets/images/banner3.jpg" class="d-block w-100" alt="">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#slide"data-bs-slide="prev"> 
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#slide"data-bs-slide="next"> 
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-sm-4 mt-3">
                    
                    <div class="border rounded mt-3">
                        <div class="card-title mt-3">
                            <h2 class="text-title text-info">Bài viết nổi bật</h2>
                        </div>
                        <hr>
                        <div class="card-body">
                            <div class="container row">
                                <div class="col-lg-6 my-3">
                                    <img src="../assets/images/corevalue.jpg" alt="" class="card-img rounded-circle">
                                </div>
                                <div class="col-md-6">
                                    <h5 class="text-title">Lợi ích khi ăn rau mỗi ngày</h5>
                                    <p>
                                        Tiêu thụ rau xanh hằng ngày giúp tăng thị lực
                                    </p>
                                </div>
                                
                            </div>
                            <div class="container row">
                                <div class="col-lg-6 my-3">
                                    <img src="../assets/images/orange_300x300.jpg" alt="" class="card-img rounded-circle">
                                </div>
                                <div class="col-md-6">
                                    <h5 class="text-title">Lợi ích khi ăn rau mỗi ngày</h5>
                                    <p>
                                        Tiêu thụ rau xanh hằng ngày giúp tăng thị lực
                                    </p>
                                </div>
                                
                            </div>
                            <div class="container row">
                                <div class="col-lg-6 my-3">
                                    <img src="../assets/images/sesameoil_300x300.jpg" alt="" class="card-img rounded-circle">
                                </div>
                                <div class="col-md-6">
                                    <h5 class="text-title">Lợi ích khi ăn rau mỗi ngày</h5>
                                    <p>
                                        Tiêu thụ rau xanh hằng ngày giúp tăng thị lực
                                    </p>
                                </div>
                                
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-8">
                    <h2 class="text-title text-info my-3 ms-3">Tất cả bài việc</h2>
                    <div class="container row">
                        <div class="col-lg-5 border rounded mt-1 mx-4 ms-5">
                            <h5 class="text-title mt-1"> Phương pháp tập Pilates giúp phục vụ việc phục hồi chấn thương <span class="fa-solid fa-message"> 16</span></h5>
                            <hr>
                            <div class="card-body">
                                <img src="../assets/images/tap-piltes.jpg" alt="" class="card-img-top m-1">
                                <p>
                                    Ngoài việc duy trì vóc giáng, cải thiện sự dẻo dai, cái bài tập Pilates còn có khả năng trị đau lưng
                                </p>
                            </div>
                        </div>
                        <div class="col-lg-5 border rounded mt-1 mx-4">
                            <a href="postDetail.html" class="nav-link"><h5 class="text-title mt-1">Đây là những gì 1 tập Pilates có thể làm cho cơ thể bạn <span class="fa-solid fa-message">8</span></h5></a>
                            <hr>
                            <div class="card-body">
                                <img src="../assets/images/tap-pilates1.jpg" alt="" class="card-img-top m-1">
                                <p>
                                    Được thiết kế để xây dựng cơ bắp săn chắc, khỏe mạnh hơn, bài tập này đã trở thành cái tên quen thuộc
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="container row mt-4">
                        <div class="col-lg-5 border rounded mt-1 mx-4 ms-5">
                            <h5 class="text-title mt-1"> tập pilates giúp cãi thiện tim mạch <span class="fa-solid fa-message"> 5</span></h5>
                            <hr>
                            <div class="card-body">
                                <img src="../assets/images/tim-mach.jpg" alt="" class="card-img-top m-1">
                                <p>
                                    tập luyện kĩ thuật này giúp cho tim mạch trở nên cãi thiện hơn có 1 cơ thể khỏe mạnh và linh hoạt mà còn có rất nhiều lợi ích
                                    . bài viết này còn giúp cho bạn tìm hiểu sâu hơn về tác đọngo tích cực
                                </p>
                            </div>
                        </div>
                        <div class="col-lg-5 border rounded mt-1 mx-4">
                            <h5 class="text-title mt-1"> EAT-CLEAN nên và không nên<span class="fa-solid fa-message"> 16</span></h5>
                            <hr>
                            <div class="card-body">
                                <img src="../assets/images/eat-clean.png" alt="" class="card-img-top m-1">
                                <p>
                                   Chúng ta luôn chú trọng lựa chọn thực phẩm sạch và duy trì lối sống lành mạnh. Vậy chế độ ăn Eat clean nên và không nên ăn gì 
                                   trong thực đơn hằng ngày để cân bằng tháp dinh dưỡng
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="container justify-content-center d-flex mt-3    ">
                        <ul class="pagination">
                            <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                            <li class="page-item"><a class="page-link" href="#">1</a></li>
                            <li class="page-item"><a class="page-link" href="#">2</a></li>
                            <li class="page-item"><a class="page-link" href="#">3</a></li>
                            <li class="page-item"><a class="page-link" href="#">Next</a></li>
                        </ul>
                            

                    </div>
                </div>
            </div>
            <footer class="bg-dark text-white text-center">
                <p class="card-text p-2">FPT Polytechnic</p>
                <p class="card-text p-2">PS39108-Bùi Hữu Lộc</p>
            </footer>
        </div>
    </div>
</template>