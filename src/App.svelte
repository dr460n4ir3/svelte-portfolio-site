<script>
	export let name;
	let src = 'images/error-404-logo.png';
</script>

<main>
	<!-- create a navbar link to an about us page -->
	<a href="about-us.html">About</a>
	<a href="contact-us.html">Contact</a>
	<a href="services.html">Services</a>
	<a href="portfolio.html">Portfolio</a>
	<a href="index.html">Home</a>

	<h1>{name}</h1>
	<!-- render an image from this project folder -->
	<img {src} alt="Our complany logo"/>
	

	<h2>Welcome to Error-404 Web Development Agency LLC</h2>
	<h2><strong>Currently Serving the DC, Maryland & Virgina Areas</strong></h2>
	<p>We are a full-stack web development agency specializing in the following services: Business Consulting, Branding/Logo Design, Developing Marketing Plans, Website Design & Development, App Design & Development, and Blockchain Development.</p>
	<p>Visit our <a href="https://twitter.com/e404dev">Twitter Page</a> here!</p>
	<p>Visit our <a href="https://www.facebook.com/error404.dev">Facebook Page</a> here!</p>
	<p>Visit our <a href="https://www.instagram.com/error_404.dev/">Instagram Page</a> here!</p>
	<p>Visit our <a href="https://www.linkedin.com/company/81305477/">LinkedIn Page</a> here!</p>
	
	<!-- create a video player for youtube -->


	<iframe width="560" height="315" src="https://www.youtube.com/embed/b8eXfV5BO98" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

	<!-- create a new row -->
	<br>
	<br>
	<br>
	<br>

	<h2>Articles</h2>

	<!-- create a link for articles that displays a thumbnail -->
	<a href="https://www.youtube.com/embed/b8eXfV5BO98">
		<img src="https://i.ytimg.com/vi/b8eXfV5BO98/maxresdefault.jpg" alt="Error-404 Web Development Agency LLC" width="560" height="315"></a>

	<a href="https://www.youtube.com/embed/b8eXfV5BO98">
		<img src="https://i.ytimg.com/vi/b8eXfV5BO98/maxresdefault.jpg" alt="Error-404 Web Development Agency LLC" width="560" height="315"></a>

	<br />

	<a href="https://www.youtube.com/embed/b8eXfV5BO98">
		<img src="https://i.ytimg.com/vi/b8eXfV5BO98/maxresdefault.jpg" alt="Error-404 Web Development Agency LLC" width="560" height="315"></a>

	<a href="https://www.youtube.com/embed/b8eXfV5BO98">
		<img src="https://i.ytimg.com/vi/b8eXfV5BO98/maxresdefault.jpg" alt="Error-404 Web Development Agency LLC" width="560" height="315"></a>

	<br />
	<br />
	<br />
	<br />

	<!-- create a contact form using sql -->
	

</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background-color: #ff3e00;
	}

	h1 {
		color: lime;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>