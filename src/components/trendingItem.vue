<template>
    <div class="col-sm-12 mt-1 col-md-3">
        <div class="card border-0 position-relative" style="width: 18rem;">
            <img :src="require(`./../assets/${args.img}`)" class="card-img-top" alt="...">
            <span class="d-block position-absolute text-center discount">{{args.discount}}</span>
            <div class="card-body">
                <div class="rating text-center">
                    <span class="" :style="[ args.rating >= 1 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ args.rating >= 2 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ args.rating >= 3 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ args.rating >= 4 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ args.rating >= 5 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                </div>
                <p class="card-text text-center font-weight-bold mt-1">{{args.title}}</p>
                <div class="text-center pricing">
                    <span class="old pl-1 pr-1">&#36;{{args.oldprice}}</span>
                    <span class="pl-1 pr-1">&#36;{{args.newprice}}</span >
                </div>
            </div>
            </div>
    </div>
</template>
<script>
export default {
    name:'TrandingItem',
    props:{
        args:Object
    }
}
</script>