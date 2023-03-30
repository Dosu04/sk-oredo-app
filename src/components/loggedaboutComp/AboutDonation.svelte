<script>
	import L from '$lib/images/about/imageL.png'
	import R from '$lib/images/about/imageR.png'
	import D from '$lib/images/about/D.png'
</script>

<div class="container-fluid lg-body">
    <div class="row">
        <div class="col-lg-4" style="padding: 3rem;">
            <img src={L} style="width:20rem" alt="">
        </div>
        <div class="col-lg-4" style="padding: 3rem; text-align:center ">
            <h4 style="margin-top: 2.5rem;">Make a donation today and</h4>
            <h4 style="color:#AD7BE9; padding:0.5rem 0">change someone's life</h4>
        <a class="btn btn-primary don-butt" style=" margin-bottom:2rem; " href="/loggedDonation">Make a Donation</a> 

        </div>
        <div class="col-lg-4" style="padding: 3rem; text-align:right">
            <img src={R} style="width:20rem" alt="">
        </div>
    </div>
</div>



<div class="container-fluid sm-body" >
    <div class="row">
        <img src={D} alt="" style="padding:2rem">
    </div>
    <div class="row">
        <div class="col-lg-12" style="text-align:center">
            <h4 style="margin-top: 2.5rem;">Make a donation today and</h4>
            <h4 style="color:#AD7BE9; padding:0.5rem 0">change someone's life</h4>
        <a class="btn btn-primary don-butt" style=" margin-bottom:2rem; " href="/loggedDonation">Make a Donation</a> 
    
        </div>
    
    </div>
</div>


<style>
   .don-butt {
		background-color: #ad7be9;
		border: #ad7be9;
        color: white;
	}
	a.don-butt:hover {
		background-color: #9b5fe3;
		border: #9b5fe3;
        color: white;

	}
    .lg-body{
        padding: 0;
    }
    .sm-body{
        margin:3rem 0;
    }
	@media (max-width: 900px) {
		.lg-body {
			display: none;
		}
	
	}
	@media (min-width: 900px) {
		.sm-body {
			display: none;
		}
	}
</style>
