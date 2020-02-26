<template>
    <!-- start section-->
    <div class="container mb-5 mt-5">
        <div class="row pt-3 pb-3 justify-content-between">

            <FurnitureType v-for="(item, index) in items" :key="index" :args=item />

        </div>
    </div>
    <!-- start section-->
</template>
<script>
import FurnitureType from './furnitureType.vue'
export default {
    name:'Categories',
    components:{
        FurnitureType
    },
    data(){
        return{
            items:[
                {title:'BOOMRANG',subTitle:'CHAIR',img:'chair3.png'},
                {title:'FLAT WODEN',subTitle:'PLATES',img:'wod.png'},
                {title:'CREATIVE DESIGN',subTitle:'THERMOSCAN',img:'chair3.png'}
            ]
        }
    }
}
</script>