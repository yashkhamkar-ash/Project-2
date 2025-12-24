# Project-2
<!-- Header -->
<header id="header" class="bg-white/80 backdrop-blur-lg fixed top-0 left-0 right-0 z-50 transition-all duration-300 shadow-sm">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
        <a href="#" class="text-2xl font-bold text-gray-800 flex items-center">
            <i data-lucide="mountain-snow" class="mr-2 text-green-600"></i>
            TrekMate
        </a>
        <nav id="desktop-nav" class="hidden md:flex space-x-8 items-center">
            <a href="#home" class="nav-link text-gray-600 hover:text-green-600 transition-colors">Home</a>
            <a href="#features" class="nav-link text-gray-600 hover:text-green-600 transition-colors">Features</a>
            <a href="#treks" class="nav-link text-gray-600 hover:text-green-600 transition-colors">Treks</a>
            <a href="#community" class="nav-link text-gray-600 hover:text-green-600 transition-colors">Community</a>
            <a href="#contact" class="nav-link text-gray-600 hover:text-green-600 transition-colors">Contact</a>
        </nav>
        <div class="flex items-center space-x-4">
            <button id="ai-assistant-btn" class="bg-green-600 text-white px-4 py-2 rounded-full hover:bg-green-700 transition-colors flex items-center shadow">
                <i data-lucide="sparkles" class="mr-2 h-5 w-5"></i>
                AI Assistant
            </button>
            <button id="mobile-menu-btn" class="md:hidden text-gray-800">
                <i data-lucide="menu"></i>
            </button>
        </div>
    </div>
    <!-- Mobile Menu -->
    <div id="mobile-menu" class="hidden md:hidden px-6 pb-4">
        <a href="#home" class="nav-link-mobile block py-2 text-gray-600 hover:text-green-600">Home</a>
        <a href="#features" class="nav-link-mobile block py-2 text-gray-600 hover:text-green-600">Features</a>
        <a href="#treks" class="nav-link-mobile block py-2 text-gray-600 hover:text-green-600">Treks</a>
        <a href="#community" class="nav-link-mobile block py-2 text-gray-600 hover:text-green-600">Community</a>
        <a href="#contact" class="nav-link-mobile block py-2 text-gray-600 hover:text-green-600">Contact</a>
    </div>
</header>

<main>
    <!-- Hero Section -->
    <section id="home" class="hero-bg text-white min-h-screen flex items-center">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-4 leading-tight">Your Adventure Awaits</h1>
            <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto">Navigate, stay safe, and connect with a community that shares your passion for the wild. TrekMate is your essential companion for every trail.</p>
            <a href="#treks" class="bg-green-600 text-white px-8 py-4 rounded-full text-lg font-semibold hover:bg-green-700 transition-transform transform hover:scale-105 shadow-lg">Start Your Adventure</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800">Everything You Need for the Perfect Trek</h2>
                <p class="text-gray-600 mt-4 max-w-2xl mx-auto">From cutting-edge safety features to a vibrant community, we've got you covered.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Feature Card -->
                <div class="bg-gray-50 p-8 rounded-lg shadow-sm text-center card-hover-effect">
                    <div class="bg-green-100 text-green-600 rounded-full p-4 inline-block mb-4">
                        <i data-lucide="map-pinned"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Real-time GPS Tracking</h3>
                    <p class="text-gray-600">Share your journey with loved ones and never lose your way with our precise, live tracking.</p>
                </div>
                <!-- Feature Card -->
                <div class="bg-gray-50 p-8 rounded-lg shadow-sm text-center card-hover-effect">
                    <div class="bg-red-100 text-red-600 rounded-full p-4 inline-block mb-4">
                        <i data-lucide="siren"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">SOS Emergency Alerts</h3>
                    <p class="text-gray-600">Instantly notify emergency contacts with your exact location at the tap of a button.</p>
                </div>
                <!-- Feature Card -->
                <div class="bg-gray-50 p-8 rounded-lg shadow-sm text-center card-hover-effect">
                    <div class="bg-green-100 text-green-600 rounded-full p-4 inline-block mb-4">
                        <i data-lucide="wifi-off"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Offline Map Access</h3>
                    <p class="text-gray-600">Download detailed maps before you go and navigate confidently, even without a signal.</p>
                </div>
                <!-- Feature Card -->
                <div class="bg-gray-50 p-8 rounded-lg shadow-sm text-center card-hover-effect">
                    <div class="bg-green-100 text-green-600 rounded-full p-4 inline-block mb-4">
                        <i data-lucide="leaf"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Eco-Reporting</h3>
                    <p class="text-gray-600">Help protect our trails by reporting litter or environmental damage with a photo and GPS tag.</p>
                </div>
                  <!-- Feature Card -->
                <div class="bg-gray-50 p-8 rounded-lg shadow-sm text-center card-hover-effect">
                    <div class="bg-green-100 text-green-600 rounded-full p-4 inline-block mb-4">
                        <i data-lucide="book-marked"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Personal Trek Diary</h3>
                    <p class="text-gray-600">Log your adventures, save your favorite spots, and create a beautiful journal of your treks.</p>
                </div>
                <!-- Feature Card -->
                <div class="bg-gray-50 p-8 rounded-lg shadow-sm text-center card-hover-effect">
                    <div class="bg-green-100 text-green-600 rounded-full p-4 inline-block mb-4">
                        <i data-lucide="users"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Thriving Community</h3>
                    <p class="text-gray-600">Share tips, photos, and reviews. Find trekking partners and join discussions in our forums.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- AI Safety Advisor Section -->
    <section id="ai-safety" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800">AI-Powered Safety Advisor</h2>
                <p class="text-gray-600 mt-4 max-w-2xl mx-auto">Enter a trek name or region to get personalized safety tips from our AI guide.</p>
            </div>
            <div class="max-w-4xl mx-auto bg-white p-8 rounded-lg shadow-md">
                <div class="flex flex-col sm:flex-row gap-4">
                    <input type="text" id="safety-input" placeholder="e.g., Mount Kilimanjaro" class="flex-grow mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500 p-3">
                    <button id="get-safety-tips-btn" class="bg-blue-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-blue-700 transition-transform transform hover:scale-105 shadow-lg flex items-center justify-center">
                        <i data-lucide="shield-check" class="mr-2"></i>
                        Get Safety Tips ✨
                    </button>
                </div>
                <div id="safety-tips-output" class="mt-8 p-6 bg-gray-50 rounded-lg hidden prose max-w-none">
                    <div id="safety-tips-loader" class="text-center hidden">
                        <div class="animate-spin rounded-full h-8 w-8 border-b-2 border-blue-600 mx-auto"></div>
                        <p class="mt-2 text-gray-600">Our AI is checking the trail conditions...</p>
                    </div>
                    <div id="safety-tips-content"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- AI Packing Planner Section -->
    <section id="ai-planner" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800">AI-Powered Packing Planner</h2>
                <p class="text-gray-600 mt-4 max-w-2xl mx-auto">Let our AI create a personalized packing list for your next adventure. Just fill in the details below!</p>
            </div>
            <div class="max-w-4xl mx-auto bg-white p-8 rounded-lg shadow-md">
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <label for="planner-destination" class="block text-sm font-medium text-gray-700">Destination</label>
                        <input type="text" id="planner-destination" placeholder="e.g., Himalayas, Nepal" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div>
                        <label for="planner-duration" class="block text-sm font-medium text-gray-700">Duration (days)</label>
                        <input type="number" id="planner-duration" placeholder="e.g., 7" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div>
                        <label for="planner-season" class="block text-sm font-medium text-gray-700">Season</label>
                        <select id="planner-season" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                            <option>Spring</option>
                            <option>Summer</option>
                            <option>Autumn</option>
                            <option>Winter</option>
                        </select>
                    </div>
                    <div>
                        <label for="planner-difficulty" class="block text-sm font-medium text-gray-700">Difficulty</label>
                        <select id="planner-difficulty" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                            <option>Easy</option>
                            <option>Moderate</option>
                            <option>Challenging</option>
                            <option>Extreme</option>
                        </select>
                    </div>
                </div>
                <div class="mt-6 text-center">
                    <button id="generate-packing-list-btn" class="bg-green-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-green-700 transition-transform transform hover:scale-105 shadow-lg flex items-center justify-center mx-auto">
                        <i data-lucide="list-checks" class="mr-2"></i>
                        Generate Packing List
                    </button>
                </div>
                <div id="packing-list-output" class="mt-8 p-6 bg-gray-50 rounded-lg hidden prose max-w-none">
                    <div id="packing-list-loader" class="text-center hidden">
                        <div class="animate-spin rounded-full h-8 w-8 border-b-2 border-green-600 mx-auto"></div>
                        <p class="mt-2 text-gray-600">Our AI is packing your bags...</p>
                    </div>
                    <div id="packing-list-content"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Upcoming Treks Section -->
    <section id="treks" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800">Join an Upcoming Trek</h2>
                <p class="text-gray-600 mt-4 max-w-2xl mx-auto">Explore breathtaking landscapes with our expert-led groups. Find your next great adventure here.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Trek Card 1 -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden card-hover-effect">
                    <img src="https://placehold.co/600x400/34a853/ffffff?text=Everest+Base+Camp" alt="Everest Base Camp Trek" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Everest Base Camp</h3>
                        <p class="text-gray-600 mb-4 flex items-center"><i data-lucide="map-pin" class="mr-2 h-4 w-4"></i>Himalayas, Nepal</p>
                        <p class="text-gray-600 mb-4 flex items-center"><i data-lucide="calendar" class="mr-2 h-4 w-4"></i>Next Trek: Oct 15, 2025</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-green-600">$1,800</span>
                            <a href="#contact" class="bg-green-600 text-white px-4 py-2 rounded-full hover:bg-green-700 transition-colors text-sm">Inquire Now</a>
                        </div>
                    </div>
                </div>
                <!-- Trek Card 2 -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden card-hover-effect">
                    <img src="https://placehold.co/600x400/fbbc05/ffffff?text=Inca+Trail" alt="Inca Trail to Machu Picchu" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Inca Trail to Machu Picchu</h3>
                        <p class="text-gray-600 mb-4 flex items-center"><i data-lucide="map-pin" class="mr-2 h-4 w-4"></i>Andes, Peru</p>
                        <p class="text-gray-600 mb-4 flex items-center"><i data-lucide="calendar" class="mr-2 h-4 w-4"></i>Next Trek: Nov 05, 2025</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-green-600">$2,200</span>
                            <a href="#contact" class="bg-green-600 text-white px-4 py-2 rounded-full hover:bg-green-700 transition-colors text-sm">Inquire Now</a>
                        </div>
                    </div>
                </div>
                <!-- Trek Card 3 -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden card-hover-effect">
                    <img src="https://placehold.co/600x400/ea4335/ffffff?text=Mount+Kilimanjaro" alt="Mount Kilimanjaro" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Mount Kilimanjaro</h3>
                        <p class="text-gray-600 mb-4 flex items-center"><i data-lucide="map-pin" class="mr-2 h-4 w-4"></i>Tanzania, Africa</p>
                        <p class="text-gray-600 mb-4 flex items-center"><i data-lucide="calendar" class="mr-2 h-4 w-4"></i>Next Trek: Jan 20, 2026</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-green-600">$3,500</span>
                            <a href="#contact" class="bg-green-600 text-white px-4 py-2 rounded-full hover:bg-green-700 transition-colors text-sm">Inquire Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Trek Map Section -->
    <section id="map-section" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800">Explore Our Trek Locations</h2>
                <p class="text-gray-600 mt-4 max-w-2xl mx-auto">Visualize your next adventure on our interactive map showing all our trek starting points.</p>
            </div>
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div id="treks-map" style="height: 500px; width: 100%;"></div>
            </div>
        </div>
    </section>

    <!-- Testimonials & Stories Section -->
    <section id="community" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800">From Our Community</h2>
                <p class="text-gray-600 mt-4 max-w-2xl mx-auto">Hear what fellow adventurers are saying. All feedback and stories are shared directly by our users and updated in real-time, offering genuine insights for your next journey.</p>
            </div>
            
            <!-- Testimonials -->
            <div class="mb-16">
                <h3 class="text-2xl font-bold text-gray-800 mb-8 text-center">What Our Trekkers Say</h3>
                <div id="testimonials-container" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Dynamic content will be loaded here -->
                    <p class="text-gray-500 text-center col-span-full">Loading feedback...</p>
                </div>
            </div>

            <!-- Stories -->
            <div>
                <h3 class="text-2xl font-bold text-gray-800 mb-8 text-center">Stories from the Trail</h3>
                <div id="stories-container" class="grid md:grid-cols-2 gap-8">
                    <!-- Dynamic content will be loaded here -->
                    <p class="text-gray-500 text-center col-span-full">Loading stories...</p>
                </div>
            </div>
        </div>
    </section>


    <!-- Blog & Feedback Submission Section -->
    <section id="blog-feedback" class="py-20 bg-white">
        <div class="container mx-auto px-6 grid lg:grid-cols-2 gap-12 items-start">
            <!-- Blog Post Submission -->
            <div class="bg-gray-50 p-8 rounded-lg shadow-md">
                <h3 class="text-2xl font-bold mb-6 text-center">Share Your Story</h3>
                <form id="blog-form">
                    <div class="mb-4">
                        <label for="blog-title" class="block text-sm font-medium text-gray-700">Title</label>
                        <input type="text" id="blog-title" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div class="mb-4">
                        <label for="blog-content" class="block text-sm font-medium text-gray-700">Your Story</label>
                        <textarea id="blog-content" rows="6" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500"></textarea>
                    </div>
                    <div class="mb-6">
                        <button type="button" id="generate-insight-btn" class="w-full text-sm bg-blue-500 text-white py-2 rounded-md hover:bg-blue-600 flex items-center justify-center">
                            <i data-lucide="sparkles" class="mr-2 h-4 w-4"></i>
                            Get AI Insight for Your Story
                        </button>
                        <div id="insight-loader" class="text-center mt-2 hidden">
                            <div class="animate-spin rounded-full h-6 w-6 border-b-2 border-blue-500 mx-auto"></div>
                        </div>
                        <p id="ai-insight" class="text-sm text-gray-600 mt-2 bg-blue-50 p-3 rounded-md hidden"></p>
                    </div>
                    <button type="submit" class="w-full bg-green-600 text-white py-3 rounded-md font-semibold hover:bg-green-700 transition-colors">Submit Blog Post</button>
                </form>
            </div>

            <!-- Feedback Form -->
            <div class="bg-gray-50 p-8 rounded-lg shadow-md">
                <h3 class="text-2xl font-bold mb-6 text-center">Give Us Your Feedback</h3>
                <form id="feedback-form">
                    <div class="mb-4">
                        <label for="feedback-name" class="block text-sm font-medium text-gray-700">Name</label>
                        <input type="text" id="feedback-name" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div class="mb-4">
                        <label for="feedback-email" class="block text-sm font-medium text-gray-700">Email</label>
                        <input type="email" id="feedback-email" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div class="mb-4">
                        <label for="feedback-message" class="block text-sm font-medium text-gray-700">Message</label>
                        <textarea id="feedback-message" rows="4" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-green-600 text-white py-3 rounded-md font-semibold hover:bg-green-700 transition-colors">Send Feedback</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6 grid lg:grid-cols-2 gap-12 items-center">
            <div>
                <h2 class="text-3xl font-bold mb-4">Get in Touch</h2>
                <p class="text-gray-600 mb-8">Have a question about a trek or need help planning your adventure? We're here to help!</p>
                <form id="contact-form">
                    <div class="mb-4">
                        <label for="contact-name" class="block text-sm font-medium text-gray-700">Name</label>
                        <input type="text" id="contact-name" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div class="mb-4">
                        <label for="contact-email" class="block text-sm font-medium text-gray-700">Email</label>
                        <input type="email" id="contact-email" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500">
                    </div>
                    <div class="mb-4">
                        <label for="contact-message" class="block text-sm font-medium text-gray-700">Message</label>
                        <textarea id="contact-message" rows="5" required class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-green-500 focus:ring-green-500"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-green-600 text-white py-3 rounded-md font-semibold hover:bg-green-700 transition-colors">Send Message</button>
                </form>
            </div>
            <div class="bg-white rounded-lg shadow-lg overflow-hidden h-96 lg:h-full">
                 <div id="contact-map" style="height: 100%; width: 100%;"></div>
            </div>
        </div>
    </section>
</main>

<!-- Footer -->
<footer class="bg-gray-800 text-white">
    <div class="container mx-auto px-6 py-12">
        <div class="grid md:grid-cols-4 gap-8">
            <div>
                <h3 class="text-lg font-bold mb-4">TrekMate</h3>
                <p class="text-gray-400">Your companion for every trail.</p>
            </div>
            <div>
                <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
                <ul>
                    <li class="mb-2"><a href="#home" class="hover:text-green-400">Home</a></li>
                    <li class="mb-2"><a href="#features" class="hover:text-green-400">Features</a></li>
                    <li class="mb-2"><a href="#treks" class="hover:text-green-400">Treks</a></li>
                    <li class="mb-2"><a href="#contact" class="hover:text-green-400">Contact</a></li>
                </ul>
            </div>
            <div>
                <h3 class="text-lg font-semibold mb-4">Support</h3>
                 <ul>
                    <li class="mb-2"><a href="#" class="hover:text-green-400">FAQs</a></li>
                    <li class="mb-2"><a href="#" class="hover:text-green-400">Help Center</a></li>
                    <li class="mb-2"><a href="#" class="hover:text-green-400">Privacy Policy</a></li>
                </ul>
            </div>
             <div>
                <h3 class="text-lg font-semibold mb-4">Follow Us</h3>
                <div class="flex space-x-4">
                    <a href="#" class="text-gray-400 hover:text-white"><i data-lucide="twitter"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white"><i data-lucide="instagram"></i></a>
                    <a href="#" class="text-gray-400 hover:text-white"><i data-lucide="facebook"></i></a>
                </div>
            </div>
        </div>
        <div class="mt-12 border-t border-gray-700 pt-8 text-center text-gray-500">
            <p>&copy; 2025 TrekMate. All rights reserved.</p>
        </div>
    </div>
</footer>

<!-- Floating SOS Button -->
<button id="sos-btn" class="fixed bottom-5 right-5 bg-red-600 text-white rounded-full p-4 shadow-lg z-50 hover:bg-red-700 transition-transform transform hover:scale-110">
    <i data-lucide="siren" class="h-8 w-8"></i>
</button>

<!-- SOS Confirmation Modal -->
<div id="sos-modal" class="modal fixed inset-0 bg-black bg-opacity-60 flex items-center justify-center p-4 z-[60] opacity-0 pointer-events-none">
    <div id="sos-modal-content" class="bg-white rounded-lg shadow-2xl w-full max-w-md transform scale-95 transition-transform duration-300">
        <div class="p-6 text-center">
            <i data-lucide="alert-triangle" class="h-16 w-16 text-red-500 mx-auto mb-4"></i>
            <h3 class="text-xl font-bold text-gray-800 mb-2">Confirm Emergency Alert</h3>
            <p class="text-gray-600 mb-6">This will send an SMS with your current location to your emergency contact. Only use this in a genuine emergency.</p>
            <div id="sos-status" class="text-gray-600 mb-4 hidden"></div>
            <div class="flex justify-center space-x-4">
                <button id="cancel-sos" class="bg-gray-200 text-gray-800 px-8 py-3 rounded-full hover:bg-gray-300 transition-colors">Cancel</button>
                <button id="confirm-sos" class="bg-red-600 text-white px-8 py-3 rounded-full hover:bg-red-700 transition-colors flex items-center justify-center">
                    <span id="confirm-sos-text">Confirm & Send</span>
                    <div id="sos-loader" class="animate-spin rounded-full h-5 w-5 border-b-2 border-white ml-2 hidden"></div>
                </button>
            </div>
        </div>
    </div>
</div>


<!-- AI Assistant Modal -->
<div id="ai-modal" class="modal fixed inset-0 bg-black bg-opacity-60 flex items-center justify-center p-4 z-50 opacity-0 pointer-events-none">
    <div id="ai-modal-content" class="bg-white rounded-lg shadow-2xl w-full max-w-lg max-h-[90vh] flex flex-col transform scale-95 transition-transform duration-300">
        <div class="p-4 border-b flex justify-between items-center">
            <h3 class="text-lg font-bold flex items-center"><i data-lucide="sparkles" class="mr-2 text-green-600"></i>AI Trek Guide</h3>
            <button id="close-ai-modal" class="text-gray-500 hover:text-gray-800">&times;</button>
        </div>
        <div id="chat-output" class="flex-grow p-4 overflow-y-auto bg-gray-100 space-y-4">
            <!-- Chat messages will be appended here -->
            <div class="flex justify-start">
                <div class="bg-gray-200 text-gray-800 p-3 rounded-lg max-w-xs">
                    Hello! I'm your AI Trek Guide. Ask me anything about hiking, gear, safety, or famous trails!
                </div>
            </div>
        </div>
        <div class="p-4 border-t">
            <div id="chat-loader" class="text-center mb-2 hidden">
                <div class="animate-spin rounded-full h-6 w-6 border-b-2 border-green-600 mx-auto"></div>
            </div>
            <div class="flex">
                <input type="text" id="chat-input" placeholder="Ask about a trek..." class="flex-grow border rounded-l-md p-2 focus:outline-none focus:ring-2 focus:ring-green-500">
                <button id="chat-send" class="bg-green-600 text-white px-4 rounded-r-md hover:bg-green-700">Send</button>
            </div>
        </div>
    </div>
</div>

<!-- Notification Toast -->
<div id="toast" class="fixed bottom-5 right-5 bg-gray-900 text-white px-6 py-3 rounded-lg shadow-lg opacity-0 translate-y-10 transition-all duration-300 z-[70]">
    <span id="toast-message"></span>
</div>

<script type="module">
    // --- CONFIGURATION ---
    const SUPABASE_URL = 'https://dwxikjpxkyotedewxgkr.supabase.co'; 
    const SUPABASE_ANON_KEY = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImR3eGlranB4a3lvdGVkZXd4Z2tyIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTc3NzI2ODksImV4cCI6MjA3MzM0ODY4OX0.0ZVsX3yfiC-pWcmy8yuUXHQOzkTutNY18FVg7LPDSUI';
    const GEMINI_API_KEY = "AIzaSyDRiCKKIkCzbFUBT0l47LnqVOCzPxqrXu8";
    const GOOGLE_MAPS_API_KEY = 'YOUR_GOOGLE_MAPS_API_KEY';
    
    // --- SOS Alert Configuration ---
    const TWILIO_FUNCTION_URL = 'SKb6f1f7f20fb476a0acce4394e05de5ff'; // IMPORTANT: Replace with your actual Twilio Function URL
    const EMERGENCY_CONTACT_NUMBER = '8080020061'; // IMPORTANT: Replace with the recipient's phone number (e.g., +15551234567)
    
    // --- INITIALIZATION ---
    lucide.createIcons();
    document.addEventListener('DOMContentLoaded', () => {
        loadGoogleMapsScript();
        loadCommunityContent();
    });

    // --- UI Interactions & Navigation ---
    const header = document.getElementById('header');
    window.addEventListener('scroll', () => {
        // Header shrink effect
        if (window.scrollY > 50) {
            header.classList.add('py-2', 'shadow-md');
            header.classList.remove('py-4');
        } else {
            header.classList.remove('py-2', 'shadow-md');
            header.classList.add('py-4');
        }
        // Active nav link highlighting
        updateActiveNavLink();
    });

    const mobileMenuBtn = document.getElementById('mobile-menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    mobileMenuBtn.addEventListener('click', () => {
        mobileMenu.classList.toggle('hidden');
    });
    
    // Close mobile menu when a link is clicked
    document.querySelectorAll('.nav-link-mobile').forEach(link => {
        link.addEventListener('click', () => {
            mobileMenu.classList.add('hidden');
        });
    });

    // Function to update active nav link on scroll
    function updateActiveNavLink() {
        const sections = document.querySelectorAll('main section');
        const navLinks = document.querySelectorAll('#desktop-nav .nav-link');
        
        let currentSectionId = '';
        sections.forEach(section => {
            const sectionTop = section.offsetTop;
            if (window.scrollY >= sectionTop - 100) { // 100px offset for header height
                currentSectionId = section.getAttribute('id');
            }
        });

        navLinks.forEach(link => {
            link.classList.remove('nav-link-active');
            if (link.getAttribute('href') === `#${currentSectionId}`) {
                link.classList.add('nav-link-active');
            }
        });
    }


    // --- Toast Notification ---
    const toast = document.getElementById('toast');
    const toastMessage = document.getElementById('toast-message');

    function showToast(message, isSuccess = true) {
        toastMessage.textContent = message;
        toast.classList.toggle('bg-red-600', !isSuccess);
        toast.classList.toggle('bg-gray-900', isSuccess);
        toast.classList.remove('opacity-0', 'translate-y-10');
        setTimeout(() => {
            toast.classList.add('opacity-0', 'translate-y-10');
        }, 3000);
    }

    // --- Supabase Data Handling ---

    // Function to FETCH data from Supabase
    async function fetchFromSupabase(tableName) {
        if (!SUPABASE_URL || !SUPABASE_ANON_KEY) return [];
        const response = await fetch(`${SUPABASE_URL}/rest/v1/${tableName}?select=*&order=created_at.desc`, {
            headers: {
                'apikey': SUPABASE_ANON_KEY,
                'Authorization': `Bearer ${SUPABASE_ANON_KEY}`,
            },
        });
        if (!response.ok) {
            console.error(`Failed to fetch from ${tableName}`);
            return [];
        }
        return response.json();
    }

    // Function to SUBMIT data to Supabase
    async function supabaseSubmit(tableName, data) {
        if (!SUPABASE_URL || !SUPABASE_ANON_KEY) {
             console.error("Supabase URL or Key is not configured.");
             showToast("Backend not configured. Check console.", false);
             return;
        }
        const response = await fetch(`${SUPABASE_URL}/rest/v1/${tableName}`, {
            method: 'POST',
            headers: {
                'apikey': SUPABASE_ANON_KEY,
                'Authorization': `Bearer ${SUPABASE_ANON_KEY}`,
                'Content-Type': 'application/json',
                'Prefer': 'return=minimal',
            },
            body: JSON.stringify(data),
        });

        if (!response.ok) {
            const error = await response.json();
            console.error('Supabase Error:', error);
            throw new Error(`Supabase error: ${error.message}`);
        }
    }
    
    // --- Dynamic Content Loading ---

    async function loadCommunityContent() {
        // Load and display feedback
        const testimonialsContainer = document.getElementById('testimonials-container');
        const feedbackData = await fetchFromSupabase('feedback');
        testimonialsContainer.innerHTML = ''; // Clear loading message
        if (feedbackData.length > 0) {
            feedbackData.slice(0, 3).forEach(item => { // Show latest 3
                const card = document.createElement('div');
                card.className = 'bg-white p-6 rounded-lg shadow-sm';
                card.innerHTML = `
                    <p class="text-gray-600 italic mb-4">"${item.message}"</p>
                    <p class="font-bold text-gray-800">- ${item.name}</p>
                `;
                testimonialsContainer.appendChild(card);
            });
        } else {
            testimonialsContainer.innerHTML = '<p class="text-gray-500 text-center col-span-full">Be the first to leave feedback!</p>';
        }

        // Load and display stories
        const storiesContainer = document.getElementById('stories-container');
        const storiesData = await fetchFromSupabase('blog_posts');
        storiesContainer.innerHTML = ''; // Clear loading message
        if (storiesData.length > 0) {
            storiesData.slice(0, 2).forEach(item => { // Show latest 2
                const card = document.createElement('div');
                card.className = 'bg-white rounded-lg shadow-sm overflow-hidden';
                card.innerHTML = `
                    <img src="https://placehold.co/600x400/6366f1/ffffff?text=Story" alt="${item.title}" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h4 class="text-xl font-bold mb-2">${item.title}</h4>
                        <p class="text-gray-600 mb-4 line-clamp-3">${item.content}</p>
                        <a href="#" class="text-green-600 font-semibold hover:underline">Read More</a>
                    </div>
                `;
                storiesContainer.appendChild(card);
            });
        } else {
            storiesContainer.innerHTML = '<p class="text-gray-500 text-center col-span-full">Be the first to share a story!</p>';
        }
    }

    // --- Form Submission Event Listeners ---
    document.getElementById('contact-form').addEventListener('submit', async (e) => {
        e.preventDefault();
        const form = e.target;
        try {
            await supabaseSubmit('contacts', {
                name: form['contact-name'].value,
                email: form['contact-email'].value,
                message: form['contact-message'].value,
            });
            showToast('Message sent successfully!');
            form.reset();
        } catch (error) {
            console.error('Contact form submission error:', error);
            showToast('Failed to send message.', false);
        }
    });

    document.getElementById('feedback-form').addEventListener('submit', async (e) => {
        e.preventDefault();
        const form = e.target;
        try {
            await supabaseSubmit('feedback', {
                name: form['feedback-name'].value,
                email: form['feedback-email'].value,
                message: form['feedback-message'].value,
            });
            showToast('Thank you for your feedback!');
            form.reset();
            loadCommunityContent(); // Refresh content after submission
        } catch (error) {
            console.error('Feedback form submission error:', error);
            showToast('Failed to send feedback.', false);
        }
    });

    document.getElementById('blog-form').addEventListener('submit', async (e) => {
        e.preventDefault();
        const form = e.target;
        try {
            await supabaseSubmit('blog_posts', {
                title: form['blog-title'].value,
                content: form['blog-content'].value,
            });
            showToast('Blog post submitted for review!');
            form.reset();
            document.getElementById('ai-insight').classList.add('hidden');
            loadCommunityContent(); // Refresh content after submission
        } catch (error) {
            console.error('Blog form submission error:', error);
            showToast('Failed to submit post.', false);
        }
    });

    // --- SOS Alert Feature ---
    const sosBtn = document.getElementById('sos-btn');
    const sosModal = document.getElementById('sos-modal');
    const sosModalContent = document.getElementById('sos-modal-content');
    const cancelSosBtn = document.getElementById('cancel-sos');
    const confirmSosBtn = document.getElementById('confirm-sos');
    const sosStatus = document.getElementById('sos-status');
    const sosLoader = document.getElementById('sos-loader');
    const confirmSosText = document.getElementById('confirm-sos-text');

    sosBtn.addEventListener('click', () => {
        sosModal.classList.remove('opacity-0', 'pointer-events-none');
        sosModalContent.classList.remove('scale-95');
    });

    function closeSosModal() {
        sosModal.classList.add('opacity-0', 'pointer-events-none');
        sosModalContent.classList.add('scale-95');
        // Reset modal state
        setTimeout(() => {
            sosStatus.classList.add('hidden');
            confirmSosBtn.disabled = false;
            sosLoader.classList.add('hidden');
            confirmSosText.textContent = 'Confirm & Send';
        }, 300); // Wait for transition
    }

    cancelSosBtn.addEventListener('click', closeSosModal);

    confirmSosBtn.addEventListener('click', () => {
        if (TWILIO_FUNCTION_URL === 'YOUR_TWILIO_FUNCTION_URL' || EMERGENCY_CONTACT_NUMBER === 'YOUR_EMERGENCY_CONTACT_PHONE_NUMBER') {
            sosStatus.textContent = 'SOS feature is not configured.';
            sosStatus.classList.remove('hidden');
            sosStatus.classList.add('text-red-500');
            return;
        }

        sosStatus.textContent = 'Getting your location...';
        sosStatus.classList.remove('hidden', 'text-red-500', 'text-green-500');
        confirmSosBtn.disabled = true;
        sosLoader.classList.remove('hidden');
        confirmSosText.textContent = 'Sending...';

        navigator.geolocation.getCurrentPosition(
            async (position) => {
                const { latitude, longitude } = position.coords;
                const mapsLink = `https://www.google.com/maps?q=${latitude},${longitude}`;
                const message = `SOS from TrekMate user! Emergency alert. Last known location: Lat: ${latitude}, Long: ${longitude}. Map: ${mapsLink}`;

                sosStatus.textContent = 'Location found. Sending alert...';
                
                try {
                    const response = await fetch(TWILIO_FUNCTION_URL, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify({ to: EMERGENCY_CONTACT_NUMBER, body: message }),
                    });

                    if (!response.ok) throw new Error('Network response was not ok.');
                    
                    const result = await response.json();

                    if (result.success) {
                        sosStatus.textContent = 'Emergency alert sent successfully!';
                        sosStatus.classList.add('text-green-500');
                        setTimeout(closeSosModal, 3000);
                    } else {
                        throw new Error(result.error || 'Unknown error from SMS service.');
                    }

                } catch (error) {
                    console.error('SOS sending failed:', error);
                    sosStatus.textContent = `Error: Could not send alert. Please check your connection.`;
                    sosStatus.classList.add('text-red-500');
                    confirmSosBtn.disabled = false;
                    sosLoader.classList.add('hidden');
                    confirmSosText.textContent = 'Retry Sending';
                }
            },
            (error) => {
                console.error('Geolocation error:', error);
                let errorMessage = 'Could not get your location.';
                if (error.code === 1) errorMessage = 'Location access was denied.';
                sosStatus.textContent = `Error: ${errorMessage}`;
                sosStatus.classList.add('text-red-500');
                confirmSosBtn.disabled = false;
                sosLoader.classList.add('hidden');
                confirmSosText.textContent = 'Retry Sending';
            },
            { enableHighAccuracy: true, timeout: 10000, maximumAge: 0 }
        );
    });

    // --- AI & Gemini API Features ---
    async function callGeminiAPI(prompt, systemInstruction) {
        if (!GEMINI_API_KEY || !GEMINI_API_KEY.startsWith("AIza")) {
             console.error("Gemini API key is not valid. Please check the key in the script.");
             return "Error: Gemini API key is not configured correctly.";
        }

        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${GEMINI_API_KEY}`;
        
        const payload = {
            contents: [{ parts: [{ text: prompt }] }]
        };

        if (systemInstruction) {
            payload.systemInstruction = { parts: [{ text: systemInstruction }] };
        }

        try {
            const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload),
            });

            if (!response.ok) {
                const errorBody = await response.json();
                console.error("Gemini API Error:", errorBody);
                throw new Error(`API call failed with status: ${response.status}`);
            }

            const result = await response.json();
            const text = result.candidates?.[0]?.content?.parts?.[0]?.text;

            if (!text) {
                 console.error("Gemini API response is empty or malformed:", result);
                 return "Sorry, I couldn't generate a response. The AI might have filtered the content.";
            }
            return text;

        } catch (error) {
            console.error("Error calling Gemini API:", error);
            return `Sorry, an error occurred while contacting the AI assistant: ${error.message}`;
        }
    }
    
    // AI Safety Advisor
    const getSafetyTipsBtn = document.getElementById('get-safety-tips-btn');
    const safetyInput = document.getElementById('safety-input');
    const safetyTipsOutput = document.getElementById('safety-tips-output');
    const safetyTipsLoader = document.getElementById('safety-tips-loader');
    const safetyTipsContent = document.getElementById('safety-tips-content');

    getSafetyTipsBtn.addEventListener('click', async () => {
        const topic = safetyInput.value.trim();
        if (!topic) {
            showToast("Please enter a trek or location.", false);
            return;
        }

        safetyTipsOutput.classList.remove('hidden');
        safetyTipsLoader.classList.remove('hidden');
        safetyTipsContent.innerHTML = '';

        const prompt = `Act as an expert trekking safety advisor. Provide a concise, actionable list of the top 5-7 most important safety tips for a trek in or to the following location: "${topic}". The tips should be specific to the potential challenges of that region (e.g., altitude, weather, wildlife). Format the response as a markdown list.`;

        const tips = await callGeminiAPI(prompt);

        let htmlTips = tips
            .replace(/\*\*([^*]+)\*\*/g, '<strong>$1</strong>')
            .replace(/\* (.*)/g, '<li class="ml-4 mb-2">$1</li>')
            .replace(/\n/g, '');

        safetyTipsLoader.classList.add('hidden');
        safetyTipsContent.innerHTML = `<ul>${htmlTips}</ul>`;
    });
    
    // AI Trek Guide (Modal)
    const aiModal = document.getElementById('ai-modal');
    const aiModalContent = document.getElementById('ai-modal-content');
    const chatOutput = document.getElementById('chat-output');
    const chatInput = document.getElementById('chat-input');
    const chatSendBtn = document.getElementById('chat-send');
    const chatLoader = document.getElementById('chat-loader');

    document.getElementById('ai-assistant-btn').addEventListener('click', () => {
        aiModal.classList.remove('opacity-0', 'pointer-events-none');
        aiModalContent.classList.remove('scale-95');
    });

    document.getElementById('close-ai-modal').addEventListener('click', () => {
        aiModal.classList.add('opacity-0', 'pointer-events-none');
        aiModalContent.classList.add('scale-95');
    });

    async function handleChatSubmit() {
        const userMessage = chatInput.value.trim();
        if (!userMessage) return;

        const userMessageDiv = document.createElement('div');
        userMessageDiv.className = 'flex justify-end';
        userMessageDiv.innerHTML = `<div class="bg-green-600 text-white p-3 rounded-lg max-w-xs">${userMessage}</div>`;
        chatOutput.appendChild(userMessageDiv);

        chatInput.value = '';
        chatOutput.scrollTop = chatOutput.scrollHeight;
        chatLoader.classList.remove('hidden');

        const systemInstruction = "You are a friendly and knowledgeable trekking guide. Your sole purpose is to provide information related to trekking, hiking, camping, and outdoor adventures. Politely refuse to answer any questions that are not related to these topics. If a user asks an unrelated question, gently steer the conversation back to trekking by saying something like, 'I specialize in trekking and hiking topics. How can I assist with your next adventure?'";
        const aiResponse = await callGeminiAPI(userMessage, systemInstruction);

        const aiMessageDiv = document.createElement('div');
        aiMessageDiv.className = 'flex justify-start';
        aiMessageDiv.innerHTML = `<div class="bg-gray-200 text-gray-800 p-3 rounded-lg max-w-xs">${aiResponse}</div>`;
        chatOutput.appendChild(aiMessageDiv);
        
        chatLoader.classList.add('hidden');
        chatOutput.scrollTop = chatOutput.scrollHeight;
    }

    chatSendBtn.addEventListener('click', handleChatSubmit);
    chatInput.addEventListener('keypress', (e) => {
        if (e.key === 'Enter') handleChatSubmit();
    });

    // AI Blog Insight Generator
    const generateInsightBtn = document.getElementById('generate-insight-btn');
    const insightLoader = document.getElementById('insight-loader');
    const aiInsight = document.getElementById('ai-insight');
    const blogContent = document.getElementById('blog-content');

    generateInsightBtn.addEventListener('click', async () => {
        const content = blogContent.value;
        if (content.length < 50) {
            showToast("Please write at least 50 characters for a good insight.", false);
            return;
        }
        insightLoader.classList.remove('hidden');
        aiInsight.classList.add('hidden');
        const prompt = `Based on the following trek story, generate a short, one-sentence, inspiring insight or takeaway for a blog post conclusion:\n\n---\n\n${content}`;
        const insight = await callGeminiAPI(prompt);
        insightLoader.classList.add('hidden');
        aiInsight.textContent = insight;
        aiInsight.classList.remove('hidden');
    });

    // AI Packing List Generator
    const generatePackingListBtn = document.getElementById('generate-packing-list-btn');
    const packingListOutput = document.getElementById('packing-list-output');
    const packingListLoader = document.getElementById('packing-list-loader');
    const packingListContent = document.getElementById('packing-list-content');

    generatePackingListBtn.addEventListener('click', async () => {
        const destination = document.getElementById('planner-destination').value;
        const duration = document.getElementById('planner-duration').value;
        const season = document.getElementById('planner-season').value;
        const difficulty = document.getElementById('planner-difficulty').value;

        if (!destination || !duration) {
            showToast("Please provide a destination and duration.", false);
            return;
        }

        packingListOutput.classList.remove('hidden');
        packingListLoader.classList.remove('hidden');
        packingListContent.innerHTML = '';

        const prompt = `Create a detailed packing list for a trek with the following specifics. Use markdown formatting with headings for categories (e.g., ## Clothing, ## Gear, ## Documents).
        
        - **Destination:** ${destination}
        - **Duration:** ${duration} days
        - **Season:** ${season}
        - **Difficulty:** ${difficulty}
        
        Provide specific recommendations where appropriate.`;
        
        const list = await callGeminiAPI(prompt);
        
        let htmlList = list
            .replace(/## (.*)/g, '<h3 class="text-lg font-semibold mt-4">$1</h3>')
            .replace(/\* (.*)/g, '<li class="ml-4">$1</li>')
            .replace(/\n/g, '<br>');

        packingListLoader.classList.add('hidden');
        packingListContent.innerHTML = `<ul>${htmlList}</ul>`;
    });

    // --- Google Maps Initialization & Loading ---
    function initMaps() {
        if (typeof google === 'undefined' || typeof google.maps === 'undefined') {
            console.warn("Google Maps could not be initialized. Using temporary iframe map.");
            
            // Temporary iframe for Treks Map (Centered on Pune region)
            const treksMapHtml = `
                <iframe 
                    width="100%" 
                    height="100%" 
                    frameborder="0" 
                    style="border:0"
                    src="https://maps.google.com/maps?q=Sinhagad+Fort&t=&z=11&ie=UTF8&iwloc=&output=embed"
                    allowfullscreen>
                </iframe>`;
            document.getElementById('treks-map').innerHTML = treksMapHtml;

            // Temporary iframe for Contact Map (Pune City)
            const contactMapHtml = `
                <iframe 
                    width="100%" 
                    height="100%" 
                    frameborder="0" 
                    style="border:0"
                    src="https://maps.google.com/maps?q=Pune+City&t=&z=13&ie=UTF8&iwloc=&output=embed"
                    allowfullscreen>
                </iframe>`;
            document.getElementById('contact-map').innerHTML = contactMapHtml;
            return;
        }

        // Updated Trek Locations for Pune
        const trekLocations = [
            { name: 'Sinhagad Fort', position: { lat: 18.3663, lng: 73.7559 }, description: 'A historic fortress located roughly 30km southwest of Pune. Famous for its steep climb and pithla-bhakri.' },
            { name: 'Lohagad Fort', position: { lat: 18.7066, lng: 73.4807 }, description: 'An easy grade trek near Lonavala, featuring the famous "Vinchu Kata" (Scorpion\'s tail) ridge.' },
            { name: 'Torna Fort', position: { lat: 18.2764, lng: 73.6135 }, description: 'Also known as Prachandagad, this was the first fort captured by Shivaji Maharaj. Highest hill-fort in the district.' },
            { name: 'Rajmachi Fort', position: { lat: 18.8298, lng: 73.4510 }, description: 'Famous for its fireflies festival in pre-monsoon and lush greenery during rains. Twin fortresses: Shrivardhan and Manaranjan.' },
            { name: 'Rajgad Fort', position: { lat: 18.2518, lng: 73.6830 }, description: 'The former capital of the Maratha Empire. Known for its distinct shape and Suvela Machi.' }
        ];

        const bounds = new google.maps.LatLngBounds();
        // Centered on Pune
        const treksMap = new google.maps.Map(document.getElementById('treks-map'), {
            zoom: 9, center: { lat: 18.5204, lng: 73.8567 }, mapTypeControl: false, streetViewControl: false,
        });

        const infoWindow = new google.maps.InfoWindow();
        trekLocations.forEach(trek => {
            const marker = new google.maps.Marker({
                position: trek.position, map: treksMap, title: trek.name, animation: google.maps.Animation.DROP,
            });
            marker.addListener('click', () => {
                infoWindow.setContent(`<strong>${trek.name}</strong><p>${trek.description}</p>`);
                infoWindow.open(treksMap, marker);
            });
            bounds.extend(marker.getPosition());
        });
        treksMap.fitBounds(bounds);

        // Updated Contact Map to Pune City Center
        const contactLocation = { lat: 18.5204, lng: 73.8567 };
        const contactMap = new google.maps.Map(document.getElementById('contact-map'), {
            zoom: 14, center: contactLocation, mapTypeControl: false, streetViewControl: false, zoomControl: false,
        });
        new google.maps.Marker({ position: contactLocation, map: contactMap, title: 'TrekMate HQ Pune' });
    }
    
    function loadGoogleMapsScript() {
        if (GOOGLE_MAPS_API_KEY === 'YOUR_GOOGLE_MAPS_API_KEY') {
            console.warn("Note: Google Maps API Key is a placeholder. The map feature will be disabled until a valid key is provided.");
            initMaps(); // Call to display the placeholder message in the map divs
            return;
        }
        const script = document.createElement('script');
        script.src = `https://maps.googleapis.com/maps/api/js?key=${GOOGLE_MAPS_API_KEY}&callback=initMaps`;
        script.async = true;
        script.defer = true;
        document.head.appendChild(script);
    }

    window.initMaps = initMaps; // Make it globally accessible for the callback
</script>
