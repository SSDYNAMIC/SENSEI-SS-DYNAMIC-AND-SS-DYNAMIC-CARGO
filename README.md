# SENSEI-SS-DYNAMIC-AND-SS-DYNAMIC-CARGO
SENSEI SS DYNAMIC AND SS DYNAMIC CARGO
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SS DYNAMIC SENSEI BORONG CHINA & SS DYNAMIC CARGO - China to Malaysia Logistics</title>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
<style>
    :root {
        --primary-red: #B91C1C;
        --primary-black: #111827;
        --accent-red: #DC2626;
        --dark-black: #030712;
    }
    
    * {
        scroll-behavior: smooth;
    }
    
    body {
        font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    }
    
    .hero-bg {
        background: linear-gradient(135deg, rgba(17, 24, 39, 0.95) 0%, rgba(185, 28, 28, 0.9) 100%), 
                    url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?q=80&w=2070') center/cover;
    }
    
    .flag-banner {
        background: linear-gradient(90deg, 
            #B91C1C 0%, 
            #B91C1C 48%, 
            #111827 52%, 
            #111827 100%);
        position: relative;
    }
    
    .flag-banner::before {
        content: '🇨🇳';
        position: absolute;
        left: 25%;
        top: 50%;
        transform: translate(-50%, -50%);
        font-size: 2.5rem;
    }
    
    .flag-banner::after {
        content: '🇲🇾';
        position: absolute;
        right: 25%;
        top: 50%;
        transform: translate(50%, -50%);
        font-size: 2.5rem;
    }
    
    .glass-effect {
        background: rgba(255, 255, 255, 0.95);
        backdrop-filter: blur(10px);
        box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.15);
    }
    
    .card-hover {
        transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
    
    .card-hover:hover {
        transform: translateY(-8px);
        box-shadow: 0 20px 40px rgba(185, 28, 28, 0.2);
    }
    
    .btn-primary {
        background: linear-gradient(135deg, #B91C1C 0%, #DC2626 100%);
        transition: all 0.3s ease;
        position: relative;
        overflow: hidden;
    }
    
    .btn-primary:hover {
        transform: translateY(-2px);
        box-shadow: 0 10px 25px rgba(185, 28, 28, 0.4);
    }
    
    .input-focus:focus {
        outline: none;
        border-color: #DC2626;
        box-shadow: 0 0 0 3px rgba(220, 38, 38, 0.1);
    }
    
    .section-divider {
        height: 4px;
        background: linear-gradient(90deg, transparent, #B91C1C, transparent);
    }
    
    @keyframes fadeInUp {
        from {
            opacity: 0;
            transform: translateY(30px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }
    
    .animate-fade-in {
        animation: fadeInUp 0.6s ease-out;
    }
    
    .sticky-nav {
        backdrop-filter: blur(12px);
        background: rgba(17, 24, 39, 0.98);
    }
    
    .mobile-menu {
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.3s ease-in-out;
    }
    
    .mobile-menu.active {
        max-height: 500px;
    }
    
    input[type="number"]::-webkit-inner-spin-button,
    input[type="number"]::-webkit-outer-spin-button {
        opacity: 1;
    }
    
    .upload-preview {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
        gap: 8px;
        margin-top: 12px;
    }
    
    .upload-preview img {
        width: 100%;
        height: 80px;
        object-fit: cover;
        border-radius: 8px;
        border: 2px solid #DC2626;
    }
    
    .converter-badge {
        background: linear-gradient(135deg, #B91C1C 0%, #111827 100%);
    }
</style>
</head>
<body class="bg-gray-50 text-gray-900">
    
    <!-- Navigation -->
    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16 md:h-20">
                <div class="flex items-center space-x-3">
                    <div class="w-12 h-12 bg-gradient-to-br from-red-600 to-red-800 rounded-lg flex items-center justify-center">
                        <i class="fas fa-shipping-fast text-white text-xl"></i>
                    </div>
                    <div class="flex flex-col">
                        <span class="text-white font-bold text-sm md:text-lg leading-tight">SS DYNAMIC SENSEI</span>
                        <span class="text-red-500 text-xs md:text-sm font-semibold">BORONG CHINA & CARGO</span>
                    </div>
                </div>
                
                <div class="hidden lg:flex items-center space-x-8">
                    <a href="#home" class="text-gray-300 hover:text-red-500 transition-colors font-medium">Home</a>
                    <a href="#about" class="text-gray-300 hover:text-red-500 transition-colors font-medium">About</a>
                    <a href="#services" class="text-gray-300 hover:text-red-500 transition-colors font-medium">Services</a>
                    <a href="#calculator" class="text-gray-300 hover:text-red-500 transition-colors font-medium">Converters</a>
                    <a href="#request" class="text-gray-300 hover:text-red-500 transition-colors font-medium">Request Form</a>
                    <a href="#contact" class="text-gray-300 hover:text-red-500 transition-colors font-medium">Contact</a>
                </div>
                
                <button id="mobile-menu-btn" class="lg:hidden text-white focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
            
            <div id="mobile-menu" class="mobile-menu lg:hidden">
                <div class="py-4 space-y-3">
                    <a href="#home" class="block text-gray-300 hover:text-red-500 transition-colors font-medium py-2">Home</a>
                    <a href="#about" class="block text-gray-300 hover:text-red-500 transition-colors font-medium py-2">About</a>
                    <a href="#services" class="block text-gray-300 hover:text-red-500 transition-colors font-medium py-2">Services</a>
                    <a href="#calculator" class="block text-gray-300 hover:text-red-500 transition-colors font-medium py-2">Converters</a>
                    <a href="#request" class="block text-gray-300 hover:text-red-500 transition-colors font-medium py-2">Request Form</a>
                    <a href="#contact" class="block text-gray-300 hover:text-red-500 transition-colors font-medium py-2">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg min-h-screen flex items-center pt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 w-full">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="text-white animate-fade-in">
                    <div class="flag-banner h-16 rounded-full mb-6 flex items-center justify-center">
                        <i class="fas fa-arrow-right text-white text-2xl"></i>
                    </div>
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold mb-6 leading-tight">
                        SS DYNAMIC SENSEI<br>
                        <span class="text-red-400">BORONG CHINA & SS DYNAMIC CARGO</span>
                    </h1>
                    <p class="text-xl md:text-2xl font-semibold mb-4 text-red-100">
                        YOUR LOGISTICS PARTNERS CARGO FORWARDER
                    </p>
                    <p class="text-lg md:text-xl mb-8 text-gray-200 leading-relaxed">
                        WE HELP MANAGE THE PURCHASE AND DELIVERY OF YOUR PRODUCTS ITEMS FROM 🇨🇳CHINA🇨🇳 TO 🇲🇾MALAYSIA🇲🇾
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#request" class="btn-primary text-white px-8 py-4 rounded-lg font-bold text-lg inline-flex items-center gap-2">
                            <i class="fas fa-box"></i> Request Quote
                        </a>
                        <a href="#calculator" class="bg-white text-gray-900 px-8 py-4 rounded-lg font-bold text-lg inline-flex items-center gap-2 hover:bg-gray-100 transition">
                            <i class="fas fa-calculator"></i> CBM Calculator
                        </a>
                    </div>
                </div>
                
                <div class="glass-effect rounded-2xl p-6 md:p-8 animate-fade-in">
                    <h3 class="text-2xl font-bold text-gray-900 mb-2">AUTOMATIC PRODUCT SEARCH ENGINE</h3>
                    <p class="text-sm text-red-600 mb-4 font-semibold">
                        <i class="fas fa-bolt"></i> Auto-opens on paste
                    </p>
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Product Link from 1688 / Taobao / Alibaba</label>
                            <input type="url" id="productLink" placeholder="Paste your product link here..." 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus transition">
                        </div>
                        <button onclick="openProductLink()" class="w-full btn-primary text-white py-3 rounded-lg font-bold inline-flex items-center justify-center gap-2">
                            <i class="fas fa-external-link-alt"></i> Open in New Tab
                        </button>
                        <p class="text-xs text-gray-600 text-center bg-yellow-50 p-2 rounded">
                            <i class="fas fa-info-circle text-red-600"></i> Link auto-opens 1.5s after you paste
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-16 md:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-extrabold text-gray-900 mb-4">About SS Dynamic Sensei</h2>
                <div class="section-divider w-24 mx-auto mb-6"></div>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">
                    Your trusted partner for China 🇨🇳 to Malaysia 🇲🇾 logistics and sourcing solutions
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="card-hover bg-gradient-to-br from-gray-900 to-gray-800 text-white p-8 rounded-2xl">
                    <div class="w-16 h-16 bg-red-600 rounded-xl flex items-center justify-center mb-6">
                        <i class="fas fa-handshake text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Professional Service</h3>
                    <p class="text-gray-300">We provide end-to-end logistics solutions from product sourcing to final delivery across Malaysia.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-red-600 to-red-700 text-white p-8 rounded-2xl">
                    <div class="w-16 h-16 bg-white rounded-xl flex items-center justify-center mb-6">
                        <i class="fas fa-dollar-sign text-3xl text-red-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Competitive Rates</h3>
                    <p class="text-gray-100">Get the best shipping rates from China with transparent CBM pricing and no hidden fees.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-gray-900 to-gray-800 text-white p-8 rounded-2xl">
                    <div class="w-16 h-16 bg-red-600 rounded-xl flex items-center justify-center mb-6">
                        <i class="fas fa-clock text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Fast Delivery</h3>
                    <p class="text-gray-300">Sea & air freight options with tracking. Sea: 10-18 days, Air: 5-7 days to Malaysia.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-extrabold text-gray-900 mb-4">Our Services</h2>
                <div class="section-divider w-24 mx-auto mb-6"></div>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">
                    Comprehensive logistics solutions tailored for your business needs
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-white p-6 rounded-xl shadow-lg card-hover">
                    <i class="fas fa-shopping-cart text-4xl text-red-600 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2 text-gray-900">Product Sourcing</h3>
                    <p class="text-gray-600 text-sm">We help you find and purchase products from 1688, Taobao, Alibaba</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-lg card-hover">
                    <i class="fas fa-warehouse text-4xl text-red-600 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2 text-gray-900">Consolidation</h3>
                    <p class="text-gray-600 text-sm">Multiple supplier consolidation to save shipping costs</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-lg card-hover">
                    <i class="fas fa-check-double text-4xl text-red-600 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2 text-gray-900">Quality Check</h3>
                    <p class="text-gray-600 text-sm">Pre-shipment inspection & photo verification available</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-lg card-hover">
                    <i class="fas fa-ship text-4xl text-red-600 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2 text-gray-900">Sea & Air Freight</h3>
                    <p class="text-gray-600 text-sm">Flexible shipping options based on urgency and budget</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Advanced Calculator Section -->
    <section id="calculator" class="py-16 md:py-24 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-extrabold text-gray-900 mb-4">Shipping Calculators & Converters</h2>
                <div class="section-divider w-24 mx-auto mb-6"></div>
                <p class="text-lg text-gray-600">
                    AUTOMATIC CBM TO WEIGHT(KG) CONVERTER - Two-Way Live Calculation
                </p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-8">
                <!-- Calculator 1: Dimension to Weight/CBM -->
                <div class="bg-gradient-to-br from-gray-900 to-gray-800 rounded-2xl shadow-2xl p-6 md:p-8 text-white">
                    <div class="converter-badge text-white px-4 py-2 rounded-lg inline-flex items-center gap-2 mb-6">
                        <i class="fas fa-cube"></i>
                        <span class="font-bold">Dimensions → Weight & CBM</span>
                    </div>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold mb-2">Length (CM)</label>
                            <input type="number" id="calc-length" step="0.01" placeholder="0.00" 
                                   class="w-full px-4 py-3 bg-gray-800 border-2 border-gray-700 rounded-lg input-focus text-white">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-semibold mb-2">Width (CM)</label>
                            <input type="number" id="calc-width" step="0.01" placeholder="0.00" 
                                   class="w-full px-4 py-3 bg-gray-800 border-2 border-gray-700 rounded-lg input-focus text-white">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-semibold mb-2">Height (CM)</label>
                            <input type="number" id="calc-height" step="0.01" placeholder="0.00" 
                                   class="w-full px-4 py-3 bg-gray-800 border-2 border-gray-700 rounded-lg input-focus text-white">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-semibold mb-2">Actual Weight (KG)</label>
                            <input type="number" id="calc-weight" step="0.01" placeholder="0.00" 
                                   class="w-full px-4 py-3 bg-gray-800 border-2 border-gray-700 rounded-lg input-focus text-white">
                        </div>
                        
                        <div class="bg-gray-800 p-4 rounded-xl border-2 border-red-600 mt-4">
                            <label class="block text-xs font-semibold mb-1 text-red-400">CBM (Cubic Meter) - Sea Freight</label>
                            <div class="text-2xl font-bold" id="result-cbm">0.00000 m³</div>
                            <p class="text-xs text-gray-400">(L × W × H) / 1,000,000</p>
                        </div>
                        
                        <div class="bg-gray-800 p-4 rounded-xl border-2 border-red-600">
                            <label class="block text-xs font-semibold mb-1 text-red-400">Volumetric Weight - Air Freight</label>
                            <div class="text-2xl font-bold" id="result-volumetric-air">0.00 KG</div>
                            <p class="text-xs text-gray-400">(L × W × H) / 6,000</p>
                        </div>
                        
                        <div class="bg-red-900 p-4 rounded-xl border-2 border-red-500">
                            <label class="block text-xs font-semibold mb-1 text-red-300">Chargeable Weight</label>
                            <div class="text-2xl font-bold text-red-400" id="result-chargeable">0.00 KG</div>
                            <p class="text-xs text-gray-300">Higher of Actual vs Volumetric</p>
                        </div>
                    </div>
                </div>

                <!-- Calculator 2: CBM/Weight Reverse Converter -->
                <div class="bg-gradient-to-br from-red-900 to-red-800 rounded-2xl shadow-2xl p-6 md:p-8 text-white">
                    <div class="bg-gray-900 text-white px-4 py-2 rounded-lg inline-flex items-center gap-2 mb-6">
                        <i class="fas fa-exchange-alt"></i>
                        <span class="font-bold">CBM ↔ Weight Two-Way Converter</span>
                    </div>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold mb-2">Enter CBM (m³)</label>
                            <input type="number" id="reverse-cbm" step="0.00001" placeholder="0.00000" 
                                   class="w-full px-4 py-3 bg-red-950 border-2 border-red-700 rounded-lg input-focus text-white">
                        </div>
                        
                        <div class="bg-red-950 p-4 rounded-xl border-2 border-gray-900">
                            <label class="block text-xs font-semibold mb-1 text-red-300">Equivalent Weight - Sea (Anti-density)</label>
                            <div class="text-2xl font-bold" id="reverse-sea-weight">0.00 KG</div>
                            <p class="text-xs text-gray-300">CBM × 1,000,000 / 6,000</p>
                        </div>
                        
                        <div class="bg-red-950 p-4 rounded-xl border-2 border-gray-900">
                            <label class="block text-xs font-semibold mb-1 text-red-300">Volumetric Weight - Air</label>
                            <div class="text-2xl font-bold" id="reverse-air-weight">0.00 KG</div>
                            <p class="text-xs text-gray-300">1 CBM = 167 KG (Air Standard)</p>
                        </div>

                        <div class="border-t-2 border-red-700 my-4 pt-4"></div>

                        <div>
                            <label class="block text-sm font-semibold mb-2">Enter Weight (KG)</label>
                            <input type="number" id="reverse-weight" step="0.01" placeholder="0.00" 
                                   class="w-full px-4 py-3 bg-red-950 border-2 border-red-700 rounded-lg input-focus text-white">
                        </div>
                        
                        <div class="bg-red-950 p-4 rounded-xl border-2 border-gray-900">
                            <label class="block text-xs font-semibold mb-1 text-red-300">Equivalent CBM from Weight</label>
                            <div class="text-2xl font-bold" id="reverse-weight-cbm">0.00000 m³</div>
                            <p class="text-xs text-gray-300">Weight × 6,000 / 1,000,000</p>
                        </div>

                        <button onclick="resetAllCalculators()" class="w-full bg-gray-900 hover:bg-gray-800 text-white py-3 rounded-lg font-bold transition mt-4">
                            <i class="fas fa-redo"></i> Reset All Calculators
                        </button>
                    </div>
                </div>
            </div>

            <div class="mt-8 bg-gradient-to-r from-gray-900 to-red-900 text-white p-6 rounded-xl">
                <h3 class="font-bold text-lg mb-3 flex items-center gap-2">
                    <i class="fas fa-info-circle"></i> Formula Reference
                </h3>
                <div class="grid md:grid-cols-3 gap-4 text-sm">
                    <div>
                        <strong class="text-red-400">CBM Formula:</strong>
                        <p class="text-gray-200">(Length × Width × Height) / 1,000,000</p>
                    </div>
                    <div>
                        <strong class="text-red-400">Air Freight Volumetric:</strong>
                        <p class="text-gray-200">(L × W × H) / 6,000 or CBM × 167</p>
                    </div>
                    <div>
                        <strong class="text-red-400">Sea Freight:</strong>
                        <p class="text-gray-200">Based on CBM, 1 CBM = 1,000 KG standard</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Enhanced Request Form Section -->
    <section id="request" class="py-16 md:py-24 bg-gray-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-extrabold text-gray-900 mb-4">Client Product Items Request Form</h2>
                <div class="section-divider w-24 mx-auto mb-6"></div>
                <p class="text-lg text-gray-600">
                    Complete form with automatic WhatsApp integration
                </p>
            </div>
            
            <form id="productForm" class="bg-white rounded-2xl shadow-2xl p-6 md:p-10">
                <!-- Customer Information -->
                <div class="mb-8">
                    <h3 class="text-xl font-bold text-gray-900 mb-4 pb-2 border-b-2 border-red-600">
                        <i class="fas fa-user text-red-600"></i> Customer Information
                    </h3>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Customer Name *</label>
                            <input type="text" name="customerName" required 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">WhatsApp Number *</label>
                            <input type="tel" name="whatsapp" required placeholder="+60123456789" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">E-mail *</label>
                            <input type="email" name="email" required 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Address *</label>
                            <input type="text" name="address" required 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                    </div>
                </div>

                <!-- Product Information -->
                <div class="mb-8">
                    <h3 class="text-xl font-bold text-gray-900 mb-4 pb-2 border-b-2 border-red-600">
                        <i class="fas fa-box text-red-600"></i> Product Information
                    </h3>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="md:col-span-2">
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Product Name *</label>
                            <input type="text" name="productName" required 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        
                        <!-- NEW FIELDS ADDED -->
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">BRAND</label>
                            <input type="text" name="brand" placeholder="e.g., Apple, Samsung" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">MODEL</label>
                            <input type="text" name="model" placeholder="e.g., iPhone 15 Pro" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">CODE MODEL</label>
                            <input type="text" name="codeModel" placeholder="e.g., A3102, SM-S918" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">QUANTITY CARTONS</label>
                            <input type="number" name="quantityCartons" min="0" placeholder="0" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">QUANTITY BOX</label>
                            <input type="number" name="quantityBox" min="0" placeholder="0" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">VOLUMETRIC WEIGHT KG</label>
                            <input type="number" step="0.01" name="volumetricWeight" placeholder="Auto-calculated" 
                                   class="w-full px-4 py-3 border-2 border-red-300 bg-red-50 rounded-lg text-red-600 font-semibold">
                        </div>
                        
                        <div class="md:col-span-2">
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Product Linked</label>
                            <div class="flex gap-2">
                                <input type="url" id="form-product-link" name="productLink" placeholder="https://1688.com/... or https://taobao.com/..." 
                                       class="flex-1 px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                                <button type="button" onclick="openFormLink()" class="px-6 bg-gray-900 text-white rounded-lg hover:bg-gray-800 transition">
                                    <i class="fas fa-external-link-alt"></i>
                                </button>
                            </div>
                            <p class="text-xs text-gray-500 mt-1">
                                <i class="fas fa-bolt text-red-600"></i> Link auto-opens on paste
                            </p>
                        </div>
                        
                        <div class="md:col-span-2">
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Product Images Photo Upload</label>
                            <input type="file" id="productImages" name="productImages" multiple accept="image/*" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                            <div id="imagePreview" class="upload-preview"></div>
                        </div>
                        
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Quantity Pieces *</label>
                            <input type="number" name="quantity" required min="1" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Variant</label>
                            <input type="text" name="variant" placeholder="e.g., Model A, Style B" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Color</label>
                            <input type="text" name="color" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Size</label>
                            <input type="text" name="size" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus">
                        </div>
                    </div>
                </div>

                <!-- Shipping Dimensions -->
                <div class="mb-8">
                    <h3 class="text-xl font-bold text-gray-900 mb-4 pb-2 border-b-2 border-red-600">
                        <i class="fas fa-ruler-combined text-red-600"></i> Shipping Dimensions & Automatic Converters
                    </h3>
                    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Weight (KG)</label>
                            <input type="number" step="0.01" id="form-weight" name="weight" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus form-dimension">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Length (CM)</label>
                            <input type="number" step="0.01" id="form-length" name="length" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus form-dimension">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Width (CM)</label>
                            <input type="number" step="0.01" id="form-width" name="width" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus form-dimension">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">Height (CM)</label>
                            <input type="number" step="0.01" id="form-height" name="height" 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-lg input-focus form-dimension">
                        </div>
                        <div class="lg:col-span-2">
                            <label class="block text-sm font-semibold text-gray-700 mb-2">
                                CBM & WEIGHT CONVERTER (Auto-Calculated)
                            </label>
                            <input type="text" id="form-cbm" name="cbm" readonly 
                                   class="w-full px-4 py-3 border-2 border-red-600 bg-red-50 rounded-lg font-bold text-red-600 text-sm">
                        </div>
                    </div>
                </div>

                <!-- Submit Buttons -->
                <div class="flex flex-col sm:flex-row gap-4">
                    <button type="button" onclick="sendToWhatsApp()" 
                            class="flex-1 btn-primary text-white py-4 rounded-lg font-bold text-lg inline-flex items-center justify-center gap-2">
                        <i class="fab fa-whatsapp"></i> AUTOMATIC WHATSAPP BUTTON - Send All Data
                    </button>
                    <button type="reset" class="sm:w-auto px-8 bg-gray-900 text-white py-4 rounded-lg font-bold hover:bg-gray-800 transition">
                        <i class="fas fa-redo"></i> Reset Form
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-gradient-to-br from-gray-900 to-gray-800 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-extrabold mb-4">Contact Us</h2>
                <div class="section-divider w-24 mx-auto mb-6 !bg-gradient-to-r !from-transparent !via-red-500 !to-transparent"></div>
                <p class="text-lg text-gray-300">
                    YOUR LOGISTICS PARTNERS CARGO FORWARDER
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="w-16 h-16 bg-red-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fab fa-whatsapp text-3xl"></i>
                    </div>
                    <h3 class="font-bold mb-2">WhatsApp</h3>
                    <p class="text-gray-300 text-sm">+60 11-5145 3147</p>
                    <a href="https://wa.me/60123456789" target="_blank" class="text-red-400 hover:text-red-300 text-sm">Chat Now</a>
                </div>
                
                <div class="text-center">
                    <div class="w-16 h-16 bg-red-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-envelope text-3xl"></i>
                    </div>
                    <h3 class="font-bold mb-2">Email</h3>
                    <p class="text-gray-300 text-sm">ssdynamiccargo@gmail.com & senseiborongchinassdynamic@gmail.com</p>
                    <a href="mailto:ssdynamiccargo@gmail.com & senseiborongchinassdynamic@gmail.com" class="text-red-400 hover:text-red-300 text-sm">Send Email</a>
                </div>
                
                <div class="text-center">
                    <div class="w-16 h-16 bg-red-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-map-marker-alt text-3xl"></i>
                    </div>
                    <h3 class="font-bold mb-2">Warehouse</h3>
                    <p class="text-gray-300 text-sm">Guangzhou, China 🇨🇳</p>
                    <p class="text-gray-300 text-sm">Kuala Lumpur, Malaysia 🇲🇾</p>
                </div>
                
                <div class="text-center">
                    <div class="w-16 h-16 bg-red-600 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-clock text-3xl"></i>
                    </div>
                    <h3 class="font-bold mb-2">Working Hours</h3>
                    <p class="text-gray-300 text-sm">Mon - Sat: 9AM - 6PM</p>
                    <p class="text-gray-300 text-sm">Sunday: Closed</p>
                </div>
            </div>
            
            <div class="mt-12 pt-12 border-t border-gray-700 text-center">
                <div class="flex justify-center space-x-6 mb-6">
                    <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-red-600 rounded-full flex items-center justify-center transition">
                        <i class="fab fa-facebook-f"></i>
                    </a>
                    <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-red-600 rounded-full flex items-center justify-center transition">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-red-600 rounded-full flex items-center justify-center transition">
                        <i class="fab fa-tiktok"></i>
                    </a>
                    <a href="#" class="w-12 h-12 bg-gray-800 hover:bg-red-600 rounded-full flex items-center justify-center transition">
                        <i class="fab fa-weixin"></i>
                    </a>
                </div>
                <p class="text-gray-400 text-sm mb-2">
                    © SINCE:2015 SS DYNAMIC SENSEI BORONG CHINA & SS DYNAMIC CARGO. All rights reserved.
                </p>
                <p class="text-red-400 text-sm font-semibold">
                    WE HELP MANAGE THE PURCHASE AND DELIVERY OF YOUR PRODUCTS ITEMS FROM 🇨🇳CHINA🇨🇳 TO 🇲🇾MALAYSIA🇲🇾
                </p>
            </div>
        </div>
    </section>

    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('active');
            const icon = mobileMenuBtn.querySelector('i');
            icon.classList.toggle('fa-bars');
            icon.classList.toggle('fa-times');
        });

        // Close mobile menu when clicking links
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('active');
                mobileMenuBtn.querySelector('i').classList.remove('fa-times');
                mobileMenuBtn.querySelector('i').classList.add('fa-bars');
            });
        });

        // Navbar scroll effect
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('sticky-nav');
            } else {
                navbar.classList.remove('sticky-nav');
            }
        });

        // AUTOMATIC PRODUCT SEARCH ENGINE - Auto open on paste
        let pasteTimeout;
        document.getElementById('productLink').addEventListener('paste', function(e) {
            clearTimeout(pasteTimeout);
            pasteTimeout = setTimeout(() => {
                const link = e.target.value;
                if (link) {
                    if (!link.startsWith('http://') && !link.startsWith('https://')) {
                        window.open('https://' + link, '_blank');
                    } else {
                        window.open(link, '_blank');
                    }
                }
            }, 1500);
        });

        document.getElementById('form-product-link').addEventListener('paste', function(e) {
            clearTimeout(pasteTimeout);
            pasteTimeout = setTimeout(() => {
                const link = e.target.value;
                if (link) {
                    if (!link.startsWith('http://') && !link.startsWith('https://')) {
                        window.open('https://' + link, '_blank');
                    } else {
                        window.open(link, '_blank');
                    }
                }
            }, 1500);
        });

        function openProductLink() {
            const link = document.getElementById('productLink').value;
            if (link) {
                if (!link.startsWith('http://') && !link.startsWith('https://')) {
                    window.open('https://' + link, '_blank');
                } else {
                    window.open(link, '_blank');
                }
            } else {
                alert('Please paste a product link first!');
            }
        }

        function openFormLink() {
            const link = document.getElementById('form-product-link').value;
            if (link) {
                if (!link.startsWith('http://') && !link.startsWith('https://')) {
                    window.open('https://' + link, '_blank');
                } else {
                    window.open(link, '_blank');
                }
            } else {
                alert('Please enter a product link first!');
            }
        }

        // CBM Calculator Functions - Live Updates
        const calcInputs = ['calc-length', 'calc-width', 'calc-height', 'calc-weight'];
        calcInputs.forEach(id => {
            document.getElementById(id).addEventListener('input', calculateCBM);
        });

        function calculateCBM() {
            const length = parseFloat(document.getElementById('calc-length').value) || 0;
            const width = parseFloat(document.getElementById('calc-width').value) || 0;
            const height = parseFloat(document.getElementById('calc-height').value) || 0;
            const weight = parseFloat(document.getElementById('calc-weight').value) || 0;

            // CBM = (L × W × H) / 1,000,000
            const cbm = (length * width * height) / 1000000;
            document.getElementById('result-cbm').textContent = cbm.toFixed(5) + ' m³';

            // Volumetric Weight Air = (L × W × H) / 6,000
            const volumetricAir = (length * width * height) / 6000;
            document.getElementById('result-volumetric-air').textContent = volumetricAir.toFixed(2) + ' KG';

            // Chargeable Weight = Higher of Actual Weight vs Volumetric
            const chargeable = Math.max(weight, volumetricAir);
            document.getElementById('result-chargeable').textContent = chargeable.toFixed(2) + ' KG';
        }

        // Reverse Converter - CBM to Weight & Weight to CBM
        document.getElementById('reverse-cbm').addEventListener('input', reverseCBMToWeight);
        document.getElementById('reverse-weight').addEventListener('input', reverseWeightToCBM);

        function reverseCBMToWeight() {
            const cbm = parseFloat(document.getElementById('reverse-cbm').value) || 0;
            
            // Sea: 1 CBM = 1000 KG (standard density)
            const seaWeight = cbm * 1000;
            document.getElementById('reverse-sea-weight').textContent = seaWeight.toFixed(2) + ' KG';
            
            // Air: 1 CBM = 167 KG (6000 divisor standard)
            const airWeight = cbm * 167;
            document.getElementById('reverse-air-weight').textContent = airWeight.toFixed(2) + ' KG';
        }

        function reverseWeightToCBM() {
            const weight = parseFloat(document.getElementById('reverse-weight').value) || 0;
            
            // CBM from weight using air freight standard: Weight / 167
            const cbm = weight / 167;
            document.getElementById('reverse-weight-cbm').textContent = cbm.toFixed(5) + ' m³';
        }

        function resetAllCalculators() {
            calcInputs.forEach(id => {
                document.getElementById(id).value = '';
            });
            document.getElementById('reverse-cbm').value = '';
            document.getElementById('reverse-weight').value = '';
            document.getElementById('result-cbm').textContent = '0.00000 m³';
            document.getElementById('result-volumetric-air').textContent = '0.00 KG';
            document.getElementById('result-chargeable').textContent = '0.00 KG';
            document.getElementById('reverse-sea-weight').textContent = '0.00 KG';
            document.getElementById('reverse-air-weight').textContent = '0.00 KG';
            document.getElementById('reverse-weight-cbm').textContent = '0.00000 m³';
        }

        // Auto CBM Calculator in Form - Live Updates
        const formDimensions = document.querySelectorAll('.form-dimension');
        formDimensions.forEach(input => {
            input.addEventListener('input', calculateFormCBM);
        });

        function calculateFormCBM() {
            const length = parseFloat(document.getElementById('form-length').value) || 0;
            const width = parseFloat(document.getElementById('form-width').value) || 0;
            const height = parseFloat(document.getElementById('form-height').value) || 0;
            const weight = parseFloat(document.getElementById('form-weight').value) || 0;

            const cbm = (length * width * height) / 1000000;
            const volumetric = (length * width * height) / 6000;
            const chargeable = Math.max(weight, volumetric);

            // Update VOLUMETRIC WEIGHT KG field
            document.querySelector('input[name="volumetricWeight"]').value = volumetric.toFixed(2);

            if (cbm > 0 || volumetric > 0 || weight > 0) {
                document.getElementById('form-cbm').value = `CBM: ${cbm.toFixed(5)} m³ | Air Vol: ${volumetric.toFixed(2)} KG | Chargeable: ${chargeable.toFixed(2)} KG`;
            } else {
                document.getElementById('form-cbm').value = '';
            }
        }

        // Image Preview
        document.getElementById('productImages').addEventListener('change', function(e) {
            const preview = document.getElementById('imagePreview');
            preview.innerHTML = '';
            const files = e.target.files;
            
            for (let i = 0; i < files.length && i < 6; i++) {
                const file = files[i];
                if (file.type.startsWith('image/')) {
                    const reader = new FileReader();
                    reader.onload = function(e) {
                        const img = document.createElement('img');
                        img.src = e.target.result;
                        preview.appendChild(img);
                    }
                    reader.readAsDataURL(file);
                }
            }
        });

        // AUTOMATIC WHATSAPP BUTTON - Send all form data
        function sendToWhatsApp() {
            const form = document.getElementById('productForm');
            const formData = new FormData(form);
            
            // Validate required fields
            const required = ['customerName', 'whatsapp', 'email', 'address', 'productName', 'quantity'];
            for (let field of required) {
                if (!formData.get(field)) {
                    alert('Please fill in all required fields marked with *');
                    return;
                }
            }

            // Build WhatsApp message with ALL data
            let message = '*NEW PRODUCT REQUEST - SS DYNAMIC SENSEI* 🇨🇳🇲🇾\n';
            message += '*BORONG CHINA & CARGO FORWARDER*\n';
            message += '━━━━━━━━━━━━━━━━━━━━━━━\n\n';
            
            message += '*📋 CUSTOMER INFORMATION:*\n';
            message += `Name: ${formData.get('customerName')}\n`;
            message += `WhatsApp: ${formData.get('whatsapp')}\n`;
            message += `Email: ${formData.get('email')}\n`;
            message += `Address: ${formData.get('address')}\n\n`;
            
            message += '*📦 PRODUCT INFORMATION:*\n';
            message += `Product: ${formData.get('productName')}\n`;
            if (formData.get('brand')) message += `BRAND: ${formData.get('brand')}\n`;
            if (formData.get('model')) message += `MODEL: ${formData.get('model')}\n`;
            if (formData.get('codeModel')) message += `CODE MODEL: ${formData.get('codeModel')}\n`;
            if (formData.get('productLink')) message += `Product Linked: ${formData.get('productLink')}\n`;
            message += `Quantity Pieces: ${formData.get('quantity')} pcs\n`;
            if (formData.get('quantityCartons')) message += `QUANTITY CARTONS: ${formData.get('quantityCartons')}\n`;
            if (formData.get('quantityBox')) message += `QUANTITY BOX: ${formData.get('quantityBox')}\n`;
            if (formData.get('variant')) message += `Variant: ${formData.get('variant')}\n`;
            if (formData.get('color')) message += `Color: ${formData.get('color')}\n`;
            if (formData.get('size')) message += `Size: ${formData.get('size')}\n\n`;
            
            message += '*📐 SHIPPING DIMENSIONS:*\n';
            if (formData.get('weight')) message += `Actual Weight: ${formData.get('weight')} KG\n`;
            if (formData.get('volumetricWeight')) message += `VOLUMETRIC WEIGHT: ${formData.get('volumetricWeight')} KG\n`;
            if (formData.get('length')) message += `Length: ${formData.get('length')} CM\n`;
            if (formData.get('width')) message += `Width: ${formData.get('width')} CM\n`;
            if (formData.get('height')) message += `Height: ${formData.get('height')} CM\n`;
            if (formData.get('cbm')) message += `CBM & Details: ${formData.get('cbm')}\n`;
            
            message += '\n━━━━━━━━━━━━━━━━━━━━━━━\n';
            message += '_Please provide quotation and shipping cost from China to Malaysia 🇨🇳→🇲🇾_';

            // Replace with your WhatsApp number
            const whatsappNumber = '60123456789';
            const whatsappUrl = `https://wa.me/${whatsappNumber}?text=${encodeURIComponent(message)}`;
            window.open(whatsappUrl, '_blank');
        }

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    const offset = 80;
                    const targetPosition = target.offsetTop - offset;
                    window.scrollTo({
                        top: targetPosition,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
<script>(function(){document.addEventListener("click",function(e){var a=e.target.closest("[data-product-id]");if(!a)return;e.preventDefault();var pid=a.getAttribute("data-product-id");if(pid)parent.postMessage({type:"ecto-artifact-link-click",productId:pid},"*")})})();</script>
</body>
