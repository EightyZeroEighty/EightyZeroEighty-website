<script>
	import '../app.css';
	let { children } = $props();
</script>

<!-- Navigation -->
<nav class="bg-purple-900 text-white">
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<div class="flex h-16 items-center justify-between">
			<div class="flex-shrink-0">
				<h1 class="text-2xl font-bold">Eighty Zero Eighty</h1>
			</div>
			<div class="hidden md:block">
				<div class="ml-10 flex items-baseline space-x-4">
					<a href="/" class="rounded-md px-3 py-2 text-sm font-medium hover:bg-purple-800">Home</a>
					<a href="/services" class="rounded-md px-3 py-2 text-sm font-medium hover:bg-purple-800"
						>Services</a
					>
					<a href="/portfolio" class="rounded-md px-3 py-2 text-sm font-medium hover:bg-purple-800"
						>Portfolio</a
					>
					<a href="#contact" class="rounded-md px-3 py-2 text-sm font-medium hover:bg-purple-800"
						>Contact</a
					>
				</div>
			</div>
		</div>
	</div>
</nav>

<div class="bg-gray-50">
	{@render children()}
</div>

<!-- Footer -->
<footer class="bg-purple-800 text-purple-100">
	<div class="mx-auto max-w-7xl px-4 py-12 sm:px-6 lg:px-8">
		<div class="flex items-center justify-between">
			<div>
				<h3 class="text-xl font-bold">Eighty Zero Eighty</h3>
				<p class="mt-2">Building the web of tomorrow</p>
			</div>
			<div class="flex space-x-6">
				<a href="#" class="hover:text-white">Twitter</a>
				<a href="#" class="hover:text-white">LinkedIn</a>
				<a href="#" class="hover:text-white">GitHub</a>
			</div>
		</div>
		<div class="mt-8 border-t border-purple-700 pt-8 text-sm">
			<p>&copy; 2024 Eighty Zero Eighty. All rights reserved.</p>
		</div>
	</div>
</footer>
