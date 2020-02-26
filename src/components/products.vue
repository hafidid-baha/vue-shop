<template>
    <!-- products section start -->
    <div class="container mt-5">
        <div class="row">
            <ProductItem v-for="(item,index) in products" :key="index" :productItemArgs=item />
        </div>
    </div>
    <!-- products section ends -->
</template>
<script>
import ProductItem from './productItem.vue'
export default {
    name:'Products',
    components:{
        ProductItem
    },
    data(){
        return{
            products:[
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:4,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:5,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:2,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:1,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:5,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:4,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:3,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:2,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:2,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:5,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:4,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:4,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:1,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:1,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:2,oldprice:121.5,newprice:25.3},
                {img:'chair3.png',desc:'Lorem ipsum dolor sit amet, consectetur.',rating:5,oldprice:121.5,newprice:25.3}
            ]
        }
    }
}
</script>