<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mehedi Hasan</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        :root {
            --primary-color: #4f46e5;
            --secondary-color: #f59e0b;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        
        .gradient-text {
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .blog-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .menu-open {
            max-height: 500px !important;
            opacity: 1 !important;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="text-xl font-bold text-indigo-600">
                        Mehedi<span class="text-indigo-400">Hasan</span>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-gray-700 hover:text-indigo-600 transition">Home</a>
                    <a href="#blog" class="text-gray-700 hover:text-indigo-600 transition">Blog</a>
                    <a href="#about" class="text-gray-700 hover:text-indigo-600 transition">About</a>
                    <a href="#contact" class="text-indigo-600 hover:text-indigo-700 transition">Contact</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="menuBtn" class="text-gray-700 hover:text-indigo-600 focus:outline-none">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobileMenu" class="md:hidden overflow-hidden max-h-0 opacity-0 transition-all duration-300 ease-in-out">
            <div class="px-2 pt-2 pb-4 space-y-2 sm:px-3 flex flex-col">
                <a href="#home" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-indigo-600">Home</a>
                <a href="#blog" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-indigo-600">Blog</a>
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-indigo-600">About</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-indigo-600 hover:text-indigo-700">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="py-20 bg-gradient-to-r from-indigo-50 to-blue-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center justify-between">
                <div class="md:w-1/2 mb-12 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-6">
                        Welcome to <span class="gradient-text">My Personal Blog</span>
                    </h1>
                    <p class="text-lg text-gray-600 mb-8">
                        Sharing thoughts, ideas, and experiences about work, travel, and everything in between.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#blog" class="px-6 py-3 bg-indigo-600 text-white rounded-lg hover:bg-indigo-700 transition">Read Blog</a>
                        <a href="#about" class="px-6 py-3 border-2 border-indigo-600 text-indigo-600 rounded-lg hover:bg-indigo-50 transition">About Me</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative">
                        <div class="absolute -top-6 -left-6 w-32 h-32 rounded-full bg-indigo-200 opacity-50 animate-pulse"></div>
                        <p><br /></p><div class="separator" style="clear: both; text-align: center;"><div class="separator" style="clear: both; text-align: center;"><a href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhYBtpzvzbN4yvQ9A1p0McppzPb6eE2HVrqjQcmYJ8SKQzj73dJ9JTza1-BFEDLpGpDJiKiBHkmynXsF0MasSWnKCA3nCMtvMOEOf-ABvU3BsFWXuKX18ZigJZlxbuN-lRTdJbkZshPyQ2_QLZ25Hgjq0CjFQpykfHEF5SfeV4gIqq14yHhi4Di0oqbzIgq/s4096/1719781726987.jpg" style="clear: left; float: left; margin-bottom: 1em; margin-right: 1em;"><img border="0" data-original-height="2576" data-original-width="4096" height="439" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhYBtpzvzbN4yvQ9A1p0McppzPb6eE2HVrqjQcmYJ8SKQzj73dJ9JTza1-BFEDLpGpDJiKiBHkmynXsF0MasSWnKCA3nCMtvMOEOf-ABvU3BsFWXuKX18ZigJZlxbuN-lRTdJbkZshPyQ2_QLZ25Hgjq0CjFQpykfHEF5SfeV4gIqq14yHhi4Di0oqbzIgq/w700-h439/1719781726987.jpg" width="700" /></a></div><br /></div><p></p><p><br /></p>
                        <div class="absolute -bottom-6 -right-6 w-32 h-32 rounded-full bg-amber-200 opacity-50 animate-pulse"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Posts -->
    <section class="py-16">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Featured Posts</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Featured Post 1 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-md blog-card transition duration-300">
                    <div class="relative h-48 overflow-hidden">
                     <p><br /></p><div class="separator" style="clear: both; text-align: center;"><div class="separator" style="clear: both; text-align: center;"><a href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhYBtpzvzbN4yvQ9A1p0McppzPb6eE2HVrqjQcmYJ8SKQzj73dJ9JTza1-BFEDLpGpDJiKiBHkmynXsF0MasSWnKCA3nCMtvMOEOf-ABvU3BsFWXuKX18ZigJZlxbuN-lRTdJbkZshPyQ2_QLZ25Hgjq0CjFQpykfHEF5SfeV4gIqq14yHhi4Di0oqbzIgq/s4096/1719781726987.jpg" style="clear: left; float: left; margin-bottom: 1em; margin-right: 1em;"><img border="0" data-original-height="2576" data-original-width="4096" height="439" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhYBtpzvzbN4yvQ9A1p0McppzPb6eE2HVrqjQcmYJ8SKQzj73dJ9JTza1-BFEDLpGpDJiKiBHkmynXsF0MasSWnKCA3nCMtvMOEOf-ABvU3BsFWXuKX18ZigJZlxbuN-lRTdJbkZshPyQ2_QLZ25Hgjq0CjFQpykfHEF5SfeV4gIqq14yHhi4Di0oqbzIgq/w700-h439/1719781726987.jpg" width="700" /></a></div><br /></div><p></p><p><br /></p>
                        <div class="absolute top-4 right-4 bg-indigo-600 text-white px-3 py-1 rounded-full text-sm font-medium">
                            Travel
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex items-center text-sm text-gray-500 mb-2">
                            <span>July 12, 2025</span>
                            <span class="mx-2">•</span>
                            <span>2 min read</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-3">A Day at Chitra Resort, Narail</h3>
                        <p class="text-gray-600 mb-4">Last week, I visited Chitra Resort in Narail, and it was one of the most refreshing trips I’ve had in a while. Nestled by the calm Chitra River, this place felt like a piece of paradise away from the city's chaos..</p>
                        <a href="#" class="text-indigo-600 font-medium hover:text-indigo-700 transition">Read more →</a>
						I took a short ride from Narail town by auto-rickshaw. As I entered, I was greeted by lush greenery, quiet walking paths, and beautifully designed cottages.

The entry fee was only 50 taka. Inside, there was a children’s park, swings, a mini train, and a relaxing natural atmosphere.
I grabbed a coffee at Grounds Café and sat by the river, soaking in the peaceful view. Later, I took a serene boat ride on the river, which was the highlight of my day.
The whole resort is well-maintained, family-friendly, and perfect for nature lovers. Time passed so smoothly that I didn’t realize when it was evening.
By the end of the day, I felt completely recharged. Chitra Resort is truly a hidden gem in southwestern Bangladesh.
I’ll definitely go back again!
                    </div>
                </div>
                
                <!-- Featured Post 2 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-md blog-card transition duration-300">
                    <div class="relative h-48 overflow-hidden">
<p>&nbsp;</p><div class="separator" style="clear: both; text-align: center;"><a href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjIup55bbw8zwiZPGSyTEqQMRGbf_qtDMJ9qgEh0UkKVpkhZiEY4fxAMlRAvcEkuiDNXKpPRvfuILJmTsyIN-tM5yplHHwFPS7-W0FrlyXRsGVoj4uB4jcEUgKqj6BiBmpmSu1qfvCRH0oqSILj8QlQnSmMyI1-UcPoaCLOlFt-15aZAgnckfJM__IWcfaS/s2160/WhatsApp%20Image%202025-05-18%20at%2020.27.42%20(2).jpeg" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="2160" data-original-width="2159" height="200" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjIup55bbw8zwiZPGSyTEqQMRGbf_qtDMJ9qgEh0UkKVpkhZiEY4fxAMlRAvcEkuiDNXKpPRvfuILJmTsyIN-tM5yplHHwFPS7-W0FrlyXRsGVoj4uB4jcEUgKqj6BiBmpmSu1qfvCRH0oqSILj8QlQnSmMyI1-UcPoaCLOlFt-15aZAgnckfJM__IWcfaS/w199-h200/WhatsApp%20Image%202025-05-18%20at%2020.27.42%20(2).jpeg" width="199" /></a></div><br /><p></p>                        <div class="absolute top-4 right-4 bg-amber-500 text-white px-3 py-1 rounded-full text-sm font-medium">
                            Travel
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex items-center text-sm text-gray-500 mb-2">
                            <span>May 28, 2024</span>
                            <span class="mx-2">•</span>
                            <span> min read</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-3">A Glimpse into Khulna–Bagerhat: My Short Escape</h3>
                        <p class="text-gray-600 mb-4">I recently took a short trip from Khulna to Bagerhat, and it felt like stepping into history.</p>
                        <a href="#" class="text-indigo-600 font-medium hover:text-indigo-700 transition">Read more →</a>
						Khulna greeted me with the calm of the Rupsha River and the taste of fresh seafood like chingri malai curry.
The next morning, I visited the iconic Sixty Dome Mosque—majestic, silent, and soaked in heritage.
Walking through its ancient halls felt surreal, like time had paused.
I also visited Khan Jahan Ali’s Mazar, where peace seemed to float in the air.
The Nine Dome Mosque and Ghora Dighi added more beauty to the day.
Bagerhat’s charm lies not just in its architecture, but in its silence and soul.
The trip was short, but the memories will last long.
If you love history, quiet beauty, and riverside towns—this journey is for you.
Khulna–Bagerhat isn’t just a trip, it’s a timeless experience.</p>
                    </div>
                </div>
                
                <!-- Featured Post 3 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-md blog-card transition duration-300">
                    <div class="relative h-48 overflow-hidden">
                      <p>&nbsp;</p><div class="separator" style="clear: both; text-align: center;"><a href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg9a9yuYkzylwZjc57504AiedSIiqfFJ_DNGTMv4GLKAVrDjnFHpkKESXQ_uW-vSOSCvWXg7nFPGWMcCaa4TSLVaW6Swr7FyZKcA51d-Wg-Y4IkNX04zvYQcCvF9aa3uyG-23Fo7gx6qXvV0vjdJWI5nnB6rohu02GvdQO4y6Jz7BXTs3ZxcYSkT3e_nYhyphenhyphen/s1920/WhatsApp%20Image%202025-06-22%20at%2022.34.49.jpeg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="1082" data-original-width="1920" height="180" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg9a9yuYkzylwZjc57504AiedSIiqfFJ_DNGTMv4GLKAVrDjnFHpkKESXQ_uW-vSOSCvWXg7nFPGWMcCaa4TSLVaW6Swr7FyZKcA51d-Wg-Y4IkNX04zvYQcCvF9aa3uyG-23Fo7gx6qXvV0vjdJWI5nnB6rohu02GvdQO4y6Jz7BXTs3ZxcYSkT3e_nYhyphenhyphen/s320/WhatsApp%20Image%202025-06-22%20at%2022.34.49.jpeg" width="320" /></a></div><br />                        <div class="absolute top-4 right-4 bg-emerald-500 text-white px-3 py-1 rounded-full text-sm font-medium">
                            Lifestyle
                        </div>
                    </div>
                    <div class="p-6">
                        <div class="flex items-center text-sm text-gray-500 mb-2">
                            <span>April 15, 2023</span>
                            <span class="mx-2">•</span>
                            <span>1 min read</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-3">Riding a bike isn’t just a way to move—</h3>
                        <p class="text-gray-600 mb-4">it's a way to live.
                                     It gives you freedom, fresh air, and a break from the chaos.</p>
                        <a href="#" class="text-indigo-600 font-medium hover:text-indigo-700 transition">Read more →</a>
						Each ride clears the mind and strengthens the body.
You see the world differently when you're on two wheels.
For me, biking is balance—between adventure and peace.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Posts Section -->
    <section id="blog" class="py-16 bg-gray-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-4">Latest Posts</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">Explore my recent thoughts and writings on various topics that interest me.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Blog Post 1 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-sm blog-card transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="null" alt="Modern office setup with ergonomic chair, laptop, and second monitor on a standing desk" class="w-full h-full object-cover">
                    </div>
                    <div class="p-5">
                        <span class="inline-block px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-xs font-medium mb-2">Productivity</span>
                        <h3 class="text-lg font-bold text-gray-800 mb-2">Remote Work Productivity Hacks</h3>
                        <p class="text-sm text-gray-600 mb-3">Essential tools and techniques for maintaining productivity while working from home.</p>
                        <div class="flex items-center text-xs text-gray-500">
                            <span>June 5, 2023</span>
                            <span class="mx-2">•</span>
                            <span>4 min read</span>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 2 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-sm blog-card transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="null" alt="Hand holding smartphone with various app icons visible on the screen showing UI design" class="w-full h-full object-cover">
                    </div>
                    <div class="p-5">
                        <span class="inline-block px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-xs font-medium mb-2">Design</span>
                        <h3 class="text-lg font-bold text-gray-800 mb-2">UI Design Trends 2023</h3>
                        <p class="text-sm text-gray-600 mb-3">Examining the most influential user interface design trends shaping digital experiences this year.</p>
                        <div class="flex items-center text-xs text-gray-500">
                            <span>May 20, 2023</span>
                            <span class="mx-2">•</span>
                            <span>7 min read</span>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 3 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-sm blog-card transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="null" alt="Fresh ingredients arranged on kitchen counter including vegetables, herbs, and olive oil" class="w-full h-full object-cover">
                    </div>
                    <div class="p-5">
                        <span class="inline-block px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-xs font-medium mb-2">Food</span>
                        <h3 class="text-lg font-bold text-gray-800 mb-2">Healthy Meal Prep for Busy People</h3>
                        <p class="text-sm text-gray-600 mb-3">Simple recipes and strategies for preparing nutritious meals in advance.</p>
                        <div class="flex items-center text-xs text-gray-500">
                            <span>May 8, 2023</span>
                            <span class="mx-2">•</span>
                            <span>5 min read</span>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 4 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-sm blog-card transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="null" alt="Bookshelf filled with books on various topics with a cozy reading chair nearby" class="w-full h-full object-cover">
                    </div>
                    <div class="p-5">
                        <span class="inline-block px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-xs font-medium mb-2">Books</span>
                        <h3 class="text-lg font-bold text-gray-800 mb-2">Summer Reading List 2023</h3>
                        <p class="text-sm text-gray-600 mb-3">My curated selection of books across fiction, non-fiction and biographies for summer.</p>
                        <div class="flex items-center text-xs text-gray-500">
                            <span>April 25, 2023</span>
                            <span class="mx-2">•</span>
                            <span>6 min read</span>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 5 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-sm blog-card transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/b6a9ac1e-a57e-4310-864f-203c7faefd3a.png" alt="Gadgets including smartwatch, wireless earbuds, and smartphone arranged neatly" class="w-full h-full object-cover">
                    </div>
                    <div class="p-5">
                        <span class="inline-block px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-xs font-medium mb-2">Gadgets</span>
                        <h3 class="text-lg font-bold text-gray-800 mb-2">Essential Tech for Digital Nomads</h3>
                        <p class="text-sm text-gray-600 mb-3">Must-have gadgets and accessories for tech-savvy professionals working remotely.</p>
                        <div class="flex items-center text-xs text-gray-500">
                            <span>April 10, 2023</span>
                            <span class="mx-2">•</span>
                            <span>8 min read</span>
                        </div>
                    </div>
                </div>
                
                <!-- Blog Post 6 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-sm blog-card transition duration-300">
                    <div class="h-48 overflow-hidden">
                        <img src="null" alt="Person journaling at a wooden desk with fountain pen and notebook under warm lighting" class="w-full h-full object-cover">
                    </div>
                    <div class="p-5">
                        <span class="inline-block px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-xs font-medium mb-2">Mindset</span>
                        <h3 class="text-lg font-bold text-gray-800 mb-2">Journaling for Self-Discovery</h3>
                        <p class="text-sm text-gray-600 mb-3">How maintaining a daily journaling practice can lead to greater self-awareness.</p>
                        <div class="flex items-center text-xs text-gray-500">
                            <span>March 28, 2023</span>
                            <span class="mx-2">•</span>
                            <span>5 min read</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-flex items-center px-6 py-3 border border-gray-300 bg-white text-gray-700 rounded-lg hover:bg-gray-50 transition">
                    View All Posts
                    <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-2/5 mb-8 md:mb-0 md:mr-12">
                    <img src="null" alt="Portrait of a professional blogger in casual attire standing against a brick wall" class="rounded-lg shadow-lg w-full">
                </div>
                <div class="md:w-3/5">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6">About Me</h2>
                    <p class="text-gray-600 mb-4">
                        Hello! I'm Alex, a writer, traveler, and technology enthusiast. I started this blog as a way to share my thoughts and experiences across different areas of my life and interests.
                    </p>
                    <p class="text-gray-600 mb-6">
                        With a background in computer science and a passion for storytelling, I enjoy exploring the intersection between technology and human experiences. When I'm not writing or coding, you can find me hiking mountains or trying out new recipes in the kitchen.
                    </p>
                    <div class="grid grid-cols-2 gap-6 mb-8">
                        <div>
                            <h3 class="text-lg font-semibold text-gray-800 mb-2">My Interests</h3>
                            <ul class="text-gray-600">
                                <li class="mb-1">Technology Trends</li>
                                <li class="mb-1">Minimalist Living</li>
                                <li class="mb-1">Outdoor Adventures</li>
                                <li class="mb-1">Photography</li>
                            </ul>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold text-gray-800 mb-2">Currently</h3>
                            <ul class="text-gray-600">
                                <li class="mb-1">📚 Reading: Atomic Habits</li>
                                <li class="mb-1">🎧 Listening: Syntax Podcast</li>
                                <li class="mb-1">📍 Location: Portland, OR</li>
                            </ul>
                        </div>
                    </div>
                    <div class="flex space-x-4">
                        <a href="#" class="px-6 py-3 bg-indigo-600 text-white rounded-lg hover:bg-indigo-700 transition">Download CV</a>
                        <a href="#" class="px-6 py-3 border-2 border-gray-300 text-gray-700 rounded-lg hover:bg-gray-100 transition">More About Me</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="py-16 bg-indigo-50">
        <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="bg-white p-8 rounded-lg shadow-sm">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">Stay Updated</h2>
                <p class="text-gray-600 mb-6">Subscribe to my newsletter to receive updates on new posts and occasional exclusive content.</p>
                <form class="flex flex-col sm:flex-row gap-3">
                    <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none">
                    <button type="submit" class="px-6 py-3 bg-indigo-600 text-white rounded-lg hover:bg-indigo-700 transition">Subscribe</button>
                </form>
                <p class="text-xs text-gray-500 mt-3">I respect your privacy. Unsubscribe at any time.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-800 text-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-12">Get In Touch</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="bg-indigo-600 rounded-full w-12 h-12 flex items-center justify-center mx-auto mb-4">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-lg font-semibold mb-2">Email</h3>
                    <p class="text-gray-400">mehedihasanajmir1000@gmail.com</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-indigo-600 rounded-full w-12 h-12 flex items-center justify-center mx-auto mb-4">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                        </svg>
                    </div>
                    <h3 class="text-lg font-semibold mb-2">Phone</h3>
                    <p class="text-gray-400">+880 1946406095</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-indigo-600 rounded-full w-12 h-12 flex items-center justify-center mx-auto mb-4">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                        </svg>
                    </div>
                    <h3 class="text-lg font-semibold mb-2">Location</h3>
                    <p class="text-gray-400">Narail,Khulna,Bangladesh</p>
                </div>
            </div>
            
            <div class="mt-12">
                <h3 class="text-lg font-semibold text-center mb-4">Connect on Social Media</h3>
                <div class="flex justify-center space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"></path>
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.858.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.354-.3.883-.344 1.818-.033.812-.01 1.747.02 2.578v.093c0 2.253.01 2.598.048 3.637.045.915.207 1.445.344 1.8.182.466.399.8.75 1.15.35.35.683.566 1.15.748.354.137.883.3 1.818.344 1.055.048 1.37.056 4.041.056h.08c2.597 0 2.917-.008 3.96-.056.915-.045 1.442-.207 1.797-.344.466-.182.8-.398 1.15-.75.35-.35.566-.683.747-1.15.137-.354.3-.883.345-1.812.048-1.055.055-1.37.055-4.041v-.08c0-2.597-.008-2.917-.056-3.96-.045-.915-.207-1.442-.344-1.797a3.097 3.097 0 00-.749-1.15 3.098 3.098 0 00-1.15-.749c-.354-.137-.882-.3-1.815-.344-1.03-.051-1.388-.058-3.808-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z" clip-rule="evenodd"></path>
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
                        </svg>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path fill-rule="evenodd" d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.419-.312-4.94.186-.75.281-1.344.703-1.712 1.328-.374.656-.465 1.349-.328 2.032.28 1.283.936 2.394 1.924 3.023a8.487 8.487 0 01-5.02 1.507c-4.689 0-8.478-3.806-8.478-8.49 0-4.689 3.806-8.487 8.496-8.487 2.131 0 4.133.819 5.642 2.295.232.225.438.468.608.729.133.222.164.492.096.744-.204.843-.255 1.68-.204 2.57.105.843.538 1.514 1.186 1.788.656.281 1.364.12 1.944-.281.12-.095 4.492-4.133 4.929-4.714.134-.156.191-.338.216-.517.06-.627-.276-1.221-.809-1.465-.608-.268-1.482-.06-2.312.376a15.613 15.613 0 01-4.373 1.752c-.633.12-1.233-.204-1.542-.778-.061-.118-.09-.247-.104-.369-.06-.633.265-1.226.791-1.482.989-.468 2.312-.738 3.744-.507.902.105 1.772.296 2.592.59.51.197.937.503 1.248.864.192.21.312.472.312.759 0 .191-.05.37-.145.535-.276.538-.944 1.149-1.812 1.729a15.62 15.62 0 01-2.958 1.481c-.36.104-.753.121-1.107.06-.466-.09-.862-.422-1.038-.881-.165-.464-.105-.952.18-1.34.314-.433.88-.699 1.517-.703.495-.001.975.121 1.384.338.422.229.765.56.982.933.21.362.321.78.321 1.213 0 .204-.03.395-.09.57-.255.763-.909 1.378-1.762 1.686a8.442 8.442 0 01-3.024.538c-2.718 0-5.171-1.215-6.774-3.182-.844.328-1.594.703-2.221 1.104-.06.054-.09.096-.12.141a8.55 8.55 0 01-1.011-2.303 8.624 8.624 0 012.834-8.875c.255-.156.563-.246.883-.246.332 0 .642.093.897.267l2.79 1.839a1.518 1.518 0 01.507.518c.104.18.18.375.204.575.06.329.06.645 0 .96-.09.639-.321 1.236-.66 1.762-.199.33-.453.613-.759.842-.257.193-.546.33-.853.397a1.557 1.557 0 01-.6.015c-.282-.06-.543-.21-.744-.435a1.567 1.567 0 01-.255-.882c0-.142.04-.286.121-.411.145-.225.368-.394.624-.494.421-.169.882-.202 1.323-.111.636.12 1.193.479 1.572 1.001.397.555.621 1.227.645 1.923.016.562-.174 1.111-.535 1.529a1.836 1.836 0 01-1.416.644c-.371 0-.729-.111-1.029-.314a1.812 1.812 0 01-.689-.916c-.141-.422-.106-.877.105-1.27.218-.411.592-.711 1.039-.808.39-.082.798.039 1.085.311.487.447.885 1.001 1.096 1.618.27.784.379 1.619.321 2.46-.03.398-.133.78-.312 1.133-.338.633-1.114 1.031-1.872 1.114z" clip-rule="evenodd"></path>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-gray-900 text-gray-400">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <div class="text-lg font-bold text-white">
                        Mehedi<span class="text-indigo-400">Hasan</span>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row items-center md:space-x-6 text-sm">
                    <a href="#" class="hover:text-white transition">Privacy Policy</a>
                    <a href="#" class="hover:text-white transition">Terms of Service</a>
                    <a href="#" class="hover:text-white transition">Cookie Policy</a>
                    <a href="#" class="hover:text-white transition">Sitemap</a>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-sm">
                <p>© 2017 My Personal Blog. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('menuBtn').addEventListener('click', function() {
            const menu = document.getElementById('mobileMenu');
            menu.classList.toggle('menu-open');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    window.scrollTo({
                        top: target.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>

The future holds good things in my life.
