<template>
    <h1>{{ greenting }}</h1>
    <button v-bind:title="buttonTitle" @click="changeGreenting">
        click để thay đổi
    </button>
</template>
<script>
    export default{
        data(){
            return{
                greenting: 'xin chào thầy',
                buttonTitle: 'Nhấn để thay đổi lời chào'
            }
        },
        methods:{
            changeGreenting(){
                
                    this.greenting='hello, world',
                    this.buttonTitle='Lời chào mới đã được cập nhật'
            }
        }
    }
</script>