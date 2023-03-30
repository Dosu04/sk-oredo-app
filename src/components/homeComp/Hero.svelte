<script>
	import HeroImage from '$lib/images/home/hero-image.jpg';
</script>


<div class="container-fluid main">
  <div class="row" >
    <div class="col-lg-6" style="background-color: white;color:black; padding-top:4rem;padding-left: 3rem; padding-right: 3rem; text-align:left; height:80%">
        <span style="color:#ad7be9">Helping communities
        </span>
      <h1 style="font-size: 3rem;"> 
        Make a difference <br> today by donating <br> your <span style="color:#ad7be9">Food</span> 
      </h1>
      <p style="margin-top: 3rem; color:gray">
        Your contributions can help provide essential resources like food, shelter, and medical care to people who are in need. Consider giving back to your community and helping those who need it most.
      </p>
      <div>

        <a class="btn btn-primary don-butt" style="margin-right:2rem; margin-bottom:2rem; " href="/donate">Make a Donation</a> 

        <a class="btn btn-outline-primary camp-butt" style=" margin-bottom:2rem" href="/startCampaign">Start a Campaign</a>
      </div>
    </div>
    <div class="col-lg-6 " style="background-color: #C0EEF2; padding: 0 0 ; height:80%; " >
      <img src={HeroImage} alt="" width="80%"  align="middle" style="margin: 3rem 0;">
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
	.camp-butt {
		border: 1px solid #ad7be9;
        color: #ad7be9;
		
	}
	a.camp-butt:hover {
		background-color: #ad7be9;
		border: 1px solid #ad7be9;
		color: white;
	}
</style>