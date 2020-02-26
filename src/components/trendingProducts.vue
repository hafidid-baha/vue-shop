<template>
    <!-- Trending products section start-->
    
    <div class="container">
        <div class="row">
            <div class="col text-center">
                <span class="d-block text-uppercase">{{ smallTitle }}</span>
                <h4>{{ mainTitle }}</h4>
            </div>
        </div>
        <div class="row mt-4 justify-content-center">
            <TrandingItem v-for="(item, index) in trendingProducts" :key="index" :args= item />
        </div>
    </div>

    <!-- Trending products section end-->
</template>
<script>
import TrandingItem from './trendingItem';
export default {
    name:'TrndingProducts',
    components:{TrandingItem},
    data(){
        return{
            smallTitle:'new shop items',
            mainTitle:'trending products',
            trendingProducts:[
                {img:'chair1.jpg',discount:'-4%',rating:2,title:'some bold title exemple for demonstrating',oldprice:50.2,newprice:10.2},
                {img:'chair2.jpg',discount:null,rating:3,title:'some bold title exemple for demonstrating',oldprice:150.2,newprice:100.2},
                {img:'chair3.jpg',discount:'-41%',rating:5,title:'some bold title exemple for demonstrating',oldprice:300.2,newprice:110.2},
                {img:'chair1.jpg',discount:null,rating:2,title:'some bold title exemple for demonstrating',oldprice:50.2,newprice:10.2}
            ]
        }
    }
}
</script>