<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pandawa Catering - Elegant Catering Service</title>
    <style>
        :root {
            --gold: #D4AF37;
            --dark: #1A1A1A;
            --light: #F5F5F5;
            --soft-gold: #F0E6D2;
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Playfair Display', serif;
        }
        
        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background-color: var(--dark);
            padding: 20px 0;
            position: fixed;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            color: var(--gold);
            font-size: 28px;
            font-weight: 700;
            letter-spacing: 2px;
        }
        
        .logo span {
            color: white;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 30px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 16px;
            transition: var(--transition);
        }
        
        nav ul li a:hover {
            color: var(--gold);
        }
        
        /* Hero Section */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://placehold.co/1920x1080');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            position: relative;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 60px;
            margin-bottom: 20px;
            color: var(--gold);
            animation: fadeIn 1.5s ease;
        }
        
        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
            animation: fadeIn 2s ease;
        }
        
        .btn {
            display: inline-block;
            background-color: var(--gold);
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 30px;
            font-size: 16px;
            cursor: pointer;
            transition: var(--transition);
            text-decoration: none;
            animation: fadeIn 2.5s ease;
        }
        
        .btn:hover {
            background-color: white;
            color: var(--dark);
            transform: translateY(-3px);
        }
        
        /* About Section */
        .about {
            padding: 100px 0;
            background-color: white;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 60px;
            font-size: 36px;
            color: var(--dark);
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 100px;
            height: 3px;
            background-color: var(--gold);
            margin: 20px auto;
        }
        
        .about-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            gap: 40px;
        }
        
        .about-text {
            flex: 1;
            min-width: 300px;
        }
        
        .about-text h3 {
            font-size: 24px;
            margin-bottom: 20px;
            color: var(--gold);
        }
        
        .about-text p {
            margin-bottom: 20px;
            font-size: 16px;
        }
        
        .about-image {
            flex: 1;
            min-width: 300px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .about-image img {
            width: 100%;
            height: auto;
            transition: var(--transition);
        }
        
        .about-image img:hover {
            transform: scale(1.05);
        }
        
        /* Services Section */
        .services {
            padding: 100px 0;
            background-color: #f9f9f9;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            transition: var(--transition);
            text-align: center;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .service-icon {
            font-size: 40px;
            color: var(--gold);
            margin-bottom: 20px;
        }
        
        .service-card h3 {
            font-size: 22px;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        .service-card p {
            font-size: 15px;
            color: #666;
        }
        
        /* Testimonials */
        .testimonials {
            padding: 100px 0;
            background-color: var(--dark);
            color: white;
        }
        
        .testimonials .section-title {
            color: white;
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .testimonial-card {
            background-color: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 10px;
            transition: var(--transition);
        }
        
        .testimonial-card:hover {
            transform: translateY(-5px);
            background-color: rgba(255,255,255,0.15);
        }
        
        .testimonial-content {
            margin-bottom: 20px;
            font-style: italic;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .testimonial-author img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 15px;
        }
        
        .author-info h4 {
            font-size: 18px;
            margin-bottom: 5px;
            color: var(--gold);
        }
        
        .author-info p {
            font-size: 14px;
            color: #aaa;
        }
        
        /* Footer */
        footer {
            background-color: #111;
            color: white;
            padding: 80px 0 30px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            color: var(--gold);
            font-size: 20px;
            margin-bottom: 20px;
        }
        
        .footer-column p {
            margin-bottom: 10px;
            font-size: 14px;
            color: #aaa;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-links a {
            color: white;
            font-size: 20px;
            transition: var(--transition);
        }
        
        .social-links a:hover {
            color: var(--gold);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid #333;
            font-size: 14px;
            color: #777;
        }
        
        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 20px;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 10px;
            }
            
            .hero h1 {
                font-size: 48px;
            }
            
            .hero p {
                font-size: 16px;
            }
            
            .section-title {
                font-size: 32px;
            }
        }
        
        @media (max-width: 480px) {
            .hero h1 {
                font-size: 36px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">PADAWA <span>CATERING</span></div>
                <nav>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">Tentang Kami</a></li>
                        <li><a href="#services">Layanan</a></li>
                        <li><a href="#testimonials">Testimoni</a></li>
                        <li><a href="#contact">Kontak</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Pandawa Catering</h1>
                <p>Menyajikan pengalaman kuliner mewah yang tak terlupakan untuk setiap acara spesial Anda</p>
                <a href="#contact" class="btn">Hubungi Kami</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about" id="about">
        <div class="container">
            <h2 class="section-title">Tentang Pandawa Catering</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Keunggulan Layanan Kami</h3>
                    <p>Pandawa Catering telah menjadi pilihan utama bagi mereka yang menginginkan pengalaman catering mewah dan elegan. Dengan pengalaman lebih dari 2 tahun di industri catering premium, kami memahami setiap detail yang membuat acara Anda menjadi sempurna.</p>
                    <p>Setiap hidangan kami disiapkan oleh chef profesional dengan bahan-bahan terpilih yang segar dan berkualitas tinggi. Kami menghadirkan inovasi dalam setiap menu yang kami tawarkan.</p>
                    <p>Komitmen kami adalah memberikan pelayanan terbaik yang memenuhi standar tinggi Anda, mulai dari penyajian yang artistik hingga rasa yang memanjakan lidah.</p>
                </div>
                <div class="about-image">
                    <img src="https://placehold.co/600x400" alt="Chef profesional sedang menyusun makanan mewah di atas piring putih elegan dengan hiasan daun emas" />
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <h2 class="section-title">Layanan Kami</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">🍽️</div>
                    <h3>Catering Pernikahan</h3>
                    <p>Hidangan mewah untuk hari istimewa Anda, disajikan dengan penuh keanggunan dan perhatian pada setiap detail.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🎉</div>
                    <h3>Catering Acara Perusahaan</h3>
                    <p>Solusi kuliner profesional untuk acara bisnis Anda, dari meeting kecil sampai galas perusahaan.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">👨‍👩‍👧‍👦</div>
                    <h3>Catering Pribadi</h3>
                    <p>Pengalaman bersantap premium di kediaman pribadi dengan menu yang disesuaikan selera Anda.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🥂</div>
                    <h3>Paket VIP</h3>
                    <p>Paket eksklusif dengan menu spesial dan layanan butler profesional untuk tamu penting Anda.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <h2 class="section-title">Apa Kata Mereka</h2>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        "Pandawa Catering benar-benar memahami arti pelayanan premium. Setiap hidangan tidak hanya enak tapi juga disajikan dengan sangat estetik."
                    </div>
                    <div class="testimonial-author">
                        <img src="https://placehold.co/100x100" alt="Portrait wanita profesional berusia 30an dengan rambut pendek dan mengenakan business suit" />
                        <div class="author-info">
                            <h4>suseno</h4>
                            <p>Direktur Marketing</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        "Resepsi pernikahan kami berjalan sempurna berkat Pandawa Catering. Tamu-tamu masih memuji hidangannya berminggu-minggu setelah acara."
                    </div>
                    <div class="testimonial-author">
                        <img src="https://placehold.co/100x100" alt="Potret pasangan pengantin muda tersenyum dengan latar belakang dekorasi pernikahan mewah" />
                        <div class="author-info">
                            <h4>Arif & Siti</h4>
                            <p>Pengantin</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        "Sebagai event planner profesional, saya selalu merekomendasikan Pandawa Catering untuk event premium. Konsisten dalam kualitas dan pelayanan."
                    </div>
                    <div class="testimonial-author">
                        <img src="https://placehold.co/100x100" alt="Foto pria berusia 40an dengan kacamata dan kemeja formal, tampak serius namun ramah" />
                        <div class="author-info">
                            <h4>Raden Wijaya</h4>
                            <p>Event Planner</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Tentang Kami</h3>
                    <p>Pandawa Catering memberikan pengalaman kuliner mewah untuk acara istimewa Anda. Dengan fokus pada kualitas, kreativitas, dan layanan premium.</p>
                </div>
                <div class="footer-column">
                    <h3>Kontak Kami</h3>
                    <p>Jl. jl swaday 1 no 16 b</p>
                    <p>kota bekasi</p>
                    <p>Telp: 089654736212</p>
                    <p>Email: huseinsumarsono7@gmail.com</p>
                </div>
                <div class="footer-column">
                    <h3>Jam Operasional</h3>
                    <p>Senin-Jumat: 08.00 - 20.00</p>
                    <p>Sabtu: 09.00 - 18.00</p>
                    <p>Minggu: Konsultasi via telepon</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2024 Pandawa Catering. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Simple animation on scroll
        window.addEventListener('scroll', function() {
            const scrollPosition = window.scrollY;
            const header = document.querySelector('header');
            
            if (scrollPosition > 100) {
                header.style.boxShadow = '0 2px 10px rgba(0,0,0,0.2)';
            } else {
                header.style.boxShadow = '0 2px 10px rgba(0,0,0,0.1)';
            }
        });
    </script>
</body>
</html>

