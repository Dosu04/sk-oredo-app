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
                        ">Reset Password</h3>
                        <br><br>
                        <div class="inputs">
                            
                                <div class="mb-3">
                                    <label for="">New Password</label>
                                  <input type="password" placeholder="Password" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                                </div>
                                <div class="mb-3">
                                    <label for="">Confirm New Password</label>
                                  <input type="password" placeholder="Password" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                                </div>
                                <br>
                               
    
                        </div>
                        
                       <a href="/login"><input type="submit" class="btn btn-primary inputs" value="Reset"/></a> 
                        <br><br>
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
                    ">Reset Password</h6>
                    <br><br>
                        <div class="inputs2">
                          
                            <div class="mb-3">
                                <label for="">New Password</label>
                              <input type="password" placeholder="Passowrd" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                            </div>
                            <div class="mb-3">
                                <label for="">Confirm New Password</label>
                              <input type="password" placeholder="Password" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                            </div>
                                <br>
                             
                                
    
                        </div>
                        
                        
                        <a href="/login"><input type="submit" class="btn btn-primary inputs2" value="Reset" style="width:100%"/></a>
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