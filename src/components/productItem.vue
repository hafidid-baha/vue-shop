<template>
    <div class="col-sm-6 col-md-3 pr-2" style="background:transparent ;">
        <div class="row">
            <div class="col-5">
                <img class="img-fluid" :src="require(`./../assets/${productItemArgs.img}`)" />
            </div>
            <div class="col-7">
                <p class="text-wrap font-weight-bold pt-2">{{productItemArgs.desc}}</p>
                <div class="rating text-left">
                    <span class="" :style="[ productItemArgs.rating >= 1 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ productItemArgs.rating >= 2 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ productItemArgs.rating >= 3 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ productItemArgs.rating >= 4 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                    <span class="" :style="[ productItemArgs.rating >= 5 ? {'background': '#b0262b'} : {'background': '#ffffff'} ]"></span>
                </div>
                <div class="text-center pricing text-left bg-danger">
                    <span class="old pl-1 pr-1 float-left">&#36;{{productItemArgs.oldprice}}</span>
                    <span class="pl-1 pr-1 float-left">&#36;{{productItemArgs.newprice}}</span >
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'ProductItem',
    props:{
        productItemArgs:Object
    }
}
</script>