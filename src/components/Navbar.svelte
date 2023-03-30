<script>
	import { page } from '$app/stores';
	const navs = [
		{ title: 'Home', href: '/' },
		{ title: 'About', href: '/about' },
		{ title: 'Donate', href: '/donate' },
		{ title: 'Programs', href: '/programs' },
		{ title: 'Contact', href: '/contact' }
	];

	$: routeID = $page.route.id;
	import Oredologo from '$lib/images/OREDO-nav-logo.png';
</script>

<!-- <nav>
    <div class="wrapper">
        <img src={Oredologo} alt="" width="120px">
        <ul>
            {#each navs as {title, href}}
            <li>
                <a {href} class:active={routeID == href}>{title}</a>
            </li>
            {/each}
        </ul>
    </div>
</nav> -->
<nav class="navbar navbar-expand-lg navbar-light ">
	<div class="container-fluid">
		<a class="navbar-brand" href="/"><img src={Oredologo} alt="" width="120px" /></a>
		<button
			class="navbar-toggler"
			type="button"
			data-bs-toggle="collapse"
			data-bs-target="#navbarSupportedContent"
			aria-controls="navbarSupportedContent"
			aria-expanded="false"
			aria-label="Toggle navigation"
			style="border: none"
		>
			<span class="navbar-toggler-icon" />
		</button>
		<div class="collapse navbar-collapse" id="navbarSupportedContent">
			
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
				{#each navs as { title, href }} 
					<li class="nav-item" style="padding-right:40px;">
						<a {href} class:active={routeID == href}>{title}</a>
					</li>
				{/each}
			</ul>
			<ul class="navbar-nav ms-auto mb-2 mb-lg-0">
				<li class="nav-but" style="padding: 12px 20px 12px 0px;">
					<a class="btn btn-primary reg-butt" href="/register">Register</a>
				</li>
				<li class="nav-but" style="padding: 12px 0px;">
					<a class="btn btn-outline-primary log-butt" href="/login">Log In</a>
				</li>
			</ul>
		</div>
	</div>
</nav>

<style>
	.reg-butt {
		background-color: #ad7be9;
		border: #ad7be9;
        color: white;
	}
	a.reg-butt:hover {
		background-color: #9b5fe3;
		border: #9b5fe3;
        color: white;

	}
	.log-butt {
		border: 1px solid #ad7be9;
		color: #ad7be9;
	}
	a.log-butt:hover {
		background-color: #ad7be9;
		border: 1px solid #ad7be9;
		color: white;
	}
	.active {
		color: #ad7be9;
	}
    div ul li a{
        text-decoration: none;
        color: black;
    }
    div ul li a:hover{
        color: #ad7be9;
    }
</style>
