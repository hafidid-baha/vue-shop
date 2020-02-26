<template>
    <div class="col-sm-12 col-md-3 p-3">
        <div class="col-12 offer-item pt-4 pb-4">
            <span class="d-block font-italic">{{offerArgs.title}}</span>
            <b>{{offerArgs.desc}}</b>
        </div>
    </div>
</template>
<script>

export default {
    name:'OfferItem',
    props:{
        offerArgs:Object
    }
}
</script>