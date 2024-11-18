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
                            <a class="nav-link" href="post.html" ><i class="fa-solid fa-blog"></i> Bài viết</a>
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
                            <a href="#" class="nav-link">Đăng Nhập</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link">Đăng ký</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <div class="carousel slide" id="slide">
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
        <div class="row">
            <!-- xây dựng aside --> 
            <aside class="col-sm-4">
                <h2 class="text-info mb-3">Về tôi</h2>
                <section class="card blog bg-light">
                    <img src="../assets/images/avatar.png" alt="ảnh của tôi" class="card-img-top">
                    <div class="body">
                        <h5 class="card-title"> Giới thiệu bản thân</h5>
                        <p class="card-text"> TS. Trần Hoàng. Tổ chức tư vấn sức khỏe quốc tế độc lập <br>
                            Châm ngôn: Ta không được chọn nơi mình sinh ra nhưng chúng ta có thể chọn nơi mình chế đi
                        </p>
                    </div>
                </section>
                <h3 class="text-info mt-2"> Chuyên mục</h3>
                <ul class="list-group">
                    <li class="list-group-item active bg-info d-flex justify-content-between align-items-center">
                        <a href="#" class="nav-link">Chế độ học tập</a>
                        <span class="badge bg-primary rounded-pill">12</span>
                    </li>
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        <a href="#" class="nav-link">Chế độ dinh dưỡng</a>
                        <span class="badge bg-primary rounded-pill">15</span>
                    </li>
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        <a href="#" class="nav-link">Cẩm nang cuộc sống</a>
                        <span class="badge bg-primary rounded-pill">99</span>
                    </li>
                </ul>
            </aside>
            <!-- xây dựng article -->
             <article class="col-sm-8 mb-5">
                <h2 class="text-info md-3">Blog của tôi</h2>
                <div class="row bg-light rounded">
                    <div class="col-sm-5 m-3 rounded" style="background-color: white;">
                        <h5 class="text-title">Phương pháp tập Pilates giúp phục hồi chấn thương cột sống <span class="fa-solid fa-message">16</span></h5>
                        <br>
                        <div class="card-body">
                            <img src="../assets/images/tap-piltes.jpg" alt="" class="card-img-top">
                            <p class="card-text">Ngoài việc giúp duy trì vóc dáng, cải thiện sự linh hoạt, dẻo dai cho người học,
                                Pilates giúp cơ bắp và các khớp mọc dài hơn, kéo giãn hơn...
                            </p>
                        </div>
                    </div>
                    <div class="col-sm-6 m-3 rounded" style="background-color: white;">
                        <ul class="list-group">
                            <li class="list-group-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6">
                                      <img src="../assets/images/corevalue.jpg" class="img-fluid" alt="Hình ảnh mô tả">
                                    </div>
                                    <div class="col-md-6">
                                      <h5>Biết ơn đời, Đời sẽ thương ta</h5>
                                      <p class="fa-solid fa-message">30</p>
                                    </div>
                                  </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6">
                                      <img src="../assets/images/orange_300x300.jpg" class="img-fluid" alt="Hình ảnh mô tả">
                                    </div>
                                    <div class="col-md-6">
                                      <h5>chín giá trị tuyệt vời của quả cam</h5>
                                      <p class="fa-solid fa-message">28</p>
                                    </div>
                                  </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6">
                                      <img src="../assets/images/sesameoil_300x300.jpg" class="img-fluid" alt="Hình ảnh mô tả">
                                    </div>
                                    <div class="col-md-6">
                                      <h5>10 công dụng bất ngờ từ dầu dừa</h5>
                                      <p class="fa-solid fa-message">15</p>
                                    </div>
                                  </div>
                            </li>
                            <li class="list-group-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6">
                                      <img src="../assets/images/eat-clean.png" class="img-fluid" alt="Hình ảnh mô tả">
                                    </div>
                                    <div class="col-md-6">
                                      <h5>lợi ích khi ăn rau mỗi ngày</h5>
                                      <p class="fa-solid fa-message">12</p>
                                    </div>
                                  </div>
                            </li>
                        </ul>
                    </div>
                    <div class="card-body d-flex text-white justify-content-center">
                        <button class="bg-info btn-primary btn mx-3" type="button">Xem thêm</button>
                    </div>
                    
                </div>
             </article>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-sm-4">
                    <ul class="nav nav-tabs" role="tablist">
                        <li class="nav-item">
                            <a href="#DocNhieu" data-bs-toggle="tab" class="nav-link" ><h4 class="text-info">Đọc nhiều</h4></a>
                        </li>
                        <li class="nav-item">
                            <a href="#XemNhieu" data-bs-toggle="tab" class="nav-link"><h4 class="text-info">Xem nhiều</h4></a>
                        </li>
                    </ul>
                    <div class="tab-content">
                        <div id="DocNhieu" class="tab-pane container active" >
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/corevalue.jpg" alt="" class="d-flex w-100 h-100">
                                </div>
                                <div class="col-sm-6">
                                    <h4>Biết ơn đời, đời sẽ thương ta</h4>
                                </div>
                            </div>
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/sesameoil_300x300.jpg" alt="" class="d-flex w-100 h-100">
                                </div>
                                <div class="col-sm-6">
                                    <h4>10 công dụng bất ngờ của dầu dừa</h4>
                                </div>
                            </div>
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/spinach_300x300.jpg" alt="" class="d-flex w-100 h-100">
                                </div>
                                <div class="col-sm-6">
                                    <h4>Lợi ích khi ăn rau mỗi ngày</h4>
                                </div>
                            </div>
                        </div>
                        <div id="XemNhieu" class="tab-pane container">
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/video1.jpg" alt="" class="d-flex w-100 h-200">
                                </div>
                                <div class="col-sm-6">
                                    <h4>Đi xa hơn để trưởng thành hơn</h4>
                                </div>
                            </div>
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/video2.jpg" alt="" class="d-flex w-100 h-200">
                                </div>
                                <div class="col-sm-6">
                                    <h4>Chút tâm tư những ngày cuối năm</h4>
                                </div>
                            </div>
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/video3.jpg" alt="" class="d-flex w-100 h-200">
                                </div>
                                <div class="col-sm-6">
                                    <h4>Ước gì được trở về tuổi thơ</h4>
                                </div>
                            </div>
                            <div class="row my-2">
                                <div class="col-sm-5">
                                    <img src="../assets/images/video4.jpg" alt="" class="d-flex w-100 h-200">
                                </div>
                                <div class="col-sm-6">
                                    <h4>Ba người thầy vĩ đại</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-sm-8 ">
                    <h3 class="text-title text-info text-center">VIDEO - ĐỪNG BỎ LỠ</h3>
                    <div class="container ms-5">
                        <div class="row  mb-5">
                            <div class="col-sm-5 mx-2 border rounded">
                                <img src="../assets/images/video1.jpg"  alt="" class="card-img-top my-2">
                                <h5 class="card-title   ">đi xa hơn để trưởng thành hơn</h5>
                                <p class="card-text">Tuổi trẻ chỉ nghĩ đến những chuyến đi,
                                 đợi mong 1 ngày được bay nhảy trên những phương trời mới lạ
                                </p>
                            </div>
                            <div class="col-sm-5 mx-2 border rounded">
                                <img src="../assets/images/video2.jpg"  alt="" class="card-img-top my-2">
                                <h5 class="card-title   ">Chút tâm tư những ngày cuối năm</h5>
                                <p class="card-text">Guồng quay cuộc sống dẫu có vội vàng, dẫu có tấp nập
                                    đến đâu thì cũng chẳng nằm ngoài quy luật của tự nhiên và bất biến xuân, hạ, thu, đông
                                    . Và rồi 1 năm cũ sắp trôi qua
                                </p>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-sm-5 mx-2 border rounded">
                                <img src="../assets/images/video3.jpg"  alt="" class="card-img-top my-2">
                                <h5 class="card-title   ">Ước gì được trở về tuổi thơ</h5>
                                <p class="card-text">
                                    Tuổi trẻ chỉ nghĩ đến những chuyến đi,
                                    đợi mong 1 ngày được bay nhảy trên những phương trời mới lạ
                                </p>
                            </div>
                            <div class="col-sm-5 mx-2 border rounded">
                                <img src="../assets/images/video4.jpg"  alt="" class="card-img-top my-2">
                                <h5 class="card-title   ">Ba người thầy vĩ đại</h5>
                                <p class="card-text">
                                    Ta xem vạn vật là thầy. Tinh thần học hỏi của ta luôn mở rộng hơn tất cả các người.
                                    Ta học hỏi từ tất cả mọi vật. Từ cành cây ngọn cỏ đến những đám mây trên trời kia
                                </p>
                            </div>
                        </div> 
                    </div>
                    <div class="d-flex justify-content-center mt-2">
                        <button class=" btn btn-primary text-white"> xem thêm</button>
                    </div>
                    
                </div>
            </div>
        </div>
        <footer class="bg-dark text-white text-center">
            <p class="card-text p-2">FPT Polytechnic</p>
            <p class="card-text p-2">PS39108-Bùi Hữu Lộc</p>
        </footer>
    </div>
</template>