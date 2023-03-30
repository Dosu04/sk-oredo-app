<script>
	import JoinImage from '$lib/images/home/join-image.png';
	import JoinImage2 from '$lib/images/home/join-image2.png';

</script>

<div class="container-fluid joindiv" style="color:white; background-color: #AD7BE9 ">
    <div class="row">
        <div class="col-lg-6" style="padding: 4rem 3rem 0 3rem;  " >
            <span style="font-size:2rem; font-weight:700 " >Join Oredo</span>
            <p style="padding-top: 3.5rem; font-size:1.1rem">Make a positive impact on the world around you by giving your time and skills. Help support important causes, build connections with your community, and gain valuable experience and skills.</p> 
            <img class="sm-img" style="padding:3rem"src={JoinImage2} alt="">
           
            <div style="padding:1rem 0 4rem 0" >
                <a class="btn btn-primary join-butt" style="" href="/loggedPrograms">Become a Volunteer</a> 
            </div>
        </div>
        
        <div class="col-lg-6" style="padding:0; text-align:right">
            <img class="lg-img" src={JoinImage} style="max-width:100%" alt="" >
        </div>
    </div>
</div>

<style>
    .join-butt {
		background-color: #E9F8F9;
		border: #E9F8F9;
        color: #AD7BE9;
        margin-right:2rem; margin-bottom:2rem;
	}
	a.join-butt:hover {
		background-color: #9b5fe3;
		border: #9b5fe3;
        color: #E9F8F9;

	}
    @media (max-width: 900px) {
  img.lg-img {
    display: none;
    
  }
  .joindiv{
    text-align: center;
  }
  .join-butt {
        margin: 0;
	}
}
@media (min-width: 900px) {
  img.sm-img {
    display: none;
   
  }
}
</style>