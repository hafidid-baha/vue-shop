<template>
    <div class="col-md-4 pl-2 pr-2 mt-1 mb-1" style="background:transparent ;">
        <div class="col-12 chair-item pt-1 pb-1">
            <div class="row">
                <div class="col-6 pt-2 pb-2">
                    <h4 class="h6">{{ args.ftitle }} <span class="marked" style="color: lightskyblue;">{{ args.stitle }}</span></h4>
                    <p class="text-wrap font-weight-light">{{args.desc}}</p>
                    <a href="" class="details">View Collection</a>
                </div>
                <div class="col-6">
                    <img class="img-fluid my-auto" src="./../assets/chair3.png" />
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:'chairCategoryItem',
    props:{
        args:Object
    },
    data(){
        return{
            fTitle:'Hanging',
            sTitle:'Chaire',
            itemDesc:'Lorem ipsum dolor sit amet, consectetur adipisicing.'
        }
    }
}
</script>