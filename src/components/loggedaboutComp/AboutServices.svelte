<script>
	import Services1 from '$lib/images/about/services (1).png';
	import Services2 from '$lib/images/about/services (2).png';
	import Services3 from '$lib/images/about/services (3).png';
	import Services4 from '$lib/images/about/services (4).png';
</script>

<div class="container-fluid lg-body">
	<div class="row ">
		<h4
			style="color: #AD7BE9
        ;"
		>
			SERVICES
		</h4>
	</div>
	<div class="row " style="margin-bottom: 2rem;">
		<div class="col-lg-6 " style="">
			<div class="boxCont">
				<img src={Services1} alt="" style="padding: 0 2rem 2rem 0; width:6rem" />
				<h5>Donation Processing</h5>
				<p>
					A platform for individuals and organizations to donate money to various charitable causes.
				</p>
			</div>
		</div>

		<div class="col-lg-6 " style="padding:0; display:grid; place-items:end">
			<div class="boxContR">
				<img src={Services4} alt="" style="padding: 0 2rem 2rem 0; width:6rem" />

				<h5>Volunteer Coordination</h5>
				<p>
					A platform for individuals and organizations to donate money to various charitable causes.
				</p>
			</div>
		</div>
	</div>
	<div class="row ">
		<div class="col-lg-6 ">
			<div class="boxCont">
				<img src={Services3} alt="" style="padding: 0 2rem 2rem 0; width:6rem" />

				<h5>Fundraising Support</h5>
				<p>Provide support to organizations looking to raise funds for donation/giving causes.</p>
			</div>
		</div>

		<div class="col-lg-6 " style="padding:0; display:grid; place-items:end">
			<div class="boxContR">
				<img src={Services2} alt="" style="padding: 0 2rem 2rem 0; width:6rem" />

				<h5>Corporate Social Responsibility (CSR) Programs</h5>
				<p>Give back to the communities and support charitable causes. <br /><br /></p>
			</div>
		</div>
	</div>
</div>



<div class="container-fluid sm-body">
	<div class="row ">
		<h4
			style="color: #AD7BE9
        ;"
		>
			SERVICES
		</h4>
	</div>
	<div class="row " style="text-align:center">
		<div class="col-lg-6 container" style="padding:2rem; ">
            <div style="background-color:#c0eef2; border-radius:10px;">
                <div class="boxContSM">
                    <img src={Services1} alt="" style="padding: 0.8rem 0 2rem 0; width:6rem" />
                    <h5>Donation Processing</h5>
                    <p>
                        A platform for individuals and organizations to donate money to various charitable causes.
                    </p>
                </div>

            </div>
        </div>
        <div class="col-lg-6 container" style="padding:2rem; ">
            <div style="background-color:#c0eef2; border-radius:10px;">
                <div class="boxContSM">
                    <img src={Services4} alt="" style="padding: 0.8rem 0 2rem 0; width:6rem" />
                    <h5>Donation Processing</h5>
                    <p>
                        A platform for individuals and organizations to donate money to various charitable causes.
                    </p>
                </div>

            </div>
        </div>
	</div>
	<div class="row " style="text-align:center">
		<div class="col-lg-6 container" style="padding:2rem; ">
            <div style="background-color:#c0eef2; border-radius:10px;">
                <div class="boxContSM">
                    <img src={Services3} alt="" style="padding: 0.8rem 0 2rem 0; width:6rem" />
                    <h5>Donation Processing</h5>
                    <p>
                        A platform for individuals and organizations to donate money to various charitable causes.
                    </p>
                </div>

            </div>
        </div>
        <div class="col-lg-6 container" style="padding:2rem; ">
            <div style="background-color:#c0eef2; border-radius:10px;">
                <div class="boxContSM">
                    <img src={Services2} alt="" style="padding: 0.8rem 0 2rem 0; width:6rem" />
                    <h5>Donation Processing</h5>
                    <p>
                        A platform for individuals and organizations to donate money to various charitable causes.
                    </p>
                </div>

            </div>
        </div>
	</div>
</div>


<style>
	.lg-body {
		margin-bottom: 4rem;
		padding: 0;
	}
	h4 {
		padding: 0 3rem 0 3rem;

		margin-bottom: 2.5rem;
	}
	h5 {
		margin-bottom: 3rem;
	}
	p {
		margin-bottom: 1.5rem;
	}
	.boxCont {
		background-color: #c0eef2;
		width: 90%;
		padding: 2rem;
	}
	.boxContR {
		background-color: #c0eef2;
		width: 90%;
		padding: 2rem;
	}
    .boxContSM {
		padding: 2rem;
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
