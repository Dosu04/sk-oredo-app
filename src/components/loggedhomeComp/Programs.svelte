<script>
	import FoodImg from '$lib/images/home/programs/food.png';
	import HealthImg from '$lib/images/home/programs/health.png';
	import EduImg from '$lib/images/home/programs/education.png';
	import HouseImg from '$lib/images/home/programs/house.png';
</script>

<div class="container-fluid" style="color:black; ">
	<div class="row">
		<div class="col-lg-6" style="padding: 8rem 3rem 0 3rem;  ">
			<span style="color:#ad7be9; ">PROGRAMS</span>

			<p style="padding-top: 3.5rem; font-size:1.4rem">
				We have several donation programs for you. You can donate according to the categories
				provided.
			</p>
			<p style="color:gray; margin-top:5rem">
				Oredo offers a variety of donation programs that cater to different causes, allowing donors
				to choose a program that aligns with their values and philanthropic goals. Each program is
				designed to address specific issues within the category, and donors can contribute to the
				program of their choice based on their interests and capacity.
			</p>
			<div style="padding:5rem 0 3rem 0">
				<a href="/loggedPrograms" style="color:#ad7be9; ">See all Programs</a><span
					style="color:#ad7be9; font-size:1.3rem"
				>
					&nbsp;&nbsp;→</span
				>
			</div>
		</div>

		<div class="col-lg-6" style="padding: 8rem 3rem 0 3rem;  ">
			<div class="row">
				<div class="col-lg-6">
					<img src={HealthImg} alt="" />
					<br />

					<span style="font-size:1.2rem; font-weight:700 ">Health Care</span>

					<p style="padding-top: 2.5rem; font-size:0.9rem">
						Help people in need of medications, treatments or surgeries
					</p>
					<div style="padding:1rem 0 4rem 0">
						<a
							class="btn btn-primary prog-butt"
							style="margin-right:2rem; margin-bottom:2rem"
							href="/loggedDonate">Donate</a
						>
					</div>
				</div>
				<div class="col-lg-6">
					<img src={FoodImg} alt="" />
					<br />

					<span style="font-size:1.2rem; font-weight:700 ">Food</span>

					<p style="padding-top: 2.5rem; font-size:0.9rem">
						Provide them with food, food supplies, or other survival aid
					</p>
					<div style="padding:1rem 0 4rem 0">
						<a
							class="btn btn-primary prog-butt"
							style="margin-right:2rem; margin-bottom:2rem"
							href="/loggedDonate">Donate</a
						>
					</div>
				</div>
			</div>
			<div class="row">
				<div class="col-lg-6">
					<img src={EduImg} alt="" />
					<br />

					<span style="font-size:1.2rem; font-weight:700 ">Education</span>

					<p style="padding-top: 2.5rem; font-size:0.9rem">
						Help people go to school or provide them with learning supplies
					</p>
					<div style="padding:1rem 0 4rem 0">
						<a
							class="btn btn-primary prog-butt"
							style="margin-right:2rem; margin-bottom:2rem"
							href="/loggedDonate">Donate</a
						>
					</div>
				</div>
				<div class="col-lg-6">
					<img src={HouseImg} alt="" />
					<br />
					<span style="font-size:1.2rem; font-weight:700 ">Housing</span>

					<p style="padding-top: 2.5rem; font-size:0.9rem">
						Provide people with a place to live <br /><br />
					</p>
					<div style="padding:1rem 0 4rem 0">
						<a
							class="btn btn-primary prog-butt"
							style="margin-right:2rem; margin-bottom:2rem"
							href="/loggedDonate">Donate</a
						>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	.prog-butt {
		background-color: #ad7be9;
		border: #ad7be9;
		color: white;
	}
	a.prog-butt:hover {
		background-color: #9b5fe3;
		border: #9b5fe3;
		color: white;
	}
	img {
		width: 15%;
		margin-bottom: 1.5rem;
	}
</style>
