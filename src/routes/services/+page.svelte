<script>
	/** @type {{ data: import('./$types').PageData }} */
	let { data } = $props();
</script>

<!-- Services Header -->
<div class="bg-purple-700 py-16">
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<h2 class="text-center text-4xl font-bold text-white">Our Services</h2>
		<p class="mx-auto mt-4 max-w-3xl text-center text-xl text-purple-100">
			From simple landing pages to complex web applications, we provide end-to-end web development
			solutions tailored to your needs.
		</p>
	</div>
</div>

<!-- Main Services Section -->
<div class="mx-auto max-w-7xl px-4 py-16 sm:px-6 lg:px-8">
	<!-- Landing Pages -->
	<div class="mb-20">
		<div class="lg:flex lg:items-center lg:justify-between">
			<div class="lg:w-1/2 lg:pr-12">
				<h3 class="text-3xl font-bold text-purple-900">Landing Pages</h3>
				<p class="mt-4 text-lg text-gray-600">
					Convert visitors into customers with high-performance landing pages designed to drive
					action.
				</p>
				<ul class="mt-6 space-y-4">
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Optimized for conversions</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Mobile-first design</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">A/B testing ready</span>
					</li>
				</ul>
				<div class="mt-8">
					<a
						href="#contact"
						class="inline-flex items-center rounded-md border border-transparent bg-purple-600 px-6 py-3 text-base font-medium text-white hover:bg-purple-700"
					>
						Get Started
					</a>
				</div>
			</div>
			<div class="mt-10 lg:mt-0 lg:w-1/2">
				<img
					src="/api/placeholder/600/400"
					alt="Landing Page Example"
					class="rounded-lg shadow-lg"
				/>
			</div>
		</div>
	</div>

	<!-- Static Websites -->
	<div class="mb-20">
		<div class="flex-row-reverse lg:flex lg:items-center lg:justify-between">
			<div class="lg:w-1/2 lg:pl-12">
				<h3 class="text-3xl font-bold text-purple-900">Static Websites</h3>
				<p class="mt-4 text-lg text-gray-600">
					Fast, secure, and maintainable websites perfect for businesses and organizations.
				</p>
				<ul class="mt-6 space-y-4">
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Blazing fast performance</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">SEO optimized</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Easy content updates</span>
					</li>
				</ul>
				<div class="mt-8">
					<a
						href="#contact"
						class="inline-flex items-center rounded-md border border-transparent bg-purple-600 px-6 py-3 text-base font-medium text-white hover:bg-purple-700"
					>
						Learn More
					</a>
				</div>
			</div>
			<div class="mt-10 lg:mt-0 lg:w-1/2">
				<img
					src="/api/placeholder/600/400"
					alt="Static Website Example"
					class="rounded-lg shadow-lg"
				/>
			</div>
		</div>
	</div>

	<!-- Web Applications -->
	<div class="mb-20">
		<div class="lg:flex lg:items-center lg:justify-between">
			<div class="lg:w-1/2 lg:pr-12">
				<h3 class="text-3xl font-bold text-purple-900">Web Applications</h3>
				<p class="mt-4 text-lg text-gray-600">
					Custom web applications that solve complex business problems and streamline operations.
				</p>
				<ul class="mt-6 space-y-4">
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Scalable architecture</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Real-time features</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Secure authentication</span>
					</li>
				</ul>
				<div class="mt-8">
					<a
						href="#contact"
						class="inline-flex items-center rounded-md border border-transparent bg-purple-600 px-6 py-3 text-base font-medium text-white hover:bg-purple-700"
					>
						Discuss Your Project
					</a>
				</div>
			</div>
			<div class="mt-10 lg:mt-0 lg:w-1/2">
				<img
					src="/api/placeholder/600/400"
					alt="Web Application Example"
					class="rounded-lg shadow-lg"
				/>
			</div>
		</div>
	</div>
	<!-- E-Commerce Solutions -->
	<div class="mb-20">
		<div class="flex-row-reverse lg:flex lg:items-center lg:justify-between">
			<div class="lg:w-1/2 lg:pl-12">
				<h3 class="text-3xl font-bold text-purple-900">E-Commerce Solutions</h3>
				<p class="mt-4 text-lg text-gray-600">
					Build your online store with powerful e-commerce solutions that drive sales.
				</p>
				<ul class="mt-6 space-y-4">
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Secure payment processing</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Inventory management</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Shopping cart optimization</span>
					</li>
				</ul>
				<div class="mt-8">
					<a
						href="#contact"
						class="inline-flex items-center rounded-md border border-transparent bg-purple-600 px-6 py-3 text-base font-medium text-white hover:bg-purple-700"
					>
						Start Selling Online
					</a>
				</div>
			</div>
			<div class="mt-10 lg:mt-0 lg:w-1/2">
				<img src="/api/placeholder/600/400" alt="E-Commerce Example" class="rounded-lg shadow-lg" />
			</div>
		</div>
	</div>

	<!-- API Development -->
	<div class="mb-20">
		<div class="lg:flex lg:items-center lg:justify-between">
			<div class="lg:w-1/2 lg:pr-12">
				<h3 class="text-3xl font-bold text-purple-900">API Development</h3>
				<p class="mt-4 text-lg text-gray-600">
					Custom API solutions that connect your systems and power your applications.
				</p>
				<ul class="mt-6 space-y-4">
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">RESTful API design</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Third-party integrations</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">API documentation</span>
					</li>
				</ul>
				<div class="mt-8">
					<a
						href="#contact"
						class="inline-flex items-center rounded-md border border-transparent bg-purple-600 px-6 py-3 text-base font-medium text-white hover:bg-purple-700"
					>
						Discuss API Needs
					</a>
				</div>
			</div>
			<div class="mt-10 lg:mt-0 lg:w-1/2">
				<img
					src="/api/placeholder/600/400"
					alt="API Development Example"
					class="rounded-lg shadow-lg"
				/>
			</div>
		</div>
	</div>

	<!-- Maintenance & Support -->
	<div class="mb-20">
		<div class="flex-row-reverse lg:flex lg:items-center lg:justify-between">
			<div class="lg:w-1/2 lg:pl-12">
				<h3 class="text-3xl font-bold text-purple-900">Maintenance & Support</h3>
				<p class="mt-4 text-lg text-gray-600">
					Keep your web presence running smoothly with our comprehensive maintenance services.
				</p>
				<ul class="mt-6 space-y-4">
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">24/7 monitoring</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Regular updates & backups</span>
					</li>
					<li class="flex items-center">
						<svg class="h-5 w-5 text-purple-500" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
								clip-rule="evenodd"
							/>
						</svg>
						<span class="ml-2 text-gray-600">Security patches</span>
					</li>
				</ul>
				<div class="mt-8">
					<a
						href="#contact"
						class="inline-flex items-center rounded-md border border-transparent bg-purple-600 px-6 py-3 text-base font-medium text-white hover:bg-purple-700"
					>
						View Support Plans
					</a>
				</div>
			</div>
			<div class="mt-10 lg:mt-0 lg:w-1/2">
				<img
					src="/api/placeholder/600/400"
					alt="Maintenance Support Example"
					class="rounded-lg shadow-lg"
				/>
			</div>
		</div>
	</div>

	<!-- Contact CTA Section -->
	<div class="mt-20 rounded-lg bg-purple-900 shadow-xl">
		<div
			class="mx-auto max-w-7xl px-4 py-12 sm:px-6 lg:flex lg:items-center lg:justify-between lg:px-8 lg:py-16"
		>
			<h2 class="text-3xl font-extrabold tracking-tight text-white sm:text-4xl">
				<span class="block">Ready to bring your project to life?</span>
				<span class="block text-purple-300">Let's discuss how we can help.</span>
			</h2>
			<div class="mt-8 flex lg:mt-0 lg:flex-shrink-0">
				<div class="inline-flex rounded-md shadow">
					<a
						href="#contact"
						class="inline-flex items-center justify-center rounded-md border border-transparent bg-white px-5 py-3 text-base font-medium text-purple-900 hover:bg-purple-50"
					>
						Get Started
					</a>
				</div>
			</div>
		</div>
	</div>
</div>
