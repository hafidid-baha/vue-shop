<template>
    <!-- chair items start -->
    <div class="container mb-5">
        <div class="row pt-3 pb-3 justify-content-between">
            <ChairCategoryItem v-for="cat in chairCategories" :key="cat" :args= cat />
        </div>
    </div>
    <!-- chair items start -->    
</template>

<script>
import ChairCategoryItem from './chairCategoryItem.vue'
export default {
    name:'ChairsContainer',
    components:{
        ChairCategoryItem
    },
    data(){
        return{
            chairCategories:{
                cat1:{ftitle:"Hafid",stitle:"id-baha",desc:"Lorem ipsum dolor sit amet, consectetur adipisicing."},
                cat2:{ftitle:"Ahmed",stitle:"chair",desc:"Lorem ipsum dolor sit amet, consectetur adipisicing."},
                cat3:{ftitle:"Osama",stitle:"chair",desc:"Lorem ipsum dolor sit amet, consectetur adipisicing."}
            }
        }
    }
}
</script>