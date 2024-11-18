<template>
    <div class="container">
        <h1 class="text-center">Kiến thức sức khỏe cộng đồng</h1>
        <div class="row">
            <div class="col-sm-4">
                <div class="card">
                    <img :src="items[0].img" alt="hình ảnh"/>
                    <div class="card-body">
                        <h3 class="card-title">{{ items[0].Title }}</h3>
                        <p class="card-text">{{ items[0].Content }}</p>
                        <button class="btn btn-info"> Xem chi tiết</button>
                    </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card">
                    <img :src="items[1].img" alt="hình ảnh"/>
                    <div class="card-body">
                        <h3 class="card-title">{{ items[1].Title }}</h3>
                        <p class="card-text">{{ items[1].Content }}</p>
                        <button class="btn btn-info"> Xem chi tiết</button>
                    </div>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="card">
                    <img :src="items[2].img" alt="hình ảnh"/>
                    <div class="card-body">
                        <h3 class="card-title">{{ items[2].Title }}</h3>
                        <p class="card-text">{{ items[2].Content }}</p>
                        <button class="btn btn-info"> Xem chi tiết</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script setup>
    import img1 from '../assets/tap-pilates1.jpg'
    import img2 from '../assets/tap-pilates2.jpg'
    import img3 from '../assets/tap-piltes.jpg'
    const items = [
        {Title: '8 loại rau củ giàu canxi', Content:'Canxi là.... ', img: img1},
        {Title: 'các loại gia vị tốt cho sức khỏe', Content:'Canxi là.... ', img: img2},
        {Title: '9 loại đậu bổ dưỡng nên dùng nhiều', Content:'Canxi là.... ', img: img3},
    ]
</script>