<template>
    <div class="container-fluid ">
        <div class="container margin_top">
            <div class="card shadow rounded"  data-aos="fade-up" data-aos-duration="1000" data-aos-anchor-placement="center-bottom">
            <div class="card-body">
                <form>
                    <h5 class="modal-title" id="exampleModalLabel">LOG IN</h5>
                    <hr>
                    <div class="form-group">
                            <label for="exampleInputEmail1">Email address</label>
                            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
                            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
                        </div>
                        <div class="form-group">
                            <label for="exampleInputPassword1">Password</label>
                            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                            <small id="emailHelp" class="form-text text-muted click_pass">Forgot Password?</small>
                        </div>
                        <div class="form-group form-check">
                            <input type="checkbox" class="form-check-input" id="exampleCheck1">
                            <label class="form-check-label" for="exampleCheck1">Remember me</label>
                        </div>
                        
                        <button type="submit" class="btn btn-primary">LOG IN</button>
        </form>
            </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.card{
    width: 30%;
    margin-left: 25rem;
}
.margin_top{
    margin-top: 13rem !important;
}
.click_pass{
    cursor: pointer;
}
.btn-primary {
    color: white;
    border-color: #f15f22 !important;
    background-color:  #f15f22 !important;
    text-transform: capitalize;
}
@media only screen and (max-width: 600px) {
.card{
    width: 100%;
    margin-left: 0;
}
.margin_top{
    margin-top: 13rem !important;
}
.click_pass{
    cursor: pointer;
} 
}
@media only screen and (min-width: 700px)  and (max-width: 1200px) {
.card{
    width: 50%;
    margin-left: 10rem !important;
}
.margin_top{
    margin-top: 13rem !important;
}
.click_pass{
    cursor: pointer;
} 
} 


</style>