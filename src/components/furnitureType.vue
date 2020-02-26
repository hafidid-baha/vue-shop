<template>
    <div class="col-md-4 pr-2 mt-1 mb-1" style="background:transparent ;">
        <div class="col-12 chair-item pt-1 pb-1">
            <div class="row align-items-center pt-3 pb-3">
                <div class="col-6 pt-2 pb-2">
                    <b class="d-block">{{args.title}}</b>
                    <b class="d-block" style="color: lightskyblue;">{{args.subTitle}}</b>
                    <a href="" class="details mt-4 d-block">View Collection</a>
                </div>
                <div class="col-6">
                    <img class="img-fluid" :src="require(`./../assets/${args.img}`)" />
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'FurnitureType',
    props:{
        args:Object
    }
}
</script>