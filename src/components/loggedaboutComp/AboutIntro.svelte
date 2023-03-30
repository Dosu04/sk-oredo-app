<script>
	import HAboutImage from '$lib/images/about/hAbout-image.jpg';
	import HAboutImageSM from '$lib/images/about/hAbout-image-sm.jpg';
</script>

<div class="container-fluid main">
    <div class="row">
        <div class="col-lg-6" style="padding: 4rem 3rem 0 3rem;">
            <h3>ABOUT OREDO</h3>
            <p>
                Oredo is a donation platform that connects individuals, communities, and organizations in need with generous donors and volunteers who want to make a positive impact. With a mission to alleviate poverty, hunger, and inequality, Oredo provides a safe and user-friendly platform for people to donate resources and time to those who need them the most. As a platform that fosters friendship and empathy, Oredo brings hope and tangible change to people's lives, creating a more equitable and sustainable world for everyone.
            </p>
            <p>
                Oredo is not just a platform that connects donors and recipients, but it also fosters a culture of compassion, inclusivity, and mutual support. Through its interactive features and resources, we creates a sense of community where individuals and organizations can collaborate and share their expertise to maximize the impact of their contributions. We also ensures transparency and accountability in all its activities, providing regular updates and reports on how the donations are being used. By promoting transparency and collaboration, we seeks to build trust and confidence among donors, recipients, and other stakeholders, creating a sustainable and scalable model for social change. With its commitment to social justice and human dignity, Oredo is a beacon of hope for those who seek to make a positive impact on the world.
            </p>
        </div>
        <div class="col-lg-6 image-cont" style="text-align: center; padding: 0 3rem 0 3rem;">
            <img class="lg-img" src={HAboutImage} width="55%" alt="">
            <img class="sm-img" src={HAboutImageSM} width="80%" alt="">
        </div>
    </div>
</div>

<style>
    h3{
        color: #ad7be9;
        margin-bottom: 2rem;
    }
    p{
        margin-bottom: 1.5rem;
    }
    .image-cont{
        display: grid;
        place-items: center;
    }
    
@media (min-width: 900px) {
  img.sm-img {
    display: none;
   
  }
}

@media (max-width: 900px) {
  img.lg-img {
    display: none;
   
  }
}
</style>