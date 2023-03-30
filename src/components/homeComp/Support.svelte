<script>
	import SupportImg1 from '$lib/images/home/support-image1.jpg';
	import SupportImg2 from '$lib/images/home/support-image2.jpg';
	import SupportImg3 from '$lib/images/home/support-image3.jpg';
	import SupportImg2SM from '$lib/images/home/support-image2-sm.jpg';
	import SupportImg1SM from '$lib/images/home/support-image1-sm.png';
</script>

<div class="container-fluid lg-support" style="color:black; padding-bottom:7rem">
	<div class="row">
		<div class="col-lg-6" style="padding: 4rem 3rem 0 3rem;  ">
			<span style="color:#ad7be9; ">SUPPORT A COMMUNITY</span>

			<p style="padding-top: 3.5rem; font-size:1.1rem">
				Volunteer your time, skills and contribute to the betterment of individuals or causes.
				Donate resources to communities in need.
			</p>
			<div style="padding:1rem 0 3rem 0">
				<a href="/about" style="color:#ad7be9; ">Learn more</a><span
					style="color:#ad7be9; font-size:1.3rem"
				>
					&nbsp;&nbsp;→</span
				>
			</div>
			<div class="container ">
				<div class="row">
					<div class="col-lg-6">
						<img src={SupportImg1} width="95%" alt="" />
					</div>
					<div class="col-lg-6">
						<img src={SupportImg2} alt="" width="95%" />
					</div>
				</div>
			</div>
		</div>
		<div class="col-lg-6" style="padding:0; display:grid; text-align:left">
			<img src={SupportImg3} width="60%" alt="" style="place-self:center" />
		</div>
	</div>
</div>

<div class="container-fluid sm-support" style="color:black; padding-bottom:7rem">
	<div class="row">
		<div class="col-lg-6" style="padding: 4rem 3rem 0 3rem;  ">
			<span style="color:#ad7be9; ">SUPPORT A COMMUNITY</span>

			<p style="padding-top: 3.5rem; font-size:1.1rem">
				Volunteer your time, skills and contribute to the betterment of individuals or causes.
				Donate resources to communities in need.
			</p>
			<div style="padding:1rem 0 3rem 0">
				<a href="/about" style="color:#ad7be9; ">Learn more</a><span
					style="color:#ad7be9; font-size:1.3rem"
				>
					&nbsp;&nbsp;→</span
				>
			</div>
			<div class="container ">
				<div class="row">
						<img class="stubborn" src={SupportImg1SM} width="120%" alt="" />

                   

				</div>
			</div>
		</div>
		<div class="col-lg-6" style="padding:0 3rem 0 3rem; display:grid; text-align:left">
			<img src={SupportImg2SM} width="85%" alt="" style="place-self:center" />
		</div>
	</div>
</div>

<style>
	img {
		padding-bottom: 1rem;
	}
    .stubborn{
        display: inline;
    }
       
@media (min-width: 900px) {
  .sm-support {
    display: none;
   
  }
}

@media (max-width: 900px) {
  .lg-support {
    display: none;
   
  }
}
</style>
