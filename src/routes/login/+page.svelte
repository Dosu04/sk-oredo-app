<script>
	import Oredologo from '$lib/images/OREDO-nav-logo.png';
	import Smile from '$lib/images/smile/smile.png';
	import Google from '$lib/images/google-icon.png';

</script>

<main>

<!-- Large screen sizes -->
<div class="container-fluid lg-screen" style="">
    <div class="row major" style="">
        <div class="col-lg-5 form-body" >
            <div class="logo">
                <img src={Oredologo} alt="" width="200px" style="margin-bottom: 1.5rem;">
            </div>
            <div class="form-content">
                <form action="">
                        <h3 class="mb-3"style="color:#AD7BE9;
                        ">Sign into your Account</h3>
                        <div class="mb-3 form-check">
                            <div style="margin-right:10rem">
                                <input type="checkbox" class="form-check-input-secondary" id="exampleCheck1">
                                <label class="form-check-label" for="exampleCheck1" >an organization</label>
                                
                            
                            <span style="float:right" >
                                
                            <input type="checkbox" class="form-check-input-secondary" id="exampleCheck1">
                            <label class="form-check-label" for="exampleCheck1" >a donor</label>
                            
                            </span>
                            </div>
                        </div><br>
                        <div class="inputs">
                            
                                <div class="mb-3">
                                  <input type="email" placeholder="Email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                                </div>
                                <br>
                                <div class="mb-3">
                                  <input type="password" placeholder="Password" class="form-control" id="exampleInputPassword1">
                                <pre style="text-align: right; color:#AD7BE9"><a href="/reset" style="color:#AD7BE9;">Forgot Password?</a></pre>                                
                                  
                                </div><br>
    
                        </div>
                        
                      <a href="/loggedHome">
                      <input type="submit" class="btn btn-primary inputs" value="Sign In"/>
                      </a>  
                        <br><br>
                        <a href="" style="background-color:white; border: 1px solid #b5b5b5; color:black;" type="submit" class="btn btn-primary inputs"><img style="margin-right:1rem"src={Google} alt="" width="25px"> Continue with Google</a>
<br><br>
<p>If you're new to Oredo,  <a href="/register" style="color:#AD7BE9">Create an Account</a> </p>
                    </form>

            </div>
        </div>
        <div class="col-lg-7" style="background-color:#AD7BE9; display:grid; place-items:center;">
            <img src={Smile} alt="" width="70%">
        </div>
    </div>
</div>


<!-- Small screen sizes -->
<div class="container-fluid sm-screen" style="">
    <div class="row major" style="">
        <div class="col-lg-12 form-body2" >
            <div class="logo">
                <img src={Oredologo} alt="" width="80px" style="margin-top:2rem;margin-bottom: 2.7rem; ">
            </div>
            <div class="form-content">
                <form action="">
                    <h6 class="mb-3"style="color:#AD7BE9;
                    ">Sign Into your Account</h6>
                    <div class="mb-3 form-check2">
                        <div style="">
                            <input type="checkbox" class="form-check-input-secondary" id="exampleCheck1">
                            <label class="form-check-label" for="exampleCheck1" >an organization</label>
                            
                        
                        <span style="float:right" >
                            
                        <input type="checkbox" class="form-check-input-secondary" id="exampleCheck1">
                        <label class="form-check-label" for="exampleCheck1" >a donor</label>
                        
                        </span>
                        </div>
                    </div>
                    <br>
                        <div class="inputs2">
                          
                                <div class="mb-3">
                                  <input type="email" placeholder="Email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                                </div>
                                <br>
                                <div class="mb-3">
                                  <input type="password" placeholder="Password" class="form-control" id="exampleInputPassword1">
                                  <pre style="text-align: right; "><a href="/reset" style="color:#AD7BE9;">Forgot Password?</a></pre> 
                                </div><br>
                                
    
                        </div>
                            <a href="/loggedHome" >
                                <input type="submit" style="width: 100%;" class="btn btn-primary inputs2" value="Sign In"/>
                                </a>  
                                 <br><br>
                       
                        <a href="" style="background-color:white; border: 1px solid #b5b5b5; color:black; width:100%" type="submit" class="btn btn-primary inputs2"><img style="margin-right:1rem"src={Google} alt="" width="25px"> Continue with Google</a>
<br><br>
<p style="padding: 0;">If you're new to Oredo,  <a href="/register" style="color:#AD7BE9">Create an Account</a> </p>
                </form>
            </div>
        </div>



<!-- <div class="container-fluid sm-screen" style="">
    <div class="row major">
        <div class="col-lg-12">
            
        </div>
    </div>
</div> -->

</main>

<style>
    input.inputs2{
    background-color:#AD7BE9 ;
    border:#AD7BE9 ;

}
.form-check2{
    margin-left:0;
}
.form-body2{
    padding: 0 1rem;
}
    .sm-screen{
    margin: 0;
    padding: 0;
    
}
    .major{
        height:100vh
    }
    
input.inputs{
    background-color:#AD7BE9 ;
    border:#AD7BE9 ;

}
.inputs {
    width: 22rem;
}
.form-content{

}
.form-body{
    padding: 3rem 3rem;
}
.lg-screen{
    margin: 0;
    padding: 0;
    
}
.row{
    margin: 0;
}
@media(max-width: 900px){
    .lg-screen{
        display: none;
    }
}
@media(min-width: 900px){
    .sm-screen{
        display: none;
    }
}
</style>