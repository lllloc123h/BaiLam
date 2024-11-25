    <template>
        <div class="container">
            <h1 class="text-center"> kiến thức cộng đồng</h1>
            <div class="row">
                <div class="col-sm-4 mb-4" v-for="(item,index) in list" :key="index">
                    <div class="card">
                        <img :src="item.img" alt="hình ảnh" class="img-fluid">
                        <div class="card-body">
                            <h3 class="card-title">{{ item.title }}</h3>
                            <p class="card-text">{{ item.content }}</p>
                            <button class="btn btn-primary">xem thêm</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </template>
    <script setup>
        import img1 from "@/assets/img/bai3_1.png"
        import img2 from "@/assets/img/bai3_2.png"
        import img3 from "@/assets/img/bai3_3.png"
        import { reactive } from "vue";
        const list = reactive([
            {
                img: img1,
                title:"8 loại rau củ giàu canxi",
                content:"canxi là khoáng chất cần thiết đối với cơ thể con ngừ. có nhiều cách để bổ sung canxi"
            },
            {
                img:img2,
                title:"Các loại gia vị tốt cho sức khỏe",
                content:"Một số loại gia vị cung cấp nhiều polyphenol chống oxi hóa cao hơn các loại gia vị khác"
            },
            {
                img:img3,
                title:"9 loại đậu bổ dưỡng nên dùng nhiều",
                content:"Đậu lăng, đậu này, đậu phộng, đậu hà lan giàu chất xơ, protein cx nhiều vitamin và khoáng chất"
            }
        ])
    </script>