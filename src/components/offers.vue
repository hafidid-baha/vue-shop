<template>
    <!-- offers section start-->
    <div class="container">
        <div class="row">
            <OfferItem v-for="(item, index) in offerItems" :key="index" :offerArgs=item />
        </div>
    </div>
    <!-- offers section ends-->
</template>
<script>
import OfferItem from './offerItem.vue'
export default {
    name:'Offers',
    components:{
        OfferItem
    },
    data(){
        return{
            offerItems:[
                {title:'Popular Furniture',desc:'BESTSELLER PRODUCTS'},
                {title:'New Furniture',desc:'NEW ARAIVALS PRODUCTS'},
                {title:'Sale Furniture',desc:'ON SALE PRODUCTS'},
                {title:'Top Furniture',desc:'TOP RATED PRODUCTS'},
            ]
        }
    }
}
</script>