<script>
	import mainHeader from '$lib/images/meeting-594091.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="The home page for the Pavlic Software Consulting Company" content="Pavlic Software Consulting Home Page" />
</svelte:head>


<section class="call-to-action" style="background-image: url({mainHeader})">
	<div class="call-to-action-overlay"></div>
	<div class="call-to-action-content">
		<h1>Welcome to Pavlic Software Consulting</h1>
		<p>We are a trusted partner for software consulting, development, and innovation.</p>
		<button>Request A Quote</button>
	</div>
</section>

<section class="introduction">
	<div class="introduction-content">
		<h2>What We Do</h2>
		<p>At Pavlic Software Consulting, we provide end-to-end software consulting services to help businesses streamline their processes, enhance productivity, and achieve their digital transformation goals. Our team of experienced consultants offers expertise in the following areas:</p>
		
		<ul>
			<li>Software Architecture and Design</li>
			<li>Custom Software Development</li>
			<li>Web and Mobile App Development</li>
			<li>Cloud Computing Solutions</li>
			<li>Data Analytics and Business Intelligence</li>
			<li>Quality Assurance and Testing</li>
		</ul>
		
		<h2>Why Choose Us</h2>
		<p>Partnering with Pavlic Software Consulting offers several advantages:</p>
		
		<ul>
			<li>Deep Industry Knowledge: Our consultants have a strong understanding of various industries, enabling us to deliver tailored solutions that address specific business challenges.</li>
			<li>Expert Team: Our highly skilled team consists of software architects, developers, and project managers who bring extensive experience and technical expertise to every project.</li>
			<li>Agile Approach: We follow an agile development methodology to ensure efficient project execution, rapid iterations, and seamless collaboration with our clients.</li>
			<li>Quality and Reliability: We are committed to delivering high-quality solutions that meet our clients' requirements and exceed their expectations. Our focus on quality ensures robust and scalable software applications.</li>
			<li>Client-Centric Approach: We prioritize client satisfaction and actively engage with our clients throughout the project lifecycle, ensuring transparency, regular communication, and timely delivery.</li>
		</ul>
		
		<h2>Contact Us</h2>
		<p>Ready to discuss your software consulting needs? Contact us today to schedule a consultation and learn how we can help your business thrive in the digital landscape.</p>
		
		<button>Contact Us</button>
	</div>
</section>

<section class="services">
</section>

<section class="project-highlights">
</section>

<section class="testimonials">
</section>

<section class="social-proof">
</section>

<section class="featured-content">
</section>

<section class="social-media-integration:">
</section>

<style>

	.call-to-action {
		position: sticky;
		width: 100%;
		height: 50rem;
		
		background-size: cover;
		background-position: top center;
		background-repeat: no-repeat;
		background-attachment: fixed;

		display: flex;
		justify-content: center;
		align-items: center;
	}
	
	.call-to-action-overlay {
		height: 100%;
		width: 100%;
		z-index: 1;
		background-color: var(--color-gray-dark);
		opacity: 0.75;
	}

	.call-to-action-content {
		position: absolute;
		height: 100%;
		width: 100%;
		z-index: 2;

		border-radius: 20px;

		color: var(--color-white);

		text-align: center;
		box-sizing: border-box;

		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center
	}

	.call-to-action-content h1 {
		margin-top: 1rem;
		margin-bottom: 1rem;
		font-size: 3rem;
	}
	.call-to-action-content p {
		margin-top: 1rem;
		margin-bottom: 1rem;
		font-size: 1.5rem;
	}
	.call-to-action-content button {
		margin-top: 1.5rem;
		font-size: 1.5rem;
		padding: 0.5rem 1rem;
		border-radius: 5px;
		border: none;
		background-color: var(--color-red);
		color: var(--color-white);
		cursor: pointer;
	}


	.introduction {
		width: 100%;
		background-color: var(--color-gray-dark);
		display: flex;
		flex-direction: column;
		align-items: center;
		box-sizing: border-box;	
	}
	.introduction .introduction-content {
		width: 100%;
        max-width: 1200px;
		margin: 0 auto;
		/* background-color: var(--color-gray-light); */
		color: var(--color-white);
	}
	
</style>