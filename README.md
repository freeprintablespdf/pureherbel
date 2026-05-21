<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pure Herble - Natural Hair Care</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Animate.css for smooth animations -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        .serif-font {
            font-family: 'Playfair Display', serif;
        }
        /* Custom Floating Animation for Product Image */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
        .floating-img {
            animation: float 4s ease-in-out infinite;
        }
        /* Custom Gradient Background */
        .bg-herbal-gradient {
            background: linear-gradient(135deg, #f4f7f4 0%, #e6ebe4 100%);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 antialiased">

    <!-- HEADER / NAVIGATION -->
    <header class="fixed w-full bg-white/80 backdrop-blur-md shadow-sm z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Logo Area -->
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 bg-emerald-700 rounded-full flex items-center justify-center text-white font-bold text-xl shadow-md">
                    <!-- Placeholder Logo Icon -->
                    <i class="fa-solid fa-leaf"></i>
                </div>
                <span class="text-2xl font-bold tracking-wide text-emerald-800 serif-font">Pure Herble</span>
            </div>
            
            <!-- Nav Links -->
            <nav class="hidden md:flex space-x-8 font-medium text-emerald-900">
                <a href="#home" class="hover:text-emerald-600 transition">Home</a>
                <a href="#about" class="hover:text-emerald-600 transition">About Us</a>
                <a href="#products" class="hover:text-emerald-600 transition">Our Products</a>
            </nav>

            <!-- Contact CTA -->
            <a href="tel:03432802357" class="inline-flex items-center px-5 py-2.5 bg-emerald-700 hover:bg-emerald-800 text-white font-semibold rounded-full shadow-md hover:shadow-lg transform hover:-translate-y-0.5 transition duration-200">
                <i class="fa-solid fa-phone mr-2 animate-pulse"></i> 0343-2802357
            </a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="pt-32 pb-20 md:pt-40 md:pb-28 bg-herbal-gradient overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <!-- Left Text Content -->
                <div class="animate__animated animate__fadeInLeft">
                    <span class="text-emerald-700 font-bold uppercase tracking-widest text-sm block mb-3">100% Organic & Chemical Free</span>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight serif-font mb-6">
                        Revitalize Your Hair <br><span class="text-emerald-700">Naturally</span>
                    </h1>
                    <p class="text-gray-600 text-lg mb-8 leading-relaxed">
                        Say goodbye to hair fall and chemical damage. Experience the ultimate holistic care with our hand-crafted, nutrient-rich herbal shampoo and premium oil blend.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#products" class="px-8 py-3.5 bg-emerald-700 hover:bg-emerald-800 text-white font-bold rounded-lg shadow-lg hover:shadow-xl transition duration-300">Shop Now</a>
                        <a href="#about" class="px-8 py-3.5 bg-white hover:bg-gray-100 text-emerald-800 font-bold rounded-lg shadow-md transition duration-300 border border-gray-200">Learn More</a>
                    </div>
                </div>

                <!-- Right Image Showcase -->
                <div class="relative flex justify-center items-center animate__animated animate__fadeInRight">
                    <!-- Decorative back circles -->
                    <div class="absolute w-72 h-72 sm:w-96 sm:h-96 bg-emerald-200/50 rounded-full blur-3xl -z-10"></div>
                    <!-- Main Product Image Placeholder -->
                    <div class="floating-img bg-white p-6 rounded-3xl shadow-2xl border border-emerald-50/50 max-w-sm sm:max-w-md w-full aspect-[4/5] flex flex-col justify-center items-center relative overflow-hidden group">
                        <!-- Replace the source inside src="" with your actual photo path later -->
                        <img src="images/shampoo.jpeg" alt="Pure Herble Hair Combo" class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition duration-700">
                        <div class="absolute inset-0 bg-black/10"></div>
                        <span class="absolute bottom-4 left-4 bg-emerald-800 text-white text-xs font-bold uppercase px-3 py-1 rounded-full tracking-wider shadow-md">Premium Combo</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT US & INGREDIENTS SECTION -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <span class="text-emerald-700 font-bold uppercase tracking-widest text-sm block mb-2">Our Secret Recipe</span>
            <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 serif-font mb-6">About Pure Herble</h2>
            <div class="w-24 h-1 bg-emerald-700 mx-auto mb-8 rounded-full"></div>
            
            <!-- Formatted Paragraph Requirement -->
            <p class="text-gray-600 text-lg sm:text-xl leading-relaxed max-w-4xl mx-auto mb-12">
                Our signature herbal shampoo and oil are meticulously crafted with a potent, time-tested blend of nature's finest treasures. Infused with <strong>amla, retha, shikakai, hibiscus flower, bhringraj powder, rosemary leaves, and fenugreek seeds</strong>, complemented by therapeutic <strong>essential oils and other organic herbs</strong>, our formula repairs your hair from root to tip. This powerhouse combo stops hair fall, treats dandruff, stimulates rapid regrowth, and restores your hair's natural, vibrant shine without a single harsh chemical.
            </p>

            <!-- Quick Ingredient Tags for Visual Appeal -->
            <div class="flex flex-wrap justify-center gap-3 max-w-3xl mx-auto">
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-seedling mr-1.5 text-emerald-600"></i> Amla</span>
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-seedling mr-1.5 text-emerald-600"></i> Retha</span>
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-seedling mr-1.5 text-emerald-600"></i> Shikakai</span>
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-flower mr-1.5 text-emerald-600"></i> Hibiscus Flower</span>
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-mortar-pestle mr-1.5 text-emerald-600"></i> Bhringraj</span>
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-leaf mr-1.5 text-emerald-600"></i> Rosemary Leaves</span>
                <span class="bg-emerald-50 text-emerald-800 text-sm font-semibold px-4 py-2 rounded-full border border-emerald-100 shadow-sm"><i class="fa-solid fa-droplet mr-1.5 text-emerald-600"></i> Essential Oils</span>
            </div>
        </div>
    </section>

    <!-- PRODUCTS SECTION -->
    <section id="products" class="py-20 bg-emerald-50/50 border-t border-b border-emerald-100/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-emerald-700 font-bold uppercase tracking-widest text-sm block mb-2">Pricing & Availability</span>
                <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 serif-font">Choose Your Pure Care</h2>
                <p class="text-gray-500 mt-2">Premium quality at unbeatable, pocket-friendly prices</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <!-- Product 1: Shampoo -->
                <div class="bg-white rounded-2xl shadow-xl overflow-hidden transform hover:-translate-y-2 transition duration-300 border border-gray-100 flex flex-col justify-between group">
                    <div class="p-6">
                        <!-- Product Image Placeholder -->
                        <div class="w-full h-64 bg-gray-100 rounded-xl mb-6 relative overflow-hidden">
                            <img src="images/shampoo.jpeg" alt="Pure Herble Shampoo" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <span class="text-xs font-bold uppercase tracking-wider text-emerald-700 bg-emerald-50 px-2.5 py-1 rounded-full">Hair Cleanser</span>
                        <h3 class="text-2xl font-bold text-gray-900 mt-3 mb-2 serif-font">Pure Herble Shampoo</h3>
                        <p class="text-gray-600 text-sm leading-relaxed">
                            Deeply cleanses dirt and pollutant buildup while gently conditioning the scalp with Amla and Reetha properties.
                        </p>
                    </div>
                    <div class="p-6 bg-gray-50 border-t border-gray-100 flex items-center justify-between">
                        <div>
                            <p class="text-xs text-gray-400 font-semibold uppercase">Price</p>
                            <p class="text-2xl font-black text-emerald-800">550 <span class="text-sm font-bold text-emerald-700">PKR</span></p>
                        </div>
                        <a href="https://wa.me/923432802357?text=Hi,%20I%20want%20to%20order%20the%20Pure%20Herble%20Shampoo." target="_blank" class="px-5 py-2.5 bg-emerald-700 hover:bg-emerald-800 text-white font-semibold rounded-lg shadow transition flex items-center gap-2 text-sm">
                            <i class="fa-brands fa-whatsapp text-lg"></i> Order Now
                        </a>
                    </div>
                </div>

                <!-- Product 2: Oil -->
                <div class="bg-white rounded-2xl shadow-xl overflow-hidden transform hover:-translate-y-2 transition duration-300 border border-gray-100 flex flex-col justify-between group">
                    <div class="p-6">
                        <!-- Product Image Placeholder -->
                        <div class="w-full h-64 bg-gray-100 rounded-xl mb-6 relative overflow-hidden">
                            <img src="images/oil.jpeg" alt="Pure Herble Oil" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <span class="text-xs font-bold uppercase tracking-wider text-emerald-700 bg-emerald-50 px-2.5 py-1 rounded-full">Root Nourishment</span>
                        <h3 class="text-2xl font-bold text-gray-900 mt-3 mb-2 serif-font">Pure Herble Hair Oil</h3>
                        <p class="text-gray-600 text-sm leading-relaxed">
                            Infused with Bhringraj, Rosemary, and rich essential oils to penetrate deep into roots, minimizing shedding and fueling growth.
                        </p>
                    </div>
                    <div class="p-6 bg-gray-50 border-t border-gray-100 flex items-center justify-between">
                        <div>
                            <p class="text-xs text-gray-400 font-semibold uppercase">Price</p>
                            <p class="text-2xl font-black text-emerald-800">400 <span class="text-sm font-bold text-emerald-700">PKR</span></p>
                        </div>
                        <a href="https://wa.me/923432802357?text=Hi,%20I%20want%20to%20order%20the%20Pure%20Herble%20Hair%20Oil." target="_blank" class="px-5 py-2.5 bg-emerald-700 hover:bg-emerald-800 text-white font-semibold rounded-lg shadow transition flex items-center gap-2 text-sm">
                            <i class="fa-brands fa-whatsapp text-lg"></i> Order Now
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER / CONTACT INFO -->
    <footer class="bg-emerald-950 text-gray-300 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <!-- Brand Logo / Identity -->
            <div class="flex justify-center items-center space-x-3 mb-6">
                <div class="w-8 h-8 bg-emerald-600 rounded-full flex items-center justify-center text-white font-bold text-sm">
                    <i class="fa-solid fa-leaf"></i>
                </div>
                <span class="text-xl font-bold text-white serif-font tracking-wide">Pure Herble</span>
            </div>

            <!-- Fast Contact Methods -->
            <p class="text-lg text-gray-200 mb-2 font-medium">Have Questions? Order Directly via Call or WhatsApp</p>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4 my-6">
                <a href="tel:03432802357" class="text-2xl text-emerald-400 hover:text-emerald-300 transition font-bold tracking-wider">
                    <i class="fa-solid fa-phone text-lg mr-2 text-white"></i> 0343-2802357
                </a>
            </div>

            <div class="w-full h-[1px] bg-emerald-900 my-8"></div>

            <!-- Footnotes -->
            <p class="text-sm text-emerald-600/80">&copy; 2026 Pure Herble. All Rights Reserved. Crafted for Natural Radiance.</p>
        </div>
    </footer>

</body>
</html>
