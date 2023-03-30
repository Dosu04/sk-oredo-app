<script>
	
	import Insta from '$lib/images/contact/instagram.png';
	import Twitter from '$lib/images/contact/twitter.png';
	import WhatsA from '$lib/images/contact/whatsapp.png';
	import Footer from '../../components/Footer.svelte';
	import Navbar from '../../components/Navbar.svelte';

</script>

	<style>
        .body{
            margin:3rem 0;
        }
		.form-container {
			max-width: 500px;
			margin: 0 auto;
			padding: 20px;

            font-family: Arial, sans-serif;
			
		}
		.form-group {
			margin-bottom: 3rem;
		}
		.form-group label {
			display: block;
			margin-bottom: 5px;
			font-weight: bold;
			color: black;
		}
		.form-group input[type=text],
		.form-group input[type=email],
		.form-group textarea {
			width: 100%;
			padding: 10px;
			border-radius: 5px;
			font-size: 16px;
			color: #333;
		}
		.form-group textarea {
			height: 150px;
		}
		.form-group button[type=submit] {
			display: block;
			width: 100%;
			padding: 10px;
			background-color: #fff;
			color: #AD7BE9;
			border: none;
			border-radius: 5px;
			font-size: 16px;
			font-weight: bold;
			cursor: pointer;
			transition: all 0.3s ease;
		}
		.form-group button[type=submit]:hover {
			background-color: #AD7BE9;
			color: #fff;
		}

		.social-media{
			text-align: center;
		}
		.social-media img{
			margin:0 4rem;
			width: 4rem;
		}
		@media screen and (max-width: 500px) {
			
		.social-media img{
			margin:0 1rem;
			width: 2rem;
		}
		}
		@media screen and (max-width: 500px) {
			.form-container {
				max-width: 100%;
				border-radius: 0;
			}
		}


	</style>
<Navbar/>

    <div class="body">
		<h2 style="text-align:center; color:#AD7BE9; margin:4rem">Get In Touch</h2>

	<div class="form-container">
		<form action="#" method="post">
			<div class="form-group">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" placeholder="Name" required>
			</div>
			<div class="form-group">
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" placeholder="Email" required>
			</div>
			<div class="form-group">
				<label for="message">Message:</label>
				<textarea id="message" name="message" placeholder="Message" required></textarea>
			</div>
			<div class="form-group">
				<button type="submit">Send Message</button>
			</div>
		</form>
	</div>
	<div class="social-media">
		<a href=""><img src={Twitter} alt=""></a>
		<a href=""><img src={WhatsA} alt=""></a>
		<a href=""><img src={Insta} alt=""></a>

	</div>

	</div>
<Footer/>

