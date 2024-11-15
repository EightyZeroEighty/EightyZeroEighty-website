<script>
    /** @type {{ data: import('./$types').PageData }} */
    let { data } = $props();
</script>

    <!-- Portfolio Header -->
    <div class="bg-purple-700 py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-white text-center">Our Work</h2>
            <p class="mt-4 text-xl text-purple-100 text-center max-w-3xl mx-auto">
                Explore our collection of successful projects that showcase our expertise in web development and design.
            </p>
        </div>
    </div>

    <!-- Portfolio Filters -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <div class="flex flex-wrap justify-center gap-4">
            <button class="px-4 py-2 bg-purple-900 text-white rounded-md hover:bg-purple-800">All Projects</button>
            <button class="px-4 py-2 bg-purple-100 text-purple-900 rounded-md hover:bg-purple-200">E-Commerce</button>
            <button class="px-4 py-2 bg-purple-100 text-purple-900 rounded-md hover:bg-purple-200">Web Apps</button>
            <button class="px-4 py-2 bg-purple-100 text-purple-900 rounded-md hover:bg-purple-200">Landing Pages</button>
        </div>
    </div>

    <!-- Portfolio Grid -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Project 1 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="/api/placeholder/400/300" alt="E-commerce Project" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-sm text-purple-600 font-medium">E-Commerce</span>
                    <h3 class="text-xl font-bold text-gray-900 mt-2">Boutique Fashion Store</h3>
                    <p class="mt-2 text-gray-600">A modern e-commerce platform with integrated payment processing and inventory management.</p>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">React</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Node.js</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Stripe</span>
                    </div>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="/api/placeholder/400/300" alt="Web App Project" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-sm text-purple-600 font-medium">Web App</span>
                    <h3 class="text-xl font-bold text-gray-900 mt-2">Task Management Platform</h3>
                    <p class="mt-2 text-gray-600">A collaborative task management solution with real-time updates and team features.</p>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Vue.js</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Firebase</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Tailwind</span>
                    </div>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="/api/placeholder/400/300" alt="Landing Page Project" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-sm text-purple-600 font-medium">Landing Page</span>
                    <h3 class="text-xl font-bold text-gray-900 mt-2">SaaS Product Launch</h3>
                    <p class="mt-2 text-gray-600">A high-converting landing page with animated sections and newsletter integration.</p>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Next.js</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">GSAP</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Vercel</span>
                    </div>
                </div>
            </div>

            <!-- Project 4 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="/api/placeholder/400/300" alt="Web App Project" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-sm text-purple-600 font-medium">Web App</span>
                    <h3 class="text-xl font-bold text-gray-900 mt-2">Analytics Dashboard</h3>
                    <p class="mt-2 text-gray-600">A comprehensive analytics platform with interactive charts and data visualization.</p>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">React</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">D3.js</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">AWS</span>
                    </div>
                </div>
            </div>

            <!-- Project 5 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="/api/placeholder/400/300" alt="E-commerce Project" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-sm text-purple-600 font-medium">E-Commerce</span>
                    <h3 class="text-xl font-bold text-gray-900 mt-2">Digital Marketplace</h3>
                    <p class="mt-2 text-gray-600">A marketplace platform for digital products with secure download delivery.</p>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Laravel</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">MySQL</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Alpine.js</span>
                    </div>
                </div>
            </div>

            <!-- Project 6 -->
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="/api/placeholder/400/300" alt="Landing Page Project" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-sm text-purple-600 font-medium">Landing Page</span>
                    <h3 class="text-xl font-bold text-gray-900 mt-2">Mobile App Launch</h3>
                    <p class="mt-2 text-gray-600">A mobile app landing page with interactive features and download tracking.</p>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Gatsby</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">GraphQL</span>
                        <span class="px-2 py-1 bg-purple-100 text-purple-800 rounded-md text-sm">Netlify</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Project Details Modal (Hidden by default) -->
    <div class="hidden fixed inset-0 bg-gray-900 bg-opacity-50 flex items-center justify-center">
        <div class="bg-white rounded-lg max-w-4xl w-full mx-4">
            <div class="p-6">
                <h3 class="text-2xl font-bold text-gray-900">Project Title</h3>
                <p class="mt-4 text-gray-600">Detailed project description goes here...</p>
                <button class="mt-6 px-4 py-2 bg-purple-900 text-white rounded-md hover:bg-purple-800">Close</button>
            </div>
        </div>
    </div>
