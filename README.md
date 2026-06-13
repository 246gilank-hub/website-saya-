```html
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmad Gilang Pratama | Portofolio Pastel Profesional</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts: Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        pastel: {
                            cream: '#FAF9F5',
                            mint: '#E6F4EA',
                            mintDark: '#137333',
                            lavender: '#F1F0FE',
                            lavenderDark: '#4F46E5',
                            peach: '#FFF0EA',
                            peachDark: '#C2410C',
                            clay: '#F4EFEA',
                            text: '#2D3748'
                        }
                    }
                }
            }
        }
    </script>
    
    <style>
        .pastel-gradient {
            background: linear-gradient(135deg, #FAF9F5 0%, #F1F0FE 50%, #E6F4EA 100%);
        }
        .pastel-text-gradient {
            background: linear-gradient(135deg, #137333 0%, #4F46E5 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glass-pastel {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.5);
        }
        .soft-shadow {
            box-shadow: 0 10px 40px -10px rgba(79, 70, 229, 0.06);
        }
        .card-shadow {
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.02);
        }
    </style>
</head>
<body class="bg-[#FAF9F5] text-slate-800 min-h-screen antialiased">

    <!-- NAVIGATION BAR -->
    <header class="fixed top-0 left-0 w-full z-50 transition-all duration-300 glass-pastel border-b border-stone-200/40" id="main-header">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center space-x-2">
                <span class="text-lg sm:text-xl font-extrabold tracking-wider text-slate-700">G I L A N G</span>
            </a>
            
            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center space-x-8">
                <a href="#tentang" class="text-sm font-semibold text-slate-600 hover:text-indigo-650 transition-colors">Tentang Saya</a>
                <a href="#proyek" class="text-sm font-semibold text-slate-600 hover:text-indigo-650 transition-colors">Proyek &amp; Riset</a>
                <a href="#kemampuan" class="text-sm font-semibold text-slate-600 hover:text-indigo-650 transition-colors">Keahlian</a>
                <a href="#pengalaman" class="text-sm font-semibold text-slate-600 hover:text-indigo-650 transition-colors">Lini Masa</a>
                <a href="#kontak" class="px-6 py-2.5 rounded-full bg-slate-900 hover:bg-slate-800 text-sm font-bold text-white shadow-md transition-all duration-350">Hubungi Saya</a>
            </nav>

            <!-- Mobile Nav Toggle -->
            <button class="md:hidden text-2xl text-slate-700 focus:outline-none" id="mobile-menu-btn" onclick="toggleMobileMenu()">
                <i class="fa-solid fa-bars-staggered" id="menu-icon"></i>
            </button>
        </div>

        <!-- Mobile Drawer -->
        <div class="hidden md:hidden absolute top-20 left-0 w-full bg-white/95 border-b border-stone-200/80 flex flex-col p-6 space-y-4" id="mobile-drawer">
            <a href="#tentang" class="text-lg font-semibold text-slate-600 border-b border-stone-100 pb-2" onclick="toggleMobileMenu()">Tentang Saya</a>
            <a href="#proyek" class="text-lg font-semibold text-slate-600 border-b border-stone-100 pb-2" onclick="toggleMobileMenu()">Proyek &amp; Riset</a>
            <a href="#kemampuan" class="text-lg font-semibold text-slate-600 border-b border-stone-100 pb-2" onclick="toggleMobileMenu()">Keahlian</a>
            <a href="#pengalaman" class="text-lg font-semibold text-slate-600 border-b border-stone-100 pb-2" onclick="toggleMobileMenu()">Lini Masa</a>
            <a href="#kontak" class="w-full text-center py-3 rounded-full bg-slate-900 font-bold text-white shadow-lg" onclick="toggleMobileMenu()">Hubungi Saya</a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="min-h-screen flex items-center pt-28 pb-16 relative overflow-hidden pastel-gradient">
        <!-- Floating decorative blobs for soft pastel style -->
        <div class="absolute top-1/4 left-5 w-72 h-72 bg-emerald-100/50 rounded-full blur-3xl"></div>
        <div class="absolute bottom-1/4 right-5 w-80 h-80 bg-violet-100/50 rounded-full blur-3xl"></div>
        <div class="absolute top-1/3 right-1/4 w-64 h-64 bg-orange-100/40 rounded-full blur-3xl"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 w-full grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            
            <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                <span class="inline-flex items-center px-4 py-1.5 rounded-full bg-white text-slate-700 text-xs sm:text-sm font-semibold border border-stone-200 shadow-sm">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 mr-2 animate-pulse"></span> Tersedia Untuk Riset &amp; Bisnis
                </span>
                
                <h1 class="text-4xl sm:text-5xl lg:text-6.5xl font-extrabold tracking-tight text-slate-900 leading-tight">
                    Ahmad Gilang <br class="hidden sm:inline" />
                    <span class="pastel-text-gradient">Pratama</span>
                </h1>
                
                <h2 class="text-lg sm:text-2xl font-bold text-slate-600 flex justify-center lg:justify-start items-center space-x-2">
                    <span>Spesialisasi</span>
                    <span class="border-r-2 border-slate-400 pr-2 text-indigo-600" id="typing-text">Riset &amp; Inovasi</span>
                </h2>
                
                <p class="text-slate-500 text-sm sm:text-base max-w-xl mx-auto lg:mx-0 leading-relaxed">
                    Menghubungkan logika analitis sains material, perancangan bisnis modern, estetika ramah lingkungan, serta rekam jejak operasional kasir ritel yang cekatan dan akurat.
                </p>
                
                <div class="flex flex-col sm:flex-row justify-center lg:justify-start gap-4">
                    <a href="#proyek" class="px-8 py-4 rounded-full bg-slate-900 hover:bg-slate-800 font-bold text-white shadow-md transform hover:-translate-y-0.5 transition-all text-center text-sm">
                        <i class="fa-solid fa-compass mr-2"></i> Jelajahi Proyek &amp; Riset
                    </a>
                    <a href="#kontak" class="px-8 py-4 rounded-full bg-white hover:bg-stone-50 border border-stone-200 shadow-sm font-bold text-slate-700 transition-all text-center text-sm">
                        Hubungi Saya <i class="fa-solid fa-arrow-right ml-2"></i>
                    </a>
                </div>
            </div>
            
            <!-- Hero Profile Image Component -->
            <div class="lg:col-span-5 flex justify-center">
                <div class="relative w-full max-w-sm">
                    <!-- Pastel background offsets -->
                    <div class="absolute -inset-1.5 bg-gradient-to-tr from-emerald-200 via-indigo-150 to-orange-200 rounded-3xl blur-md opacity-70"></div>
                    
                    <div class="relative bg-white rounded-3xl p-5 border border-stone-200/50 shadow-xl flex flex-col items-center">
                        <div class="w-full h-80 rounded-2xl bg-stone-100 overflow-hidden relative border border-stone-100 mb-5 group">
                            <!-- Integrated User Photo -->
                            <img src="IMG-20260413-WA0063.jpg" alt="Ahmad Gilang Pratama" class="w-full h-full object-cover object-top transition-transform duration-700 group-hover:scale-105" onerror="this.onerror=null; this.src='data:image/svg+xml;utf8,<svg xmlns=%22http://www.w3.org/2000/svg%22 width=%22100%22 height=%22100%22 viewBox=%220 0 100 100%22><rect width=%22100%22 height=%22100%22 fill=%22%23f4efe9%22/><text x=%2250%22.5 y=%2250%22 font-size=%228%22 text-anchor=%22middle%22 fill=%22%238b5cf6%22 font-family=%22sans-serif%22 font-weight=%22bold%22>IMG-20260413-WA0063.jpg</text></svg>';">
                            
                            <div class="absolute bottom-4 left-4 right-4 bg-white/95 backdrop-blur-md px-4 py-2.5 rounded-xl border border-stone-200/40 shadow-sm">
                                <p class="text-xs font-bold text-slate-800">Ahmad Gilang Pratama</p>
                                <p class="text-[10px] text-slate-500">MIPA SMAN 1 Sukodadi</p>
                            </div>
                        </div>
                        
                        <div class="grid grid-cols-3 gap-2 w-full text-center">
                            <div class="p-2.5 rounded-xl bg-pastel-mint border border-emerald-100/60">
                                <span class="text-xs font-bold text-emerald-800 block">Sains</span>
                                <span class="text-[9px] text-emerald-600 block mt-0.5">Bioplastik</span>
                            </div>
                            <div class="p-2.5 rounded-xl bg-pastel-lavender border border-indigo-100/60">
                                <span class="text-xs font-bold text-indigo-800 block">Bisnis</span>
                                <span class="text-[9px] text-indigo-600 block mt-0.5">SWIBUMA</span>
                            </div>
                            <div class="p-2.5 rounded-xl bg-pastel-peach border border-orange-100/60">
                                <span class="text-xs font-bold text-orange-800 block">Mode</span>
                                <span class="text-[9px] text-orange-600 block mt-0.5">UNIERA</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
        </div>
    </section>

    <!-- TENTANG SAYA -->
    <section id="tentang" class="py-24 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-indigo-600 text-xs font-extrabold tracking-widest uppercase bg-pastel-lavender px-4 py-1.5 rounded-full">Filosofi &amp; Profil</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Keseimbangan Antara Riset Dan Aplikasi Bisnis</h2>
                <div class="w-12 h-1 bg-indigo-500 mx-auto rounded-full mt-3"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-6 space-y-6 text-slate-600 text-sm sm:text-base leading-relaxed">
                    <p>
                        Saya adalah lulusan MIPA **SMAN 1 Sukodadi Lamongan** (Kurikulum Merdeka, Lulus Mei 2025) dengan minat mendalam pada pengembangan produk sirkular, sains material, serta riset pasar operasional.
                    </p>
                    <p>
                        Pengalaman lapangan saya sebagai **Kasir di Toko Gading Kuning Lamongan** (September 2025 - Sekarang) melatih ketahanan kerja tinggi, ketelitian transaksi harian melayani 200+ pelanggan (arus transaksi mencapai 80 juta per sif 10 jam kerja), serta kemampuan komunikasi persuasif yang sangat berharga untuk penawaran produk.
                    </p>
                    <p class="border-l-4 border-emerald-300 pl-4 bg-pastel-mint/30 py-3 rounded-r-xl">
                        Di sisi konseptual akademis, saya memimpin penyusunan proposal bisnis dan riset laboratorium di kancah nasional, seperti **LKTI REACTOR 2024, FIKSI, dan Universitas Muhammadiyah Lamongan**. Saya mahir dalam visualisasi data menggunakan Google Spreadsheets, desain visual Canva, serta integrasi teknologi kecerdasan buatan (Prompting).
                    </p>
                </div>

                <div class="lg:col-span-6 grid grid-cols-2 gap-4">
                    <div class="p-6 rounded-2xl bg-pastel-mint border border-emerald-100 flex flex-col justify-between h-40">
                        <span class="text-3xl text-emerald-600"><i class="fa-solid fa-flask"></i></span>
                        <div>
                            <h4 class="font-bold text-slate-800 text-sm sm:text-base">Inovasi Bioplastik</h4>
                            <p class="text-[10px] sm:text-xs text-slate-500 mt-1">Sintesis limbah kulit jagung &amp; bionanokomposit nanas.</p>
                        </div>
                    </div>
                    <div class="p-6 rounded-2xl bg-pastel-lavender border border-indigo-100 flex flex-col justify-between h-40">
                        <span class="text-3xl text-indigo-600"><i class="fa-solid fa-chart-pie"></i></span>
                        <div>
                            <h4 class="font-bold text-slate-800 text-sm sm:text-base">Business Plan</h4>
                            <p class="text-[10px] sm:text-xs text-slate-500 mt-1">Top 10 Universitas Muhammadiyah Lamongan.</p>
                        </div>
                    </div>
                    <div class="p-6 rounded-2xl bg-pastel-peach border border-orange-100 flex flex-col justify-between h-40">
                        <span class="text-3xl text-orange-600"><i class="fa-solid fa-shirt"></i></span>
                        <div>
                            <h4 class="font-bold text-slate-800 text-sm sm:text-base">Sustainable Fashion</h4>
                            <p class="text-[10px] sm:text-xs text-slate-500 mt-1">Vest sekaligus tas multifungsi kain tenun tradisional.</p>
                        </div>
                    </div>
                    <div class="p-6 rounded-2xl bg-[#F4EFEA] border border-stone-200 flex flex-col justify-between h-40">
                        <span class="text-3xl text-stone-600"><i class="fa-solid fa-cash-register"></i></span>
                        <div>
                            <h4 class="font-bold text-slate-800 text-sm sm:text-base">Akurasi Transaksi</h4>
                            <p class="text-[10px] sm:text-xs text-slate-500 mt-1">Mengelola 80 juta per sif di lingkungan ritel dinamis.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PROYEK & RISET INTERAKTIF -->
    <section id="proyek" class="py-24 bg-[#FAF9F5] relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-emerald-700 text-xs font-extrabold tracking-widest uppercase bg-pastel-mint px-4 py-1.5 rounded-full">Katalog Karya</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Karya Ilmiah &amp; Proyek Unggulan</h2>
                <div class="w-12 h-1 bg-emerald-500 mx-auto rounded-full mt-3"></div>
                <p class="text-slate-500 text-xs sm:text-sm">Eksplorasi secara interaktif proposal riset, pemetaan BMC, dan SWOT analitis dari proyek-proyek saya.</p>
            </div>

            <!-- Filter Controls -->
            <div class="flex flex-wrap justify-center gap-2.5 mb-12">
                <button onclick="filterProjects('semua')" id="btn-semua" class="filter-btn active px-5 py-2 rounded-full font-bold text-xs sm:text-sm transition-all duration-300 bg-slate-900 text-white shadow-sm">Semua</button>
                <button onclick="filterProjects('sains')" id="btn-sains" class="filter-btn px-5 py-2 rounded-full font-bold text-xs sm:text-sm transition-all duration-300 bg-white text-slate-600 hover:bg-stone-100 border border-stone-200 shadow-sm">Riset &amp; Sains</button>
                <button onclick="filterProjects('bisnis')" id="btn-bisnis" class="filter-btn px-5 py-2 rounded-full font-bold text-xs sm:text-sm transition-all duration-300 bg-white text-slate-600 hover:bg-stone-100 border border-stone-200 shadow-sm">Perencanaan Bisnis</button>
                <button onclick="filterProjects('fashion')" id="btn-fashion" class="filter-btn px-5 py-2 rounded-full font-bold text-xs sm:text-sm transition-all duration-300 bg-white text-slate-600 hover:bg-stone-100 border border-stone-200 shadow-sm">Fashion &amp; Budaya</button>
            </div>

            <!-- Grid Konten -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8" id="projects-container">
                
                <!-- UNIERA -->
                <div class="project-card bg-white rounded-3xl overflow-hidden border border-stone-200/60 flex flex-col group h-[480px] card-shadow hover:-translate-y-1.5 transition-all duration-300" data-category="fashion">
                    <div class="relative h-48 bg-pastel-peach flex items-center justify-center overflow-hidden">
                        <!-- Clean Vector SVG Minimalist Asset instead of bad placeholders -->
                        <div class="absolute inset-0 bg-gradient-to-tr from-orange-50 to-orange-100 flex flex-col items-center justify-center p-4">
                            <svg class="w-16 h-16 text-orange-400 group-hover:scale-110 transition-transform duration-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                            </svg>
                            <span class="text-[10px] uppercase tracking-widest text-orange-700 font-extrabold mt-3">UNIERA FASHION</span>
                        </div>
                        <span class="absolute top-4 right-4 px-3 py-1 bg-white border border-orange-200/50 text-orange-700 text-[10px] font-extrabold rounded-full">Creative Business</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div class="space-y-3">
                            <h3 class="text-lg font-extrabold text-slate-900 group-hover:text-orange-700 transition-colors">UNIERA (Tunica et Pera)</h3>
                            <p class="text-xs sm:text-sm text-slate-500 leading-relaxed line-clamp-3">Inovasi vest multifungsi sekaligus tas selempang penunjang zero waste mode yang berpadu dengan kearifan lokal Kain Tenun Ikat Paradila khas Lamongan.</p>
                        </div>
                        <div class="mt-6 flex items-center justify-between border-t border-stone-100 pt-4">
                            <span class="text-xs text-slate-400"><i class="fa-solid fa-calendar mr-1"></i> Agustus 2024</span>
                            <button onclick="openModal('uniera')" class="px-4 py-2 rounded-xl bg-pastel-peach text-orange-700 border border-orange-100/60 font-bold text-xs transition-colors hover:bg-orange-100/60">Detail Proyek</button>
                        </div>
                    </div>
                </div>

                <!-- SWIBUMA -->
                <div class="project-card bg-white rounded-3xl overflow-hidden border border-stone-200/60 flex flex-col group h-[480px] card-shadow hover:-translate-y-1.5 transition-all duration-300" data-category="bisnis">
                    <div class="relative h-48 bg-pastel-lavender flex items-center justify-center overflow-hidden">
                        <div class="absolute inset-0 bg-gradient-to-tr from-indigo-50 to-indigo-100 flex flex-col items-center justify-center p-4">
                            <svg class="w-16 h-16 text-indigo-400 group-hover:scale-110 transition-transform duration-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 13.5a3 3 0 100-6 3 3 0 000 6z"></path>
                            </svg>
                            <span class="text-[10px] uppercase tracking-widest text-indigo-700 font-extrabold mt-3">SWIBUMA BOBA</span>
                        </div>
                        <span class="absolute top-4 right-4 px-3 py-1 bg-white border border-indigo-200/50 text-indigo-700 text-[10px] font-extrabold rounded-full">Economic Festival</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div class="space-y-3">
                            <h3 class="text-lg font-extrabold text-slate-900 group-hover:text-indigo-700 transition-colors">SWIBUMA (Sweet Bubble Gogguma)</h3>
                            <p class="text-xs sm:text-sm text-slate-500 leading-relaxed line-clamp-3">Inovasi minuman boba sehat bernutrisi tinggi berbasis ubi jalar ungu lokal Lamongan untuk optimalisasi kesehatan gizi era Society 5.0.</p>
                        </div>
                        <div class="mt-6 flex items-center justify-between border-t border-stone-100 pt-4">
                            <span class="text-xs text-slate-400"><i class="fa-solid fa-calendar mr-1"></i> November 2023</span>
                            <button onclick="openModal('swibuma')" class="px-4 py-2 rounded-xl bg-pastel-lavender text-indigo-700 border border-indigo-100/60 font-bold text-xs transition-colors hover:bg-indigo-100/60">Detail Proyek</button>
                        </div>
                    </div>
                </div>

                <!-- LKTI REACTOR 2024 -->
                <div class="project-card bg-white rounded-3xl overflow-hidden border border-stone-200/60 flex flex-col group h-[480px] card-shadow hover:-translate-y-1.5 transition-all duration-300" data-category="sains">
                    <div class="relative h-48 bg-pastel-mint flex items-center justify-center overflow-hidden">
                        <div class="absolute inset-0 bg-gradient-to-tr from-emerald-50 to-emerald-100 flex flex-col items-center justify-center p-4">
                            <svg class="w-16 h-16 text-emerald-400 group-hover:scale-110 transition-transform duration-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path>
                            </svg>
                            <span class="text-[10px] uppercase tracking-widest text-emerald-700 font-extrabold mt-3">BIOPLASTIK R&amp;D</span>
                        </div>
                        <span class="absolute top-4 right-4 px-3 py-1 bg-white border border-emerald-200/50 text-emerald-700 text-[10px] font-extrabold rounded-full">Karya Tulis Ilmiah</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between">
                        <div class="space-y-3">
                            <h3 class="text-lg font-extrabold text-slate-900 group-hover:text-emerald-700 transition-colors">LKTI REACTOR 2024</h3>
                            <p class="text-xs sm:text-sm text-slate-500 leading-relaxed line-clamp-3">Sintesis pembuatan bioplastik biodegradable berbasis kulit biji jagung (Zea mays) yang diperkuat bionanokomposit serat daun nanas.</p>
                        </div>
                        <div class="mt-6 flex items-center justify-between border-t border-stone-100 pt-4">
                            <span class="text-xs text-slate-400"><i class="fa-solid fa-calendar mr-1"></i> Nov/Jan 2024</span>
                            <button onclick="openModal('lkti')" class="px-4 py-2 rounded-xl bg-pastel-mint text-emerald-700 border border-emerald-100/60 font-bold text-xs transition-colors hover:bg-emerald-100/60">Detail Proyek</button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- PORTFOLIO LIGHT-PASTEL INTERACTIVE MODAL -->
    <div id="project-modal" class="hidden fixed inset-0 z-50 overflow-y-auto bg-stone-900/60 backdrop-blur-md flex items-center justify-center p-4">
        <div class="bg-[#FAF9F5] max-w-4xl w-full rounded-3xl overflow-hidden shadow-2xl relative border border-stone-200/80 transform transition-all duration-300" id="modal-content">
            <!-- Modal Close Button -->
            <button onclick="closeModal()" class="absolute top-5 right-5 text-2xl text-slate-400 hover:text-slate-700 transition-colors z-15">
                <i class="fa-solid fa-circle-xmark"></i>
            </button>
            <div id="modal-dynamic-body" class="p-6 sm:p-8 space-y-6 max-h-[90vh] overflow-y-auto">
                <!-- Content injected via JS -->
            </div>
        </div>
    </div>

    <!-- KEMAMPUAN / PASTEL PROGRESS METERS -->
    <section id="kemampuan" class="py-24 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-indigo-600 text-xs font-extrabold tracking-widest uppercase bg-pastel-lavender px-4 py-1.5 rounded-full">Metrik Keahlian</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Keahlian Utama &amp; Penunjang Kerja</h2>
                <div class="w-12 h-1 bg-indigo-500 mx-auto rounded-full mt-3"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <!-- Left: Hard Skills (Meters) -->
                <div class="space-y-6">
                    <h3 class="text-lg font-bold text-slate-800 mb-4 flex items-center"><i class="fa-solid fa-layer-group text-emerald-600 mr-2"></i> Penguasaan Teknis &amp; Alat</h3>
                    
                    <div class="space-y-5">
                        <!-- Excel Skill -->
                        <div>
                            <div class="flex justify-between text-xs sm:text-sm font-bold mb-1">
                                <span class="text-slate-700">Google Spreadsheets (Advanced: XLOOKUP, Pivot Tables, Dashboards)</span>
                                <span class="text-emerald-700">90%</span>
                            </div>
                            <div class="h-3 bg-stone-100 rounded-full overflow-hidden p-0.5 border border-stone-200/50">
                                <div class="h-full bg-emerald-400/80 rounded-full transition-all duration-1000 w-[90%]"></div>
                            </div>
                        </div>
                        <!-- Business Analysis Skill -->
                        <div>
                            <div class="flex justify-between text-xs sm:text-sm font-bold mb-1">
                                <span class="text-slate-700">Analisis Strategis (SWOT, Business Model Canvas, Perencanaan HPP)</span>
                                <span class="text-emerald-700">85%</span>
                            </div>
                            <div class="h-3 bg-stone-100 rounded-full overflow-hidden p-0.5 border border-stone-200/50">
                                <div class="h-full bg-emerald-400/80 rounded-full transition-all duration-1000 w-[85%]"></div>
                            </div>
                        </div>
                        <!-- Graphic Design -->
                        <div>
                            <div class="flex justify-between text-xs sm:text-sm font-bold mb-1">
                                <span class="text-slate-700">Canva (Branding Visual, Desain Proposal &amp; Poster Kreatif)</span>
                                <span class="text-emerald-700">80%</span>
                            </div>
                            <div class="h-3 bg-stone-100 rounded-full overflow-hidden p-0.5 border border-stone-200/50">
                                <div class="h-full bg-emerald-400/80 rounded-full transition-all duration-1000 w-[80%]"></div>
                            </div>
                        </div>
                        <!-- Lab R&D -->
                        <div>
                            <div class="flex justify-between text-xs sm:text-sm font-bold mb-1">
                                <span class="text-slate-700">Sintesis Kimia Polimer, Ekstraksi Biomassa &amp; Standardisasi ASTM</span>
                                <span class="text-emerald-700">75%</span>
                            </div>
                            <div class="h-3 bg-stone-100 rounded-full overflow-hidden p-0.5 border border-stone-200/50">
                                <div class="h-full bg-emerald-400/80 rounded-full transition-all duration-1000 w-[75%]"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right: Adaptability & Interpersonal -->
                <div class="space-y-6">
                    <h3 class="text-lg font-bold text-slate-800 mb-4 flex items-center"><i class="fa-solid fa-heart text-indigo-600 mr-2"></i> Adaptabilitas &amp; Kualitas Kerja</h3>
                    
                    <div class="grid grid-cols-2 gap-4">
                        <div class="p-5 rounded-2xl bg-pastel-mint border border-emerald-100 text-center">
                            <span class="text-2xl text-emerald-600 block mb-2"><i class="fa-solid fa-headset"></i></span>
                            <h4 class="font-bold text-xs sm:text-sm text-slate-800">Layanan Pelanggan</h4>
                            <p class="text-[10px] text-slate-500 mt-1">Menguasai teknik up-selling persuasif &amp; pemecahan keluhan secara taktis.</p>
                        </div>
                        <div class="p-5 rounded-2xl bg-pastel-lavender border border-indigo-100 text-center">
                            <span class="text-2xl text-indigo-600 block mb-2"><i class="fa-solid fa-brain"></i></span>
                            <h4 class="font-bold text-xs sm:text-sm text-slate-800">Kecerdasan Buatan (AI)</h4>
                            <p class="text-[10px] text-slate-500 mt-1">ChatGPT &amp; Gemini Prompting untuk riset pasar &amp; riset material cepat.</p>
                        </div>
                        <div class="p-5 rounded-2xl bg-pastel-peach border border-orange-100 text-center">
                            <span class="text-2xl text-orange-600 block mb-2"><i class="fa-solid fa-people-group"></i></span>
                            <h4 class="font-bold text-xs sm:text-sm text-slate-800">Manajemen Tim</h4>
                            <p class="text-[10px] text-slate-500 mt-1">Memimpin kolaborasi riset, pembagian peran divisi keuangan &amp; produksi.</p>
                        </div>
                        <div class="p-5 rounded-2xl bg-[#F4EFEA] border border-stone-200 text-center">
                            <span class="text-2xl text-stone-600 block mb-2"><i class="fa-solid fa-bolt"></i></span>
                            <h4 class="font-bold text-xs sm:text-sm text-slate-800">Adaptasi Cepat</h4>
                            <p class="text-[10px] text-slate-500 mt-1">Fleksibel menyesuaikan ritme operasional kasir &amp; tantangan riset akademis.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- LINI MASA PENGALAMAN & PRESTASI -->
    <section id="pengalaman" class="py-24 bg-[#FAF9F5] relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-orange-700 text-xs font-extrabold tracking-widest uppercase bg-pastel-peach px-4 py-1.5 rounded-full">Jejak Langkah</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Perjalanan &amp; Pencapaian Akademis</h2>
                <div class="w-12 h-1 bg-orange-500 mx-auto rounded-full mt-3"></div>
            </div>

            <!-- Timeline -->
            <div class="relative max-w-3xl mx-auto border-l-2 border-stone-200">
                
                <!-- Item 1: RETAIL WORK -->
                <div class="mb-12 pl-8 relative">
                    <div class="absolute -left-3 top-1.5 w-5 h-5 rounded-full bg-emerald-400 border-4 border-[#FAF9F5]"></div>
                    <span class="text-[10px] font-extrabold text-emerald-800 uppercase tracking-wider bg-pastel-mint px-3 py-1 rounded-full border border-emerald-100">September 2025 - Sekarang</span>
                    <h3 class="text-lg sm:text-xl font-extrabold mt-2 text-slate-900">Kasir Ritel Utama</h3>
                    <h4 class="text-xs sm:text-sm text-slate-500 font-semibold">Toko Gading Kuning Lamongan</h4>
                    <p class="text-xs sm:text-sm text-slate-400 mt-2 leading-relaxed">
                        Bertanggung jawab atas efisiensi transaksi harian, melayani 200+ pelanggan dengan total transaksi mencapai 80 juta per sif 10 jam. Mengelola inventarisasi, pemisahan barang kadaluarsa/cacat, serta pelaporan keuangan berkala kepada pemilik toko.
                    </p>
                </div>

                <!-- Item 2: LKTI REACTOR -->
                <div class="mb-12 pl-8 relative">
                    <div class="absolute -left-3 top-1.5 w-5 h-5 rounded-full bg-indigo-400 border-4 border-[#FAF9F5]"></div>
                    <span class="text-[10px] font-extrabold text-indigo-800 uppercase tracking-wider bg-pastel-lavender px-3 py-1 rounded-full border border-indigo-100">Desember 2024 - Januari 2025</span>
                    <h3 class="text-lg sm:text-xl font-extrabold mt-2 text-slate-900">Semifinalis LKTI REACTOR 2024</h3>
                    <h4 class="text-xs sm:text-sm text-slate-500 font-semibold">Institut Teknologi Bandung (ITB)</h4>
                    <p class="text-xs sm:text-sm text-slate-400 mt-2 leading-relaxed">
                        Membangun proposal riset dan merancang eksperimen sintesis bioplastik biodegradable ramah lingkungan dari limbah pati kulit jagung dengan penguatan selulosa bionanokomposit daun nanas yang tahan air.
                    </p>
                </div>

                <!-- Item 3: UNIERA -->
                <div class="mb-12 pl-8 relative">
                    <div class="absolute -left-3 top-1.5 w-5 h-5 rounded-full bg-orange-400 border-4 border-[#FAF9F5]"></div>
                    <span class="text-[10px] font-extrabold text-orange-800 uppercase tracking-wider bg-pastel-peach px-3 py-1 rounded-full border border-orange-100">Agustus 2024</span>
                    <h3 class="text-lg sm:text-xl font-extrabold mt-2 text-slate-900">Inovator Utama Proyek UNIERA</h3>
                    <h4 class="text-xs sm:text-sm text-slate-500 font-semibold">Kompetisi Creative Business BMC SMAN 1 Sukodadi</h4>
                    <p class="text-xs sm:text-sm text-slate-400 mt-2 leading-relaxed">
                        Bertindak sebagai Ketua Tim "Kita Bangkit" dalam merancang proposal bisnis 2-in-1 vest multifungsi berpadu tas berbahan baku daur ulang kain perca dan Kain Tenun Tradisional Paradila khas Lamongan.
                    </p>
                </div>

                <!-- Item 4: SWIBUMA -->
                <div class="mb-12 pl-8 relative">
                    <div class="absolute -left-3 top-1.5 w-5 h-5 rounded-full bg-indigo-300 border-4 border-[#FAF9F5]"></div>
                    <span class="text-[10px] font-extrabold text-indigo-800 uppercase tracking-wider bg-pastel-lavender px-3 py-1 rounded-full border border-indigo-100">November 2023</span>
                    <h3 class="text-lg sm:text-xl font-extrabold mt-2 text-slate-900">Peringkat 10 Besar (Top 10) Business Plan</h3>
                    <h4 class="text-xs sm:text-sm text-slate-500 font-semibold">Economic Festival Universitas Muhammadiyah Lamongan</h4>
                    <p class="text-xs sm:text-sm text-slate-400 mt-2 leading-relaxed">
                        Merancang dan mempresentasikan produk kuliner boba ubi ungu sehat SWIBUMA sebagai solusi sirkular peningkatan nilai komoditas pertanian ubi lokal di Lamongan di era kemandirian Society 5.0.
                    </p>
                </div>

            </div>
        </div>
    </section>

    <!-- HUBUNGI SAYA / FORM KONTAK -->
    <section id="kontak" class="py-24 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-indigo-600 text-xs font-extrabold tracking-widest uppercase bg-pastel-lavender px-4 py-1.5 rounded-full">Komunikasi Sinergi</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight">Kirimkan Pesan Anda</h2>
                <div class="w-12 h-1 bg-indigo-500 mx-auto rounded-full mt-3"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                <!-- Info Column -->
                <div class="lg:col-span-5 space-y-6">
                    <h3 class="text-lg sm:text-xl font-extrabold text-slate-900">Mari Bicarakan Kerjasama</h3>
                    <p class="text-slate-500 text-xs sm:text-sm leading-relaxed">
                        Tertarik merekrut saya untuk posisi *Marketing Associate*, Asisten Laboratorium, Perencana Bisnis, atau Staf Operasional Kasir? Sampaikan perihal Anda sekarang juga melalui form atau kontak pribadi saya.
                    </p>
                    
                    <div class="space-y-4">
                        <div class="flex items-center space-x-3 text-xs sm:text-sm">
                            <span class="w-10 h-10 rounded-xl bg-pastel-lavender text-indigo-600 flex items-center justify-center text-lg"><i class="fa-solid fa-envelope"></i></span>
                            <div>
                                <p class="text-[10px] text-slate-400">Surel Resmi</p>
                                <p class="font-semibold text-slate-800">gilangpratama.business@gmail.com</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-3 text-xs sm:text-sm">
                            <span class="w-10 h-10 rounded-xl bg-pastel-mint text-emerald-600 flex items-center justify-center text-lg"><i class="fa-solid fa-phone"></i></span>
                            <div>
                                <p class="text-[10px] text-slate-400">Seluler / WhatsApp</p>
                                <p class="font-semibold text-slate-800">+62 812-5246-9060</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-3 text-xs sm:text-sm">
                            <span class="w-10 h-10 rounded-xl bg-pastel-peach text-orange-600 flex items-center justify-center text-lg"><i class="fa-solid fa-map-location-dot"></i></span>
                            <div>
                                <p class="text-[10px] text-slate-400">Domisili Sekarang</p>
                                <p class="font-semibold text-slate-800">Sukodadi, Lamongan, Jawa Timur</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Form Column -->
                <div class="lg:col-span-7">
                    <form class="p-6 sm:p-8 rounded-3xl space-y-4 bg-[#FAF9F5] border border-stone-200/80 shadow-sm" id="contact-form" onsubmit="handleContactSubmit(event)">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-[10px] font-extrabold text-slate-500 uppercase tracking-wider mb-1">Nama Lengkap</label>
                                <input type="text" required class="w-full bg-white border border-stone-200 rounded-xl px-4 py-3 text-xs sm:text-sm text-slate-800 focus:outline-none focus:border-indigo-500 transition-colors">
                            </div>
                            <div>
                                <label class="block text-[10px] font-extrabold text-slate-500 uppercase tracking-wider mb-1">Alamat Surel / Email</label>
                                <input type="email" required class="w-full bg-white border border-stone-200 rounded-xl px-4 py-3 text-xs sm:text-sm text-slate-800 focus:outline-none focus:border-indigo-500 transition-colors">
                            </div>
                        </div>
                        <div>
                            <label class="block text-[10px] font-extrabold text-slate-500 uppercase tracking-wider mb-1">Subjek / Perihal Kerja</label>
                            <input type="text" required class="w-full bg-white border border-stone-200 rounded-xl px-4 py-3 text-xs sm:text-sm text-slate-800 focus:outline-none focus:border-indigo-500 transition-colors">
                        </div>
                        <div>
                            <label class="block text-[10px] font-extrabold text-slate-500 uppercase tracking-wider mb-1">Pesan Utama Anda</label>
                            <textarea required rows="4" class="w-full bg-white border border-stone-200 rounded-xl p-4 text-xs sm:text-sm text-slate-800 focus:outline-none focus:border-indigo-500 transition-colors"></textarea>
                        </div>
                        
                        <div id="form-alert" class="hidden p-4 rounded-xl text-xs sm:text-sm font-semibold"></div>

                        <button type="submit" class="w-full py-4 rounded-xl bg-slate-900 hover:bg-slate-800 font-bold text-white shadow-md transition-all duration-300 text-xs sm:text-sm">
                            Kirim Pesan Sinergi <i class="fa-solid fa-paper-plane ml-2"></i>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-[#FAF9F5] border-t border-stone-200/50 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4">
            <span class="text-lg font-extrabold tracking-wider text-slate-700 uppercase">Ahmad Gilang Pratama</span>
            <p class="text-xs text-slate-400">&copy; 2026 Ahmad Gilang Pratama. Seluruh Hak Cipta Dilindungi.</p>
        </div>
    </footer>

    <!-- INTERACTIVE PORTFOLIO ENGINE (JAVASCRIPT) -->
    <script>
        // Typing roles dynamic effect
        const typingRoles = ["Riset & Sains", "Perencana Bisnis", "Operasional Ritel"];
        let currentRoleIndex = 0;
        let charIndex = 0;
        let isDeleting = false;
        const typingSpeed = 120;
        const typingDelay = 2200;

        function typeEffect() {
            const typingTextSpan = document.getElementById("typing-text");
            if (!typingTextSpan) return;

            const currentRole = typingRoles[currentRoleIndex];

            if (isDeleting) {
                typingTextSpan.textContent = currentRole.substring(0, charIndex - 1);
                charIndex--;
            } else {
                typingTextSpan.textContent = currentRole.substring(0, charIndex + 1);
                charIndex++;
            }

            if (!isDeleting && charIndex === currentRole.length) {
                isDeleting = true;
                setTimeout(typeEffect, typingDelay);
            } else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                currentRoleIndex = (currentRoleIndex + 1) % typingRoles.length;
                setTimeout(typeEffect, 500);
            } else {
                setTimeout(typeEffect, isDeleting ? 60 : typingSpeed);
            }
        }

        document.addEventListener("DOMContentLoaded", () => {
            typeEffect();
        });

        // Filter Projects logic
        function filterProjects(category) {
            const buttons = document.querySelectorAll('.filter-btn');
            buttons.forEach(btn => {
                btn.className = "filter-btn px-5 py-2 rounded-full font-bold text-xs sm:text-sm transition-all duration-300 bg-white text-slate-600 hover:bg-stone-100 border border-stone-200 shadow-sm";
            });

            const activeBtn = document.getElementById(`btn-${category}`);
            if (activeBtn) {
                activeBtn.className = "filter-btn active px-5 py-2 rounded-full font-bold text-xs sm:text-sm transition-all duration-300 bg-slate-900 text-white shadow-sm";
            }

            const cards = document.querySelectorAll('.project-card');
            cards.forEach(card => {
                if (category === 'semua' || card.getAttribute('data-category') === category) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // Deep Analytical Project Database from uploaded PDF Papers
        const projectsData = {
            uniera: {
                title: "UNIERA (Tunica et Pera) - Sustainable Fashion",
                sub: "Inovasi Kombinasi Vest (Rompi) dan Tas yang Mendukung Konsep Zero-Waste",
                desc: "UNIERA memprioritaskan daur ulang sisa potongan kain perca katun/tile serta asimilasi kearifan lokal melalui penggunaan Kain Tenun Doby Paradila yang didirikan oleh generasi muda Desa Parengan, Maduran, Lamongan. Dapat diubah fungsi dari vest taktis trendi menjadi tas selempang instan dalam waktu singkat.",
                highlights: [
                    "<b>Aspek Keberlanjutan:</b> Berperan meminimalisir tingginya limbah fashion sekali pakai (*fast fashion*) melalui penerapan sistem upcycle-recycle sisa potongan kain perca.",
                    "<b>Identitas Kebudayaan:</b> Memperkenalkan Kain Tenun Paradila bemotif batik kolaboratif 'bandeng-lele' khas Lamongan ke kancah nasional.",
                    "<b>Target Penjualan Tahunan:</b> Kapasitas produksi tahun pertama 480 unit (40 unit/bulan) dengan harga jual Rp 350.000 per unit.",
                    "<b>Tingkat Kelayakan:</b> Total kebutuhan modal awal Rp 130.848.000, menghasilkan estimasi laba bersih Rp 40.200.000 pada tahun pertama."
                ],
                marketing: {
                    price: "Rp 350.000 / pcs",
                    target: "Masyarakat lokal &amp; luar daerah (wisatawan) usia 13-40 tahun (Milenial &amp; Gen Z).",
                    swot: {
                        s: "Konsep 2-in-1 inovatif, bahan ramah lingkungan bermutu tinggi, mempromosikan penenun lokal.",
                        w: "Proses penjahitan yang kompleks, ketergantungan pasokan tenun doby terstandar.",
                        o: "Tingginya pertumbuhan kesadaran eco-fashion di kota besar seperti Jakarta, Surabaya, &amp; Bali.",
                        t: "Gempuran pakaian impor murah manufaktur massal (fast fashion)."
                    }
                }
            },
            swibuma: {
                title: "SWIBUMA (Sweet Bubble Gogguma)",
                sub: "Inovasi Minuman Boba Ubi Ungu Sehat di Era Society 5.0",
                desc: "SWIBUMA merupakan gagasan kuliner inovatif berupa minuman boba sehat kaya nutrisi yang memanfaatkan komoditas ubi jalar ungu lokal Lamongan sebagai bahan baku utama boba organik. Mengeliminasi citra minuman manis berpengawet dan beralih ke kearifan rasa nusantara.",
                highlights: [
                    "<b>Kaya Gizi &amp; Antioksidan:</b> Mengandung antosianin alami ubi ungu (519 mg/100 g) untuk penawar racun dan imunitas, mematahkan ancaman stunting pada balita &amp; anak.",
                    "<b>Pemberdayaan Petani:</b> Bekerjasama dengan petani ubi Lamongan guna mendongkrak kestabilan harga serta kesejahteraan primer sektor pertanian.",
                    "<b>Varian Rasa Komparatif:</b> Varian Original (boba ubi ungu, gula merah jawa asli, susu UHT) dan Roasted Milk Tea (racikan teh panggang bermutu).",
                    "<b>Proyeksi Keuangan:</b> Target produksi tahun pertama 14.400 unit (8.800 Original &amp; 5.600 Roasted Milk Tea), meraup laba bersih sebesar Rp 92.834.500."
                ],
                marketing: {
                    price: "Rp 10.000 / botol (400 ml)",
                    target: "Pelajar, mahasiswa, guru, wisatawan, dan pencari alternatif asupan nutrisi praktis.",
                    swot: {
                        s: "Boba kenyal ubi ungu tanpa bahan pengawet/pewarna buatan, kaya vitamin A, B1, C.",
                        w: "Daya simpan boba relatif pendek karena bebas pengawet.",
                        o: "Generasi muda aktif menyukai kepraktisan boba kekinian dengan asupan nutrisi sehat.",
                        t: "Tingginya persaingan dari korporasi waralaba boba konvensional yang memegang pasar."
                    }
                }
            },
            lkti: {
                title: "LKTI REACTOR 2024 - R&amp;D Bioplastik Polimer",
                sub: "Sintesis Pati Kulit Jagung &amp; Bionanokomposit Selulosa Serat Daun Nanas",
                desc: "Riset laboratorium komparatif ini menginvestigasi sintesis pembuatan bioplastik biodegradable alternatif berbahan dasar pati dari limbah kulit biji jagung (Zea mays) yang diperkuat dengan pengisi selulosa serat daun nanas (Ananas Comosus L Merr) untuk meningkatkan sifat mekanis.",
                highlights: [
                    "<b>Komposisi Kimia Unggul:</b> Pati kulit jagung mengandung selulosa 44,08% dan lignin 15%, menghasilkan fleksibilitas termal yang andal.",
                    "<b>Sifat Mekanis Teruji:</b> Penambahan selulosa serat daun nanas (konsentrasi optimal 45%) meningkatkan kekuatan tarik mencapai 12,5 MPa berdasarkan uji standardisasi ASTM.",
                    "<b>Laju Biodegradasi:</b> Terurai secara sempurna di dalam tanah (*soil burial test*) hingga 90% hanya dalam kurun waktu 30 hari melalui aktivitas mikroorganisme.",
                    "<b>Sifat Hidrofobik:</b> Ikatan hidrogen inter dan intra molekuler selulosa nanas dengan pati mengurangi laju absorbsi air secara drastis."
                ],
                marketing: {
                    price: "Biaya Bahan Baku: Rp 4.966 / unit produksi standar",
                    target: "Industri pengemasan makanan, logistik retail, dan alternatif pengganti kemasan polystyrene sekali pakai.",
                    swot: {
                        s: "Laju dekomposisi ramah lingkungan tanpa polutan mikroplastik, kekuatan tarik unggul (12,5 MPa).",
                        w: "Proses preparasi serat nanas (oven 24 jam &amp; hidrolisis asam) membutuhkan akurasi tinggi.",
                        o: "Dukungan penuh regulasi pemerintah daerah/global dalam larangan kantong plastik konvensional.",
                        t: "Standardisasi kontinuitas pasokan serat nanas kering skala pabrikasi industri."
                    }
                }
            }
        };

        // Open Modal and Inject HTML content dynamically
        function openModal(projectId) {
            const data = projectsData[projectId];
            if (!data) return;

            const modal = document.getElementById('project-modal');
            const body = document.getElementById('modal-dynamic-body');
            
            // Build highlights content string
            let highlightsHtml = '';
            data.highlights.forEach(hl => {
                highlightsHtml += `<li class="text-xs sm:text-sm text-slate-650 leading-relaxed"><i class="fa-solid fa-circle-check text-emerald-600 mr-2"></i> ${hl}</li>`;
            });

            body.innerHTML = `
                <div class="space-y-6">
                    <div>
                        <span class="text-[10px] font-extrabold uppercase tracking-wider text-indigo-700 bg-pastel-lavender px-3 py-1 rounded-full border border-indigo-100">${data.sub}</span>
                        <h3 class="text-xl sm:text-2xl font-extrabold text-slate-900 mt-2.5">${data.title}</h3>
                    </div>
                    
                    <p class="text-slate-600 text-xs sm:text-sm leading-relaxed">${data.desc}</p>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 pt-2">
                        <!-- Points Column -->
                        <div class="space-y-3">
                            <h4 class="text-sm sm:text-base font-extrabold text-slate-800 border-b border-stone-200 pb-2 flex items-center">
                                <i class="fa-solid fa-star text-orange-600 mr-2"></i> Fitur &amp; Keunggulan
                            </h4>
                            <ul class="space-y-2">
                                ${highlightsHtml}
                            </ul>
                        </div>
                        
                        <!-- Financial & Plan Column -->
                        <div class="space-y-3">
                            <h4 class="text-sm sm:text-base font-extrabold text-slate-800 border-b border-stone-200 pb-2 flex items-center">
                                <i class="fa-solid fa-chart-line text-orange-600 mr-2"></i> Strategi Pemasaran
                            </h4>
                            <div class="space-y-2.5 text-xs sm:text-sm">
                                <p class="text-slate-500"><strong class="text-slate-700">Harga / Biaya Jual:</strong> ${data.marketing.price}</p>
                                <p class="text-slate-500"><strong class="text-slate-700">Target Pasar Utama:</strong> ${data.marketing.target}</p>
                            </div>
                        </div>
                    </div>

                    <!-- SWOT Matrix Segment -->
                    <div class="space-y-3 pt-3">
                        <h4 class="text-sm sm:text-base font-extrabold text-slate-800 border-b border-stone-200 pb-2 flex items-center">
                            <i class="fa-solid fa-shield-halved text-emerald-600 mr-2"></i> Pemetaan Matriks SWOT
                        </h4>
                        <div class="grid grid-cols-1 sm:grid-cols-4 gap-3 text-[10px] sm:text-xs">
                            <div class="p-3 bg-pastel-mint border border-emerald-100 rounded-2xl">
                                <h5 class="font-extrabold text-emerald-800 uppercase tracking-widest mb-1">STRENGTHS</h5>
                                <p class="text-slate-600">${data.marketing.swot.s}</p>
                            </div>
                            <div class="p-3 bg-pastel-peach border border-orange-100 rounded-2xl">
                                <h5 class="font-extrabold text-orange-800 uppercase tracking-widest mb-1">WEAKNESSES</h5>
                                <p class="text-slate-600">${data.marketing.swot.w}</p>
                            </div>
                            <div class="p-3 bg-pastel-lavender border border-indigo-100 rounded-2xl">
                                <h5 class="font-extrabold text-indigo-800 uppercase tracking-widest mb-1">OPPORTUNITIES</h5>
                                <p class="text-slate-600">${data.marketing.swot.o}</p>
                            </div>
                            <div class="p-3 bg-stone-100 border border-stone-200 rounded-2xl">
                                <h5 class="font-extrabold text-stone-700 uppercase tracking-widest mb-1">THREATS</h5>
                                <p class="text-slate-600">${data.marketing.swot.t}</p>
                            </div>
                        </div>
                    </div>
                </div>
            `;

            modal.classList.remove('hidden');
            document.body.classList.add('overflow-hidden');
        }

        function closeModal() {
            const modal = document.getElementById('project-modal');
            modal.classList.add('hidden');
            document.body.classList.remove('overflow-hidden');
        }

        // Toggle Mobile Menu Drawer
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-drawer');
            const icon = document.getElementById('menu-icon');
            drawer.classList.toggle('hidden');
            
            if (drawer.classList.contains('hidden')) {
                icon.className = "fa-solid fa-bars-staggered";
            } else {
                icon.className = "fa-solid fa-xmark";
            }
        }

        // Simulation feedback for contact form
        function handleContactSubmit(event) {
            event.preventDefault();
            const alert = document.getElementById('form-alert');
            
            alert.classList.remove('hidden', 'bg-red-50', 'text-red-700', 'bg-emerald-50', 'text-emerald-700');
            alert.classList.add('bg-emerald-50', 'text-emerald-700', 'border', 'border-emerald-200');
            alert.innerHTML = '<i class="fa-solid fa-circle-check mr-2"></i> Terima kasih! Pesan simulasi Anda telah terkirim. Gilang akan segera menghubungi Anda.';
            
            event.target.reset();
        }

        // Close modal on background click
        window.onclick = function(event) {
            const modal = document.getElementById('project-modal');
            if (event.target === modal) {
                closeModal();
            }
        }
    </script>
</body>
</html>

```
