<template>
    <div class="container">
        <div class="row w-100">
            <div class="col-12">
                <nav class="navbar navbar-expand-lg navbar-light">
                    <a class="navbar-brand" href="#"><img class="img-fluid" src="./../assets/logo.png" height="50" /></a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                  
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav mr-aut w-100">
                            <li class="nav-item active">
                                <a class="nav-link active" href="">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="">Shope</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="">Blog</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="">Pages</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="">Contact Us</a>
                            </li>
                            <li class="nav-item d-inline-block ml-auto">
                                <a class="i-settings d-inline-block ml-2"><i class="fab fa-medium"></i></a>
                                <a class="i-search d-inline-block ml-2"></a>
                                <a class="i-market d-inline-block ml-4"></a>
                                <div class="item-count pl-2 pr-2 d-inline-block">5</div>
                            </li>
                        </ul>
                    </div>
                </nav>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Nav'
}
</script>
<style scoped>

</style>