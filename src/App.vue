<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <button type="button" class="btn btn-primary">test primary</button> -->
    <Nav/>
    <Header/>
    <ChairsContainer/>
    <TrendingProsucts/>
    <Categories/>
    <Offers />
    <products/>
    <!-- devider start-->
    <div class="container mt-5 mb-5">
        <hr />
    </div>
    <!-- devider ends-->
    <Futters/>
    <!-- footer start -->
    <div class="container-fluid banner overflow-hidden mt-5 pt-3 pb-3">
        <div class="container">
            <div class="row">
                <div class="col-md-3 p-1 align-self-center text-center">
                    <h5 style="height: 50px;line-height: 50px;"><img class="img-fluid" src="./assets/logo.png" height="50" /></h5>
                    <span class="footer-text d-block mt-4">Address:NO 40-Baria Street 133/2,Usa</span>
                    <span class="footer-text d-block">Phone 01:+(800) 123 458 458</span>
                    <span class="footer-text d-block">Phone 02:+(800) 524 246 478</span>
                    <span class="footer-text d-block">Fax:(800) 124 246 478</span>
                    <span class="footer-text d-block">Email:Contact@gmail.com</span> 
                </div>
                <div class="col-md-3 p-1 text-center">
                    <h5 style="height: 50px;line-height: 50px;" class="text-uppercase">About Us</h5>
                    <span class="footer-text mt-4 d-block">Support Center</span>
                    <span class="footer-text d-block">Customer Support</span>
                    <span class="footer-text d-block">About Us</span>
                    <span class="footer-text d-block">Copyright</span>
                    <span class="footer-text d-block">Popular Compaign</span> 
                </div>
                <div class="col-md-3 p-1 text-center">
                    <h5 style="height: 50px;line-height: 50px;" class="text-uppercase">Our Information</h5>
                    <span class="footer-text mt-4 d-block">Return Policy</span>
                    <span class="footer-text d-block">Privacy Policy</span>
                    <span class="footer-text d-block">Termes And Conditions</span>
                    <span class="footer-text d-block">Site Map</span>
                    <span class="footer-text d-block">Store Hours</span> 
                </div>
                <div class="col-md-3 p-1 text-center">
                    <h5 style="height: 50px;line-height: 50px;" class="text-uppercase">My Account</h5>
                    <span class="footer-text mt-4 d-block">My Account</span>
                    <span class="footer-text d-block">Cart</span>
                    <span class="footer-text d-block">CheckOut</span>
                    <span class="footer-text d-block">Contact</span>
                    <span class="footer-text d-block">Checklist</span> 
                </div>
            </div>
            <hr />
            <div class="row mt-1">
                <div class="col-12 text-center p-1">
                    <h5 style="height: 50px;line-height: 50px;" class="text-uppercase">Join Our NewsLetter</h5>
                    <span class="footer-text mt-2 d-block">Be The First To Hear About New Trending And Offers And See How You Have Helped.</span>
                    <div class="">
                        <form class="subscribe-form d-inline-flex mx-auto mt-5 mb-5">
                            <input placeholder="your email Address" class="p-2 m-0 border-0 pl-1 pr-1" type="email" name="" value="" />
                            <input type="submit" class="border-0 overflow-hidden" name="" value="Subscribe" />
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- footer ends -->

    <!-- footer links starts-->
    
    <div class="container mt-3">
        <div class="row">
            <div class="col-sm-4 col-md-4 text-center">
                <p class="copy">Copyright &copy;2020 hafid id-baha</p>
            </div>
            <div class="col-sm-4 col-md-4 text-center">
                <div class="mx-auto">
                    <i class="fab fa-facebook-f mr-2 ml-2"></i>
                    <i class="fab fa-twitter mr-2 ml-2"></i>
                    <i class="fab fa-google mr-2 ml-2"></i>
                    <i class="fab fa-instagram mr-2 ml-2"></i>
                </div>
            </div>
            <div class="col-sm-4 col-md-4">
                <div class="mx-auto text-center">
                    <img class="img-fluid mr-2 ml-2" src="./assets/visa.png" />
                    <img class="img-fluid mr-2 ml-2" src="./assets/paypal.png" />
                    <img class="img-fluid mr-2 ml-2" src="./assets/mastercard.png" />
                    <img class="img-fluid mr-2 ml-2" src="./assets/meastro.png" />
                </div>
            </div>
        </div>
    </div>
    
    <!-- footer links ends-->
    
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/nav.vue'
import Header from './components/header.vue'
import ChairsContainer from './components/chairsContainer.vue'
import TrendingProsucts from './components/trendingProducts.vue'
import Categories from './components/categories.vue'
import Offers from './components/offers.vue'
import Products from './components/products.vue'
import Futters from './components/futters.vue'

export default {
  name: 'App',
  components: {
    Nav,Header,ChairsContainer,TrendingProsucts,Categories,Offers,Products,Futters
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

body {
  background-color: #ffffff;
  color: #2a2a2a;
  font-family: 'Poppins', sans-serif;
}

body h1, body h2, body h3, body h4 {
  text-transform: uppercase;
}

body .navbar-nav .nav-item a {
  color: #2a2a2a;
}

body .navbar-nav .nav-item .i-settings {
  background: url(/img/settings.svg);
  background-position: center;
  background-size: contain;
  width: 30px;
  height: 30px;
  cursor: pointer;
}

body .navbar-nav .nav-item .i-search {
  background: url(/img/search.svg);
  background-position: center;
  background-size: contain;
  width: 30px;
  height: 30px;
  cursor: pointer;
}

body .navbar-nav .nav-item .i-market {
  background: url(/img/market.svg);
  background-position: center;
  background-size: contain;
  width: 30px;
  height: 30px;
  cursor: pointer;
}

body .navbar-nav .nav-item .item-count {
  background-color: #b0262b;
  border-radius: 50%;
  color: #ffffff;
  font-size: 0.8em;
}

body .banner {
  background-color: #e7e5e536;
}

body .banner .btn-light {
  border: 2px #2a2a2a solid;
  text-transform: capitalize;
  background: transparent;
}

body .banner .footer-text {
  color: #2a2a2a;
}

body .banner .subscribe-form input[type='email'] {
  border-radius: 15px 0px 0px 15px;
  overflow: hidden;
}

body .banner .subscribe-form input[type='submit'] {
  border-radius: 0px 15px 15px 0px;
  background-color: #2a2a2a;
  color: #ffffff;
}

body .banner .subscribe-form input[type='email']:hover,
body .banner .subscribe-form input[type='email']:active,
body .banner .subscribe-form input[type='email']:focus {
  outline: none;
}

body .chair-item {
  background-color: #e7e5e536;
}

body .chair-item .details {
  text-decoration: underline;
  color: #b0262b;
}

body .chair-item img {
  -o-object-fit: fill;
     object-fit: fill;
}

body .rating span {
  width: 25px;
  height: 25px;
  display: inline-block;
  background-position: center;
  background-size: cover;
  -webkit-clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
          clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
}

body .rating .small {
  width: 15px !important;
  height: 15px !important;
}

body .pricing .old {
  text-decoration: line-through;
  color: #e4e4e4;
}

body .discount {
  width: 50px;
  background: #b0262b;
  color: #ffffff;
}

body .offer-item {
  background-color: #e7e5e536;
}

body .copy {
  color: #2a2a2a;
}
/*# sourceMappingURL=main.css.map */
</style>
