<script>
	import { page } from '$app/stores';
	const navs = [
		{ title: 'Home', href: '/loggedHome' },
		{ title: 'About', href: '/loggedAbout' },
		{ title: 'Donate', href: '/loggedDonate' },
		{ title: 'Programs', href: '/loggedPrograms' },
		{ title: 'Contact', href: '/loggedContact' }
	];

	$: routeID = $page.route.id;
	import Oredologo from '$lib/images/OREDO-nav-logo.png';
	import Usr from '$lib/images/nav/user.png';

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
			<ul class="navbar-nav ms-auto mb-2 mb-lg-0" style="margin-right: 10rem ;">
				<li class="nav-but" style="padding: 12px 20px 12px 0px;">
					<a href=""><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-bell-fill" viewBox="0 0 16 16">
						<path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z"/>
					  </svg></a>
				</li>
				<li class="nav-but" style="padding: 12px 0px;">
					<div class="dropdown">
						<img src={Usr} alt="" class="user dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false"/>
						
						<ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
						  <li><a class="dropdown-item" href="/account"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
							<path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
						  </svg> Account Settings</a></li>
						  <li><a class="dropdown-item" href="/donationHistory"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-coin" viewBox="0 0 16 16">
							<path d="M5.5 9.511c.076.954.83 1.697 2.182 1.785V12h.6v-.709c1.4-.098 2.218-.846 2.218-1.932 0-.987-.626-1.496-1.745-1.76l-.473-.112V5.57c.6.068.982.396 1.074.85h1.052c-.076-.919-.864-1.638-2.126-1.716V4h-.6v.719c-1.195.117-2.01.836-2.01 1.853 0 .9.606 1.472 1.613 1.707l.397.098v2.034c-.615-.093-1.022-.43-1.114-.9H5.5zm2.177-2.166c-.59-.137-.91-.416-.91-.836 0-.47.345-.822.915-.925v1.76h-.005zm.692 1.193c.717.166 1.048.435 1.048.91 0 .542-.412.914-1.135.982V8.518l.087.02z"/>
							<path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
							<path d="M8 13.5a5.5 5.5 0 1 1 0-11 5.5 5.5 0 0 1 0 11zm0 .5A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"/>
						  </svg> Donation History</a></li>
						  <li><a class="dropdown-item" href="/programHistory"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar" viewBox="0 0 16 16">
							<path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
						  </svg> Program History</a></li>
						  <li><a class="dropdown-item" href="/"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-box-arrow-right" viewBox="0 0 16 16">
							<path fill-rule="evenodd" d="M10 12.5a.5.5 0 0 1-.5.5h-8a.5.5 0 0 1-.5-.5v-9a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 .5.5v2a.5.5 0 0 0 1 0v-2A1.5 1.5 0 0 0 9.5 2h-8A1.5 1.5 0 0 0 0 3.5v9A1.5 1.5 0 0 0 1.5 14h8a1.5 1.5 0 0 0 1.5-1.5v-2a.5.5 0 0 0-1 0v2z"/>
							<path fill-rule="evenodd" d="M15.854 8.354a.5.5 0 0 0 0-.708l-3-3a.5.5 0 0 0-.708.708L14.293 7.5H5.5a.5.5 0 0 0 0 1h8.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3z"/>
						  </svg> Log Out</a></li>

						</ul>
					  </div>
				</li>
			</ul>
		</div>
	</div>
</nav>

<style>
	img.user{
		width: 2rem;
		border-radius: 100%;
		border: 1.5px solid black;
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
