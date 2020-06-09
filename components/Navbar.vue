<template>
    <div class="container-fluid container_bg col fixed-top">
       <div class="container nav_padding">
      <nav class="navbar navbar-expand-lg navbar-light mt-2">
        <nuxt-link to ="/" class="navbar-brand"><img src="img/logo/logo.png" alt="" srcset=""></nuxt-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      
        <div class="collapse navbar-collapse " id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto line_down">
            <li class="nav-item active">
              <nuxt-link to ="/" class="nav-link">home <span class="sr-only">(current)</span></nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="#about" class="nav-link" >about</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="#service" class="nav-link">services</nuxt-link>
            </li>
          </ul>
          <form>
            <li class="nav-item btn_nav">
              <div class="dropdown">
                    <button class="btn btn-dark dropdown dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                      get started
                    </button>
                    <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                      <nuxt-link to ="/login" class="dropdown-item" >Log In</nuxt-link>
                      <nuxt-link to="/signIn" class="dropdown-item">Sign Up</nuxt-link>
                    </div>
                  </div>              
            </li>
          </form>
        </div>
      </nav>
      </div>
    </div>
    
</template>

<script>
export default {
  
}
</script>
<style scoped>
.container_bg{
  padding: 1rem 1rem;
  background-color: hsl(229, 31%, 21%);
}
.navbar-nav > li{
    margin-left: 2rem !important;
    text-transform: capitalize; 
}
ul li a{
  color: white !important;
  font-size: 1.2rem;
  -webkit-transition: 2s; 
  transition:  2s;
}
li a:hover{
    color : #f15f22 !important;
}
.dropdown-menu > a .dropdown-item{
  color: black !important;
}
.btn_nav{
  margin-left: 3rem;
  text-transform: capitalize !important;
  list-style-type: none !important;
}
.btn-dark {
    color: white;
    border-color: #f15f22 !important;
    background-color:  #f15f22 !important;
    -webkit-transition: 2s; 
    text-transform: capitalize !important;
    transition:  2s;
}
/* .btn-dark:hover{
  background-color: #ffc107 !important;
  border-color:  #ffc107 !important;
  transition-timing-function: ease-in;
  color: hsl(229, 31%, 21%);
} */
.btn{
  padding: .375rem 2rem !important;
}
.line_down{
  -webkit-transition: 2s; 
  transition:  2s;
}
.line_down li:hover{
   border-bottom: 4px solid  #f15f22 !important;
}
@media only screen and (max-width: 600px) {
li{
    text-transform: capitalize;
    padding: 0.4rem;
}
.navbar-nav > li{
    margin-left: 0 !important;
    text-transform: capitalize; 
}
.nav_padding{
    padding-right: 0px !important;
    padding-left: 0px !important;
}
.navbar{
  padding : 0 !important;
}
.btn_nav{
  margin-left: 0;
  text-transform: capitalize;
  list-style-type: none !important;
}
.navbar-light .navbar-toggler {
  border-color: white !important;
  background-color: white !important;
}
.line_down li:hover{
   border-bottom: none !important;
   
}
}
@media only screen and (max-width: 800px) {
li{
    text-transform: capitalize;
    padding: 0.4rem;
}
.navbar-nav > li{
    margin-left: 0 !important;
    text-transform: capitalize; 
}
.nav_padding{
    padding-right: 0px !important;
    padding-left: 0px !important;
}
.navbar{
  padding : 0 !important;
}
.btn_nav{
  margin-left: 0;
  text-transform: capitalize;
  list-style-type: none !important;
}
.navbar-light .navbar-toggler {
  border-color: white !important;
  background-color: white !important;
}
}


</style>