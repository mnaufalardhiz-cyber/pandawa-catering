<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pandawa Catering - Jasa Catering Pernikahan Mewah</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .playfair {
            font-family: 'Playfair Display', serif;
        }
        .hero-gradient {
            background: linear-gradient(135deg, rgba(139,69,19,0.8) 0%, rgba(160,82,45,0.8) 50%, rgba(205,133,63,0.8) 100%);
        }
        .gold-gradient {
            background: linear-gradient(135deg, #D4AF37 0%, #FFD700 50%, #DAA520 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .menu-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .menu-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        .gallery-item {
            transition: transform 0.3s ease;
        }
        .gallery-item:hover {
            transform: scale(1.05);
        }
        .testimonial-card {
            background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
            border-left: 4px solid #D4AF37;
        }
    </style>
</head>
<body class="bg-white text-gray-800">
    <!-- Header -->
    <header class="fixed w-full bg-white shadow-md z-50">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <h1 class="playfair text-2xl font-bold gold-gradient">Pandawa Catering</h1>
                </div>
                <nav class="hidden md:flex space-x-8">
                    <a href="#home" class="hover:text-amber-600 transition-colors">Beranda</a>
                    <a href="#about" class="hover:text-amber-600 transition-colors">Tentang Kami</a>
                    <a href="#services" class="hover:text-amber-600 transition-colors">Layanan</a>
                    <a href="#gallery" class="hover:text-amber-600 transition-colors">Galeri</a>
                    <a href="#testimonials" class="hover:text-amber-600 transition-colors">Testimoni</a>
                    <a href="#contact" class="hover:text-amber-600 transition-colors">Kontak</a>
                </nav>
                <div class="md:hidden">
                    <button id="menu-toggle" class="text-gray-800">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg">
            <div class="px-6 py-4 space-y-4">
                <a href="#home" class="block hover:text-amber-600">Beranda</a>
                <a href="#about" class="block hover:text-amber-600">Tentang Kami</a>
                <a href="#services" class="block hover:text-amber-600">Layanan</a>
                <a href="#gallery" class="block hover:text-amber-600">Galeri</a>
                <a href="#testimonials" class="block hover:text-amber-600">Testimoni</a>
                <a href="#contact" class="block hover:text-amber-600">Kontak</a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative h-screen flex items-center justify-center">
        <div class="absolute inset-0">
            <img src="https://placehold.co/1920x1080" alt="Luxury wedding reception setup with elegant table settings, floral arrangements, and ambient lighting in a grand ballroom" class="w-full h-full object-cover" />
        </div>
        <div class="absolute inset-0 hero-gradient"></div>
        <div class="relative z-10 text-center text-white px-6">
            <h2 class="playfair text-5xl md:text-7xl font-bold mb-6">Pandawa Catering</h2>
            <p class="text-xl md:text-2xl mb-8">Mewujudkan Momen Pernikahan Impian Anda dengan Rasa dan Pelayanan Terbaik</p>
            <div class="space-x-4">
                <a href="#contact" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-3 rounded-full font-semibold transition-colors">Konsultasi Gratis</a>
                <a href="#gallery" class="border-2 border-white hover:bg-white hover:text-amber-600 text-white px-8 py-3 rounded-full font-semibold transition-colors">Lihat Portfolio</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="playfair text-4xl md:text-5xl font-bold mb-4">Tentang Pandawa Catering</h2>
                <div class="w-24 h-1 bg-amber-600 mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <img src="https://placehold.co/600x400" alt="Professional catering team in kitchen preparing gourmet wedding dishes with precision and care" class="rounded-lg shadow-xl" />
                </div>
                <div>
                    <h3 class="playfair text-3xl font-bold mb-6 gold-gradient">Pengalaman Tak Terlupakan dalam Setiap Suapan</h3>
                    <p class="text-lg mb-6">Sejak 2010, Pandawa Catering telah menjadi pilihan utama pasangan pengantin yang menginginkan pengalaman kuliner istimewa pada hari pernikahan mereka. Kami menghadirkan cita rasa autentik dengan sentuhan modern.</p>
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-medal text-amber-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">10+ Tahun Pengalaman</h4>
                                <p class="text-gray-600">Melayani ribuan pernikahan</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-users text-amber-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Tim Profesional</h4>
                                <p class="text-gray-600">Chef dan staff berpengalaman</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-star text-amber-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Bahan Berkualitas</h4>
                                <p class="text-gray-600">Menggunakan bahan pilihan terbaik</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="playfair text-4xl md:text-5xl font-bold mb-4">Layanan Kami</h2>
                <p class="text-xl text-gray-600">Paket lengkap untuk pernikahan sempurna Anda</p>
                <div class="w-24 h-1 bg-amber-600 mx-auto mt-4"></div>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Package 1 -->
                <div class="menu-card bg-white rounded-xl shadow-lg p-8 border border-gray-100">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-crown text-amber-600 text-2xl"></i>
                        </div>
                        <h3 class="playfair text-2xl font-bold mb-2">Paket Royal</h3>
                        <p class="text-amber-600 font-bold text-2xl">Rp 2.500.000/100 pax</p>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>8 Menu Utama Pilihan</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>3 Menu Dessert Premium</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Welcome Drink Spesial</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Dekorasi Meja Mewah</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Pelayanan Butler Professional</span>
                        </li>
                    </ul>
                    <button class="w-full bg-amber-600 hover:bg-amber-700 text-white py-3 rounded-lg font-semibold transition-colors">Pilih Paket</button>
                </div>

                <!-- Package 2 -->
                <div class="menu-card bg-white rounded-xl shadow-lg p-8 border-2 border-amber-600 transform scale-105">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 bg-amber-600 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-gem text-white text-2xl"></i>
                        </div>
                        <h3 class="playfair text-2xl font-bold mb-2">Paket Exclusive</h3>
                        <p class="text-amber-600 font-bold text-2xl">Rp 1.800.000/100 pax</p>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>6 Menu Utama Pilihan</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>2 Menu Dessert Premium</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Welcome Drink Eksklusif</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Dekorasi Meja Elegant</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Pelayanan Staff Berpengalaman</span>
                        </li>
                    </ul>
                    <button class="w-full bg-amber-600 hover:bg-amber-700 text-white py-3 rounded-lg font-semibold transition-colors">Pilih Paket</button>
                </div>

                <!-- Package 3 -->
                <div class="menu-card bg-white rounded-xl shadow-lg p-8 border border-gray-100">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 bg-amber-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-heart text-amber-600 text-2xl"></i>
                        </div>
                        <h3 class="playfair text-2xl font-bold mb-2">Paket Classic</h3>
                        <p class="text-amber-600 font-bold text-2xl">Rp 1.200.000/100 pax</p>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>4 Menu Utama Pilihan</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>1 Menu Dessert</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Welcome Drink Classic</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Dekorasi Meja Minimalis</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-green-500 mr-3"></i>
                            <span>Pelayanan Standar</span>
                        </li>
                    </ul>
                    <button class="w-full bg-amber-600 hover:bg-amber-700 text-white py-3 rounded-lg font-semibold transition-colors">Pilih Paket</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="playfair text-4xl md:text-5xl font-bold mb-4">Galeri Pernikahan</h2>
                <p class="text-xl text-gray-600">Bukti keindahan dan kelezatan yang kami hadirkan</p>
                <div class="w-24 h-1 bg-amber-600 mx-auto mt-4"></div>
            </div>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Elegant wedding buffet setup with silver chafing dishes and floral centerpieces" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Close-up of beautifully plated wedding dishes with gourmet presentation" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Grand wedding reception hall with luxurious table settings and ambient lighting" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Wedding cake table with multi-tiered cake and dessert displays" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Bride and groom cutting wedding cake with guests applauding in background" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Elegant table setting with fine china, crystal glasses, and floral arrangements" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Professional catering staff serving guests at wedding reception" class="w-full h-64 object-cover" />
                </div>
                <div class="gallery-item rounded-lg overflow-hidden">
                    <img src="https://placehold.co/400x300" alt="Aerial view of wedding reception showing beautiful table arrangements and decor" class="w-full h-64 object-cover" />
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="playfair text-4xl md:text-5xl font-bold mb-4">Testimoni Pelanggan</h2>
                <p class="text-xl text-gray-600">Apa kata mereka tentang Pandawa Catering</p>
                <div class="w-24 h-1 bg-amber-600 mx-auto mt-4"></div>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="testimonial-card p-6 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold">Sarah & Budi</h4>
                            <p class="text-gray-600">Pernikahan, 12 Nov 2023</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"Makanannya luar biasa! Tamu-tamu semua memuji rasa dan presentasinya. Pelayanan staff juga sangat profesional."</p>
                    <div class="flex mt-4">
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                    </div>
                </div>
                <div class="testimonial-card p-6 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold">Dewi & Rizky</h4>
                            <p class="text-gray-600">Pernikahan, 5 Okt 2023</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"Dari konsultasi hingga hari H, tim Pandawa sangat membantu. Menu bisa custom sesuai request dan hasilnya memuaskan!"</p>
                    <div class="flex mt-4">
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                    </div>
                </div>
                <div class="testimonial-card p-6 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center mr-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold">Maya & Adit</h4>
                            <p class="text-gray-600">Pernikahan, 28 Sep 2023</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"Worth every penny! Dekorasi meja sangat elegant dan makanan masih hangat sampai acara selesai. Highly recommended!"</p>
                    <div class="flex mt-4">
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                        <i class="fas fa-star text-amber-400"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-900 text-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="playfair text-4xl md:text-5xl font-bold mb-4">Hubungi Kami</h2>
                <p class="text-xl text-gray-300">Konsultasi gratis untuk pernikahan impian Anda</p>
                <div class="w-24 h-1 bg-amber-600 mx-auto mt-4"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-bold mb-6">Informasi Kontak</h3>
                    <div class="space-y-6">
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-600 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Alamat</h4>
                                <p class="text-gray-300">Jalan Swadaya 1 No 16B<br>Kota Bekasi Jatimakmur<br>Pondok Gede</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-600 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Telepon</h4>
                                <p class="text-gray-300">0896-5473-6212</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-600 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Email</h4>
                                <p class="text-gray-300">pandawacatering@gmail.com</p>
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-amber-600 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold">Jam Operasional</h4>
                                <p class="text-gray-300">Senin - Minggu: 08:00 - 22:00</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div>
                    <h3 class="text-2xl font-bold mb-6">Form Konsultasi</h3>
                    <form class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-medium mb-2">Nama Lengkap</label>
                                <input type="text" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg focus:outline-none focus:border-amber-600" placeholder="Nama Anda">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Email</label>
                                <input type="email" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg focus:outline-none focus:border-amber-600" placeholder="email@contoh.com">
                            </div>
                        </div>
                        <div class="grid md:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-medium mb-2">Telepon</label>
                                <input type="tel" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg focus:outline-none focus:border-amber-600" placeholder="08xx-xxxx-xxxx">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Tanggal Acara</label>
                                <input type="date" class="w-full px-4 py-3 bg-gray-800 border border-gray-700 rounded-lg focus:outline-none focus:border-amber-600">
                            </div>
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-2">Jumlah Tamu</label>
                            <select class="w-full px-4 py-3
