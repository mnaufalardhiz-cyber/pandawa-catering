<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pandawa Catering - Jasa Catering Pernikahan Mewah</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        
        .heading-font {
            font-family: 'Playfair Display', serif;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, rgba(139, 69, 19, 0.85) 0%, rgba(160, 82, 45, 0.8) 50%, rgba(205, 133, 63, 0.85) 100%);
        }
        
        .gold-gradient {
            background: linear-gradient(135deg, #D4AF37 0%, #FFD700 100%);
        }
        
        .hover-gold:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(212, 175, 55, 0.3);
        }
        
        .food-card {
            transition: all 0.3s ease;
            border-bottom: 3px solid transparent;
        }
        
        .food-card:hover {
            transform: translateY(-5px);
            border-bottom: 3px solid #D4AF37;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
        }
        
        .gallery-item {
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }
        
        .gallery-item img {
            transition: transform 0.5s ease;
        }
        
        .gallery-item:hover img {
            transform: scale(1.05);
        }
        
        .testimonial-card {
            background: linear-gradient(145deg, #ffffff 0%, #f8f9fa 100%);
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            border-left: 4px solid #D4AF37;
        }
        
        .nav-scroll {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 2px 20px rgba(0,0,0,0.1);
        }
        
        .whatsapp-btn:hover {
            background: #25D366 !important;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="fixed w-full z-50 transition-all duration-300" id="navbar">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <h1 class="heading-font text-2xl font-bold text-amber-800">Pandawa Catering</h1>
                </div>
                
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-700 hover:text-amber-600 transition-colors">Beranda</a>
                    <a href="#about" class="text-gray-700 hover:text-amber-600 transition-colors">Tentang</a>
                    <a href="#gallery" class="text-gray-700 hover:text-amber-600 transition-colors">Gallery</a>
                    <a href="#menu" class="text-gray-700 hover:text-amber-600 transition-colors">Menu</a>
                    <a href="#testimoni" class="text-gray-700 hover:text-amber-600 transition-colors">Testimoni</a>
                    <a href="#contact" class="text-gray-700 hover:text-amber-600 transition-colors">Kontak</a>
                </div>
                
                <div class="md:hidden">
                    <button id="menu-toggle" class="text-gray-700">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden bg-white shadow-lg">
            <div class="flex flex-col space-y-4 p-6">
                <a href="#home" class="text-gray-700 hover:text-amber-600 py-2">Beranda</a>
                <a href="#about" class="text-gray-700 hover:text-amber-600 py-2">Tentang</a>
                <a href="#gallery" class="text-gray-700 hover:text-amber-600 py-2">Gallery</a>
                <a href="#menu" class="text-gray-700 hover:text-amber-600 py-2">Menu</a>
                <a href="#testimoni" class="text-gray-700 hover:text-amber-600 py-2">Testimoni</a>
                <a href="#contact" class="text-gray-700 hover:text-amber-600 py-2">Kontak</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative min-h-screen flex items-center justify-center pt-16">
        <div class="absolute inset-0">
            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/10165ff3-9ec7-4a60-aaf1-c986c509bb73.png" alt="Elegant wedding reception setup with gold decor, crystal chandeliers, and floral arrangements in a luxurious ballroom" class="w-full h-full object-cover">
            <div class="absolute inset-0 hero-gradient"></div>
        </div>
        
        <div class="relative z-10 text-center text-white max-w-4xl mx-auto px-6">
            <h2 class="heading-font text-5xl md:text-7xl font-bold mb-6">Pandawa Catering</h2>
            <p class="text-xl md:text-2xl mb-8 opacity-90">Mewujudkan Momen Pernikahan Impian Anda dengan Rasa dan Pelayanan Terbaik</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#contact" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-4 rounded-full font-semibold hover-gold transition-all duration-300">
                    Konsultasi Gratis
                </a>
                <a href="#gallery" class="border-2 border-white text-white px-8 py-4 rounded-full font-semibold hover:bg-white hover:text-amber-800 transition-all duration-300">
                    Lihat Gallery
                </a>
            </div>
        </div>

        <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2">
            <a href="#about" class="text-white animate-bounce">
                <i class="fas fa-chevron-down text-3xl"></i>
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl md:text-5xl font-bold text-amber-800 mb-4">Tentang Pandawa Catering</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Sejak 2015, kami telah membantu ribuan pasangan merayakan hari spesial mereka dengan layanan catering pernikahan terbaik.</p>
            </div>

            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/68cffe23-c4b1-4453-9fd4-e73e39716b8c.png" alt="Professional catering team preparing elegant wedding dishes in a modern kitchen setting" class="rounded-2xl shadow-xl">
                </div>
                
                <div>
                    <h3 class="heading-font text-3xl font-bold text-gray-800 mb-6">Keunggulan Layanan Kami</h3>
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="gold-gradient p-3 rounded-full mr-4">
                                <i class="fas fa-utensils text-white text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-lg mb-2">Menu Berkualitas Tinggi</h4>
                                <p class="text-gray-600">Hidangan lezat dengan bahan-bahan segar pilihan yang diolah oleh chef profesional.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="gold-gradient p-3 rounded-full mr-4">
                                <i class="fas fa-users text-white text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-lg mb-2">Pelayanan Ramah</h4>
                                <p class="text-gray-600">Staff berpengalaman dan profesional siap melayani dengan penuh keramahan.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="gold-gradient p-3 rounded-full mr-4">
                                <i class="fas fa-palette text-white text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-lg mb-2">Dekorasi Elegan</h4>
                                <p class="text-gray-600">Tata rias meja dan dekorasi yang memukau untuk menciptakan atmosfer pernikahan sempurna.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl md:text-5xl font-bold text-amber-800 mb-4">Gallery Pernikahan</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Bukti kesempurnaan layanan kami dalam berbagai acara pernikahan mewah.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Wedding 1 -->
                <div class="gallery-item">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/cae9d73a-a4a5-4733-9fdf-253e87662aa9.png" alt="Luxurious outdoor wedding reception with golden decorations, floral arches, and elegant table settings under fairy lights" class="w-full h-64 object-cover">
                    <div class="p-6 bg-white">
                        <h4 class="font-semibold text-lg mb-2">Pernikahan Sarah & Michael</h4>
                        <p class="text-gray-600">Garden Wedding dengan tema golden elegance</p>
                    </div>
                </div>

                <!-- Wedding 2 -->
                <div class="gallery-item">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/e4789036-a0c1-4342-95de-42c5c3879c7c.png" alt="Indoor ballroom wedding with crystal chandeliers, gold trimmed chairs, and magnificent floral centerpieces" class="w-full h-64 object-cover">
                    <div class="p-6 bg-white">
                        <h4 class="font-semibold text-lg mb-2">Pernikahan Amanda & David</h4>
                        <p class="text-gray-600">Ballroom wedding dengan dekorasi kristal</p>
                    </div>
                </div>

                <!-- Wedding 3 -->
                <div class="gallery-item">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/53ef7ec0-66d8-4582-bfa0-760b52c2f968.png" alt="Beachfront wedding setup with white drapes, wooden decor, and tropical floral arrangements during sunset" class="w-full h-64 object-cover">
                    <div class="p-6 bg-white">
                        <h4 class="font-semibold text-lg mb-2">Pernikahan Lisa & Robert</h4>
                        <p class="text-gray-600">Beach wedding dengan sentuhan tropis</p>
                    </div>
                </div>

                <!-- Wedding 4 -->
                <div class="gallery-item">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/ba32a453-4e25-4ea0-88de-03ead0cc47cd.png" alt="Close-up of elegant wedding buffet table with gold serving dishes, crystal glasses, and gourmet food presentation" class="w-full h-64 object-cover">
                    <div class="p-6 bg-white">
                        <h4 class="font-semibold text-lg mb-2">Tata Saji Mewah</h4>
                        <p class="text-gray-600">Buffet style dengan presentation premium</p>
                    </div>
                </div>

                <!-- Wedding 5 -->
                <div class="gallery-item">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/21837fd9-3e1e-4bf4-afa6-8eff01df0dfe.png" alt="Wedding cake table with multi-tier gold decorated cake, macarons, and dessert display surrounded by flowers" class="w-full h-64 object-cover">
                    <div class="p-6 bg-white">
                        <h4 class="font-semibold text-lg mb-2">Dessert Table Elegan</h4>
                        <p class="text-gray-600">Special dessert corner dengan cake custom</p>
                    </div>
                </div>

                <!-- Wedding 6 -->
                <div class="gallery-item">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/4843ff60-7608-4f4e-a9d2-23e71cabbf92.png" alt="Bridal party table with gold cutlery, fine china, floral centerpiece, and elegant name cards in a romantic setting" class="w-full h-64 object-cover">
                    <div class="p-6 bg-white">
                        <h4 class="font-semibold text-lg mb-2">Table Setting Premium</h4>
                        <p class="text-gray-600">Setting meja dengan peralatan makan premium</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl md:text-5xl font-bold text-amber-800 mb-4">Paket Catering Pernikahan</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Berbagai pilihan paket catering yang dapat disesuaikan dengan kebutuhan dan budget Anda.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Package 1 -->
                <div class="food-card bg-white rounded-2xl shadow-lg overflow-hidden border border-gray-100">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/9eba6ac0-af8d-4faf-85e6-e5a8dfff0ea5.png" alt="Silver package wedding buffet with elegant serving dishes and basic floral decorations" class="w-full h-48 object-cover">
                        <div class="absolute top-4 left-4 bg-amber-600 text-white px-4 py-2 rounded-full">
                            <span class="font-semibold">Silver</span>
                        </div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">Paket Silver</h3>
                        <ul class="space-y-3 text-gray-600 mb-6">
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                4 Menu Utama + 2 Menu Pendamping
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Free Soft Drink & Air Mineral
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Basic Decorations
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Service Staff 5 Orang
                            </li>
                        </ul>
                        <div class="text-center">
                            <p class="text-2xl font-bold text-amber-700 mb-4">Mulai dari Rp 1.500.000</p>
                            <button class="w-full bg-amber-600 hover:bg-amber-700 text-white py-3 rounded-lg font-semibold transition-colors">
                                Pesan Sekarang
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Package 2 -->
                <div class="food-card bg-white rounded-2xl shadow-lg overflow-hidden border border-gray-100 transform scale-105">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/60c52cd4-9cac-4883-b938-3c890ac4fb2c.png" alt="Gold package wedding reception with luxurious buffet setup, floral arrangements, and premium servingware" class="w-full h-48 object-cover">
                        <div class="absolute top-4 left-4 gold-gradient text-white px-4 py-2 rounded-full">
                            <span class="font-semibold">Gold</span>
                        </div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">Paket Gold</h3>
                        <ul class="space-y-3 text-gray-600 mb-6">
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                6 Menu Utama + 4 Menu Pendamping
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Free Juice & Welcome Drink
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Premium Decorations
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Service Staff 8 Orang + Coordinator
                            </li>
                        </ul>
                        <div class="text-center">
                            <p class="text-2xl font-bold text-amber-700 mb-4">Mulai dari Rp 2.500.000</p>
                            <button class="w-full gold-gradient text-white py-3 rounded-lg font-semibold hover-gold transition-all">
                                Pesan Sekarang
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Package 3 -->
                <div class="food-card bg-white rounded-2xl shadow-lg overflow-hidden border border-gray-100">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f75416ab-c576-4740-9ddc-fbddf31e8212.png" alt="Platinum package exclusive wedding dining with luxury table settings, crystal glassware, and gourmet food presentation" class="w-full h-48 object-cover">
                        <div class="absolute top-4 left-4 bg-gray-800 text-white px-4 py-2 rounded-full">
                            <span class="font-semibold">Platinum</span>
                        </div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">Paket Platinum</h3>
                        <ul class="space-y-3 text-gray-600 mb-6">
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                8 Menu Utama + 6 Menu Pendamping
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Free Coffee Stand & Dessert Station
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Luxury Decorations & Floral Arrangements
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-amber-600 mr-2"></i>
                                Full Service Team + Event Coordinator
                            </li>
                        </ul>
                        <div class="text-center">
                            <p class="text-2xl font-bold text-amber-700 mb-4">Mulai dari Rp 4.000.000</p>
                            <button class="w-full bg-gray-800 hover:bg-gray-900 text-white py-3 rounded-lg font-semibold transition-colors">
                                Pesan Sekarang
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonial Section -->
    <section id="testimoni" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl md:text-5xl font-bold text-amber-800 mb-4">Testimoni Pelanggan</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Apa kata mereka yang telah mempercayakan acara pernikahan kepada kami.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="testimonial-card p-8 rounded-2xl">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center">
                            <i class="fas fa-user text-amber-600 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-semibold">Sarah Wijaya</h4>
                            <p class="text-amber-600">Pernikahan Garden, 2023</p>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Pelayanan dan makanan dari Pandawa Catering sangat luar biasa! Tamu-tamu kami terus memuji rasa makanannya yang enak dan presentationnya yang elegan."</p>
                    <div class="flex text-amber-400 mt-4">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="testimonial-card p-8 rounded-2xl">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center">
                            <i class="fas fa-user text-amber-600 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-semibold">Michael Santoso</h4>
                            <p class="text-amber-600">Pernikahan Ballroom, 2023</p>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Staffnya sangat profesional dan responsif. Mereka membantu kami dari planning sampai execution dengan sempurna. Highly recommended!"</p>
                    <div class="flex text-amber-400 mt-4">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>

                <!-- Testimonial 3 -->
                <div class="testimonial-card p-8 rounded-2xl">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center">
                            <i class="fas fa-user text-amber-600 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-semibold">Amanda Putri</h4>
                            <p class="text-amber-600">Pernikahan Beach, 2022</p>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Dekorasinya exactly seperti yang kita inginkan! Makanannya masih fresh sampai akhir acara. Thank you Pandawa Catering untuk hari yang sempurna!"</p>
                    <div class="flex text-amber-400 mt-4">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl md:text-5xl font-bold text-amber-800 mb-4">Hubungi Kami</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Konsultasikan kebutuhan catering pernikahan Anda dengan tim profesional kami.</p>
            </div>

            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <div class="bg-gray-50 p-8 rounded-2xl shadow-lg">
                        <h3 class="text-2xl font-bold text-gray-800 mb-6">Informasi Kontak</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-center">
                                <div class="gold-gradient p-3 rounded-full mr-4">
                                    <i class="fas fa-phone text-white"></i>
                                </div>
                                <div>
                                    <p class="font-semibold">Telepon/WhatsApp</p>
                                    <a href="https://wa.me/6289654736212" class="text-amber-600 hover:text-amber-700">0896-5473-6212</a>
                                </div>
                            </div>
                            
                            <div class="flex items-center">
                                <div class="gold-gradient p-3 rounded-full mr-4">
                                    <i class="fas fa-envelope text-white"></i>
                                </div>
                                <div>
                                    <p class="font-semibold">Email</p>
                                    <a href="mailto:pandawacatering@gmail.com" class="text-amber-600 hover:text-amber-700">pandawacatering@gmail.com</a>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="gold-gradient p-3 rounded-full mr-4">
                                    <i class="fas fa-map-marker-alt text-white"></i>
                                </div>
                                <div>
                                    <p class="font-semibold">Alamat</p>
                                    <p class="text-gray-600">Jalan Swadaya 1 No16b, Kota Bekasi<br>Jatimakmur, Pondok Gede</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center">
                                <div class="gold-gradient p-3 rounded-full mr-4">
                                    <i class="fas fa-clock text-white"></i>
                                </div>
                                <div>
                                    <p class="font-semibold">Jam Operasional</p>
                                    <p class="text-gray-600">Senin - Minggu: 08:00 - 21:00 WIB</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <a href="https://wa.me/6289654736212" class="whatsapp-btn bg-green-500 hover:bg-green-600 text-white px-6 py-3 rounded-lg font-semibold flex items-center justify-center transition-colors">
                                <i class="fab fa-whatsapp mr-2 text-xl"></i>
                                Chat via WhatsApp
                            </a>
                        </div>
                    </div>
                </div>
                
                <div>
                    <div class="bg-gray-50 p-8 rounded-2xl shadow-lg">
                        <h3 class="text-2xl font-bold text-gray-800 mb-6">Kirim Pesan</h3>
                        
                        <form class="space-y-6">
                            <div>
                                <label class="block text-gray-700 mb-2">Nama Lengkap</label>
                                <input type="text" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent" placeholder="Masukkan nama Anda">
                            </div>
                            
                            <div>
                                <label class="block text-gray-700 mb-2">Email</label>
                                <input type="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent" placeholder="Masukkan email Anda">
                            </div>
                            
                            <div>
                                <label class="block text-gray-700 mb-2">Telepon</label>
                                <input type="tel" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent" placeholder="Masukkan nomor telepon">
                            </div>
                            
                            <div>
                                <label class="block text-gray-700 mb-2">Pesan</label>
                                <textarea rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-amber-500 focus:border-transparent" placeholder="Tulis pesan Anda..."></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-amber-600 hover:bg-amber-700 text-white py-3 rounded-lg font-semibold transition-colors">
                                Kirim Pesan
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <h3 class="heading-font text-2xl font-bold text-amber-400 mb-4">Pandawa Catering</h3>
                    <p class="text-gray-400 mb-6">Mewujudkan momen pernikahan impian Anda dengan layanan catering premium.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition-colors">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition-colors">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-amber-400 transition-colors">
                            <i class="fab fa-twitter"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="font-semibold text-lg mb-4">Layanan</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Catering Pernikahan</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Dekorasi Pernikahan</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Event Planning</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Consultan Pernikahan</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-semibold text-lg mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition-colors">Beranda</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white transition-colors">Tentang Kami</a></li>
                        <li><a href="#gallery" class="text-gray-400 hover:text-white transition-colors">Gallery</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition-colors">Kontak</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-semibold text-lg mb-4">Newsletter</h4>
                    <p class="text-gray-400 mb-4">Dapatkan informasi promo dan tips pernikahan terbaru.</p>
                    <div class="flex">
                        <input type="email" placeholder="Email Anda" class="flex-1 px-4 py-2 bg-gray-800 border border-gray-700 rounded-l-lg focus:outline-none focus:ring-2 focus:ring-amber-500">
                        <button class="bg-amber-600 hover:bg-amber-700 px-4 py-2 rounded-r-lg transition-colors">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 text-center">
                <p class="text-gray-400">© 2024 Pandawa Catering. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 100) {
                navbar.classList.add('nav-scroll');
                navbar.classList.remove('bg-transparent');
            } else {
                navbar.classList.remove('nav-scroll');
                navbar.classList.add('bg-transparent');
            }
        });

        // Mobile menu toggle
        document.getElementById('menu-toggle').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking outside
        document.addEventListener('click', function(event) {
            const mobileMenu = document.getElementById('mobile-menu');
            const menuToggle = document.getElementById('menu-toggle');
            
            if (!mobileMenu.contains(event.target) && !menuToggle.contains(event.target)) {
                mobileMenu.classList.add('hidden');
            }
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    
                    // Close mobile menu if open
                    document.getElementById('mobile-menu').classList.add('hidden');
                }
            });
        });

        // Form submission
        document.querySelector('form')?.addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Terima kasih! Pesan Anda telah berhasil dikirim. Tim kami akan segera menghubungi Anda.');
            this.reset();
        });
    </script>
</body>
</html>

