<script>
	import SubscribeImg from '$lib/images/home/subscribe-image.png';
	import { subscribe } from 'svelte/internal';
</script>

<div class="image-container ">
    <img style="width:100%; height:20rem" src={SubscribeImg} alt="">
    <div class="image-overlay container" >
        <h2>Be a part of our Inner Circle</h2>
        <p style="padding: 1.5rem 0 2.5rem 0;">Stay up-to-date on our latest volunteer opportunities and charitable events by subscribing to Oredo's newsletter today!</p>
        <div class="input-group mb-3 container" style="width: 20rem; height:4rem">
            <input  type="text" class="form-control " placeholder="Enter Email Address" aria-label="Enter Email Address" aria-describedby="button-addon2">
            <button class="btn btn-outline-primary sub-butt" type="button" id="button-addon2">Subscribe</button>
        </div>
        

    </div>
  </div>
  

<style>
    .image-container {
  position: relative;

}

.image-overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  color: black;
text-align: center;
padding: 2rem;
}

.sub-butt {
		background-color: #ad7be9;
		border: #ad7be9;
		color: white;
	}
	button.sub-butt:hover {
		background-color: #9b5fe3;
		border: #9b5fe3;
		color: white;
	}

</style>