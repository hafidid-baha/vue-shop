<template>
    <!-- header section start -->
    <div class="container-fluid banner overflow-hidden">
        <div class="container h-100 pt-3 pb-3">
            <div class="row h-100 align-items-center">
                <div class="col-md-6">
                    <div class="w-50 mx-auto my-auto text-left">
                        <h4 class="text-capitalize font-weight-normal">{{title}}</h4>
                        <b style="font-size: 2em;">{{itemName}}</b>
                        <p class="text-wrap font-weight-light mt-3">
                            {{itemDesc}}
                        </p>
                        <a href="" class="btn btn-light rounded-0 font-weight-bold mt-5 pl-4 pr-4">SHOP NOW</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <img class="img-fluid p-5" v-bind:src="require(`./../assets/${itemImage}`)" />
                </div>
            </div>

        </div>
    </div>
    <!-- header section ends -->
</template>
<script>
export default {
    name:'Header',
    data(){
        return {
            title:'New Arrivals',
            itemName:'STINGRAY CHAIR',
            itemDesc:'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sint, nobis.',
            itemImage:"schair.png"
        }
    }
}
</script>
<style scoped>

</style>