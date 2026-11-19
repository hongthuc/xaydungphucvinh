<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH GPXD PHÚC VINH | Thiết Kế, Thi Công Nhà Trọn Gói, Sơn, Chống Thấm, Trần Sàn Ốp Nhựa Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH GPXD PHÚC VINH (phucvinh.com) - Chuyên thiết kế, thi công nhà trọn gói, sơn nước, chống thấm, cung cấp và thi công trần nhựa Nano, sàn nhựa, ốp lam sóng tại Đà Nẵng. Hotline: 0353.826.625." />

  <!-- Meta Open Graph & Favicon sử dụng Logo trang web làm ảnh thumbnail khi chia sẻ link -->
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl&sz=w256" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://phucvinh.com/" />
  <meta property="og:site_name" content="CÔNG TY TNHH GPXD PHÚC VINH" />
  <meta property="og:title" content="CÔNG TY TNHH GPXD PHÚC VINH - Thiết Kế, Thi Công Nhà Trọn Gói & Trần Sàn Ốp Nhựa Đà Nẵng" />
  <meta property="og:description" content="Chuyên thiết kế, thi công nhà trọn gói, sơn, chống thấm, cung cấp & thi công trần, sàn, ốp nhựa uy tín tại Thôn An Ngãi Đông, Phường Hòa Khánh, TP Đà Nẵng. Hotline: 0353.826.625." />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl&sz=w1000" />
  <meta property="og:image:width" content="1000" />
  <meta property="og:image:height" content="1000" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH GPXD PHÚC VINH - phucvinh.com" />
  <meta name="twitter:description" content="Thiết kế, thi công nhà trọn gói, sơn, chống thấm, trần sàn ốp nhựa tại Đà Nẵng." />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl&sz=w1000" />

  <!-- Font Inter & Tailwind CSS -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: '#0E3A5D',   /* Xanh Navy đậm chủ đạo chuyên ngành xây dựng */
              dark: '#08253D',
              accent: '#D98A1C',    /* Vàng cam xây dựng đồng bộ nhận diện thương hiệu */
              accentHover: '#BA7210',
              soft: '#F4F7FA',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Thiết lập chuẩn chống tràn viền ngang và chống lệch giao diện sang phải */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0px;
      padding: 0px;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      scroll-behavior: smooth;
      color: #1E293B;
      background-color: #FFFFFF;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% màn hình, căn giữa tuyệt đối */
    .pv-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 640px) {
      .pv-container {
        padding-left: 20px;
        padding-right: 20px;
      }
    }
    @media (min-width: 1024px) {
      .pv-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0px;
        padding-right: 0px;
      }
    }

    /* Tiêu đề Section chuẩn phong cách Flatsome UX Builder */
    .flatsome-title {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-title::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0px;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background-color: #D98A1C;
      border-radius: 999px;
    }
    .flatsome-title-left::after {
      left: 0px;
      transform: none;
    }

    /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối */
    .hero-slider-wrap {
      position: relative;
      width: 100%;
      overflow: hidden;
    }
    .hero-slides-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .hero-slide-item {
      width: 50%;
      flex-shrink: 0;
      position: relative;
      height: 310px;
    }
    @media (min-width: 640px) {
      .hero-slide-item {
        height: 390px;
      }
    }
    @media (min-width: 1024px) {
      .hero-slide-item {
        height: 470px;
      }
    }
    @media (min-width: 1280px) {
      .hero-slide-item {
        height: 520px;
      }
    }

    /* Dropdown Menu Flatsome mượt mà trên Desktop */
    .nav-dropdown-wrap:hover .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0px);
    }
    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }

    /* Hiệu ứng sóng nhẹ cho nút liên hệ nổi Hotline / Zalo / Facebook */
    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(217, 138, 28, 0.55); }
      70% { box-shadow: 0 0 0 10px rgba(217, 138, 28, 0); }
      100% { box-shadow: 0 0 0 0 rgba(217, 138, 28, 0); }
    }
    .btn-hotline-pulse {
      animation: pulseRing 2.2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ======================================================================= -->
  <!-- [FLATSOME TOP BAR] Thanh thông tin cơ bản (Không hiển thị thanh UX Builder) -->
  <!-- ======================================================================= -->
  <div class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
    <div class="pv-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="font-medium tracking-wide">CÔNG TY TNHH GPXD PHÚC VINH</span>
        <span class="hidden md:inline text-white/40">|</span>
        <span class="hidden md:inline text-slate-200">Thôn An Ngãi Đông, Phường Hòa Khánh, TP Đà Nẵng</span>
      </div>
      <div class="flex items-center gap-x-4">
        <a href="tel:0353826625" class="hover:text-brand-accent transition-colors font-semibold">Hotline: 0353.826.625</a>
        <span class="hidden sm:inline text-white/40">|</span>
        <span class="hidden sm:inline text-slate-200">phucvinh.com</span>
      </div>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- [FLATSOME MAIN HEADER] Logo gọn nhỏ + Menu 1 hàng (Không đặt nút Gọi ngay) -->
  <!-- ======================================================================= -->
  <header id="main-header" class="sticky top-0 z-40 bg-white/98 backdrop-blur-sm shadow-sm border-b border-slate-200 w-full">
    <div class="pv-container flex items-center justify-between h-16 lg:h-[74px] gap-3">
      <!-- Logo gọn nhỏ -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
        <img
          src="https://drive.google.com/thumbnail?id=1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl&sz=w400"
          alt="Logo CÔNG TY TNHH GPXD PHÚC VINH"
          class="h-10 sm:h-11 lg:h-12 w-auto max-w-[115px] object-contain rounded"
          onerror="handleImgError(this, '1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl', 'PHUC+VINH')"
        />
        <div class="leading-tight">
          <div class="text-brand-primary font-extrabold text-xs sm:text-sm lg:text-[15px] tracking-tight whitespace-nowrap">GPXD PHÚC VINH</div>
          <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium whitespace-nowrap">phucvinh.com</div>
        </div>
      </a>

      <!-- Menu Desktop: Chữ nhỏ gọn nằm liền trên 1 hàng duy nhất, không xuống dòng -->
      <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3.5 xl:gap-6 min-w-0" aria-label="Menu chính">
        <a href="#trang-chu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-brand-primary hover:text-brand-accent transition-colors whitespace-nowrap py-2">Trang chủ</a>
        <a href="#gioi-thieu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Giới thiệu</a>

        <!-- Dropdown Lĩnh vực hoạt động (theo bố cục web mẫu) -->
        <div class="relative nav-dropdown-wrap">
          <a href="#dich-vu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2 inline-flex items-center gap-1">
            <span>Lĩnh vực hoạt động</span>
            <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-64 z-50">
            <div class="bg-white rounded-lg shadow-lg border border-slate-200 py-2">
              <a href="#san-pham" onclick="filterProducts('xay-nha')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Thiết kế &amp; Thi công nhà trọn gói</a>
              <a href="#san-pham" onclick="filterProducts('son-chong-tham')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Sơn nước &amp; Chống thấm</a>
              <a href="#san-pham" onclick="filterProducts('tran-nhua')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Cung cấp &amp; Thi công trần nhựa</a>
              <a href="#san-pham" onclick="filterProducts('san-op-nhua')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Sàn nhựa &amp; Ốp tường lam sóng</a>
            </div>
          </div>
        </div>

        <a href="#san-pham" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Sản phẩm</a>
        <a href="#du-an-da-nang" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Dự án Đà Nẵng</a>
        <a href="#bao-gia" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Báo giá</a>
        <a href="#tin-tuc" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Tin tức</a>
        <a href="#doi-tac" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Đối tác</a>
        <a href="#lien-he" class="text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap py-2">Liên hệ</a>
      </nav>

      <!-- Nút mở Menu Mobile (Không đặt nút Gọi ngay trên Header) -->
      <button
        type="button"
        id="mobileMenuBtn"
        onclick="toggleMobileMenu()"
        class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-brand-primary border border-slate-200 hover:bg-slate-50 focus:outline-none"
        aria-label="Mở danh mục"
      >
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>

    <!-- Drawer Menu Mobile thân thiện cảm ứng -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg w-full">
      <div class="pv-container py-3 flex flex-col divide-y divide-slate-100">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-brand-primary">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Giới thiệu</a>
        <a href="#dich-vu" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Lĩnh vực hoạt động</a>
        <a href="#san-pham" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Danh mục sản phẩm &amp; Thi công</a>
        <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Các dự án tại Đà Nẵng</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Yêu cầu &amp; Báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Tin tức &amp; Kiến thức xây dựng</a>
        <a href="#doi-tac" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Đối tác</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="py-3 text-sm font-semibold text-slate-700">Bản đồ &amp; Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ======================================================================= -->
    <!-- [FLATSOME UX SLIDER] 2 Ảnh Banner Tự Trượt Chuyên Nghiệp Kích Thước Bằng Nhau -->
    <!-- Hình ảnh và chữ nằm gọn bên trong banner, cách xa viền, không mất chữ trên Mobile & PC -->
    <!-- ======================================================================= -->
    <section class="w-full bg-brand-dark">
      <div class="hero-slider-wrap">
        <div id="heroTrack" class="hero-slides-track">

          <!-- BANNER 1 -->
          <div class="hero-slide-item">
            <img
              src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
              alt="Thiết kế và thi công nhà trọn gói CÔNG TY TNHH GPXD PHÚC VINH"
              class="w-full h-full object-cover object-center"
              onerror="handleImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'GPXD+PHUC+VINH+DA+NANG')"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-[#08253D]/90 via-[#08253D]/70 to-[#08253D]/35"></div>
            <!-- Vùng an toàn cách xa viền ảnh banner trên mọi thiết bị -->
            <div class="absolute inset-0 flex items-center">
              <div class="pv-container">
                <div class="px-6 sm:px-12 lg:px-16 py-6 max-w-2xl text-white">
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-accent mb-2">
                    CÔNG TY TNHH GPXD PHÚC VINH • ĐÀ NẴNG
                  </p>
                  <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-3">
                    THIẾT KẾ &amp; THI CÔNG NHÀ TRỌN GÓI CHUYÊN NGHIỆP
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5">
                    Giải pháp xây dựng chuẩn kỹ thuật, đúng tiến độ, vật tư chính hãng và báo giá minh bạch tại Đà Nẵng và khu vực miền Trung.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#bao-gia" class="px-4 sm:px-6 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-semibold text-xs sm:text-sm transition-colors">
                      Nhận báo giá ngay
                    </a>
                    <a href="#du-an-da-nang" class="px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition-colors">
                      Xem dự án Đà Nẵng
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="hero-slide-item">
            <img
              src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1600"
              alt="Sơn chống thấm và cung cấp thi công trần sàn ốp nhựa Phúc Vinh"
              class="w-full h-full object-cover object-center"
              onerror="handleImgError(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_', 'TRAN+SAN+OP+NHUA+PHUC+VINH')"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-[#08253D]/90 via-[#08253D]/72 to-[#08253D]/35"></div>
            <!-- Vùng an toàn cách xa viền ảnh banner trên mọi thiết bị -->
            <div class="absolute inset-0 flex items-center">
              <div class="pv-container">
                <div class="px-6 sm:px-12 lg:px-16 py-6 max-w-2xl text-white">
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-accent mb-2">
                    HOÀN THIỆN NỘI NGOẠI THẤT BỀN ĐẸP
                  </p>
                  <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-3">
                    SƠN, CHỐNG THẤM &amp; THI CÔNG TRẦN, SÀN, ỐP NHỰA
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5">
                    Cung cấp và thi công trọn gói trần nhựa Nano, tấm ốp lam sóng, sàn nhựa SPC chịu nước, sơn chống thấm chất lượng cao.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#san-pham" class="px-4 sm:px-6 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-semibold text-xs sm:text-sm transition-colors">
                      Xem danh mục sản phẩm
                    </a>
                    <a href="#lien-he" class="px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition-colors">
                      Tư vấn miễn phí
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Banner gọn gàng sát mép ngoài vùng chữ -->
        <button
          type="button"
          onclick="moveSlide(-1)"
          class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors z-10"
          aria-label="Banner trước"
        >
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button
          type="button"
          onclick="moveSlide(1)"
          class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors z-10"
          aria-label="Banner tiếp theo"
        >
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm chỉ báo 2 banner -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
          <button type="button" onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-brand-accent transition-all" aria-label="Banner 1"></button>
          <button type="button" onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: DỊCH VỤ TIÊU BIỂU] Bố cục 4 cột đơn giản giống web mẫu -->
    <!-- ======================================================================= -->
    <section id="dich-vu" class="py-10 sm:py-14 bg-white">
      <div class="pv-container">
        <div class="text-center mb-8 sm:mb-10">
          <h2 class="flatsome-title text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase text-brand-primary">
            Dịch Vụ Tiêu Biểu
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            CÔNG TY TNHH GPXD PHÚC VINH cung cấp giải pháp trọn gói từ tư vấn thiết kế, xây dựng phần thô đến hoàn thiện sơn, chống thấm và trang trí trần, sàn, ốp nhựa.
          </p>
        </div>

        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <a href="#san-pham" onclick="filterProducts('xay-nha')" class="group bg-brand-soft rounded-xl p-4 sm:p-6 text-center border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
              <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
            </div>
            <h3 class="text-xs sm:text-sm lg:text-base font-bold uppercase text-brand-primary mb-1.5 break-words">Thiết Kế &amp; Xây Nhà Trọn Gói</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Thi công phần thô, hoàn thiện nhà phố, biệt thự chìa khóa trao tay.</p>
          </a>

          <a href="#san-pham" onclick="filterProducts('son-chong-tham')" class="group bg-brand-soft rounded-xl p-4 sm:p-6 text-center border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
              <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"/></svg>
            </div>
            <h3 class="text-xs sm:text-sm lg:text-base font-bold uppercase text-brand-primary mb-1.5 break-words">Sơn Nước &amp; Chống Thấm</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Thi công sơn nội ngoại thất, xử lý chống thấm triệt để sân thượng, tường đứng.</p>
          </a>

          <a href="#san-pham" onclick="filterProducts('tran-nhua')" class="group bg-brand-soft rounded-xl p-4 sm:p-6 text-center border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
              <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z"/></svg>
            </div>
            <h3 class="text-xs sm:text-sm lg:text-base font-bold uppercase text-brand-primary mb-1.5 break-words">Thi Công Trần Nhựa Nano</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Trần nhựa Nano phẳng, trần giật cấp giả gỗ chống ẩm mốc, cách nhiệt bền đẹp.</p>
          </a>

          <a href="#san-pham" onclick="filterProducts('san-op-nhua')" class="group bg-brand-soft rounded-xl p-4 sm:p-6 text-center border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all">
            <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 sm:mb-4 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
              <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M9 17V7m0 10a2 2 0 01-2 2H5a2 2 0 01-2-2V7a2 2 0 012-2h2a2 2 0 012 2m0 10a2 2 0 002 2h2a2 2 0 002-2M9 7a2 2 0 012-2h2a2 2 0 012 2m0 10V7m0 10a2 2 0 002 2h2a2 2 0 002-2V7a2 2 0 00-2-2h-2a2 2 0 00-2 2"/></svg>
            </div>
            <h3 class="text-xs sm:text-sm lg:text-base font-bold uppercase text-brand-primary mb-1.5 break-words">Sàn Nhựa &amp; Ốp Lam Sóng</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Cung cấp và lắp đặt sàn nhựa hèm khóa SPC, tấm ốp tường lam sóng, PVC vân đá.</p>
          </a>
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: GIỚI THIỆU & THẾ MẠNH] Giống cấu trúc web mẫu Tín Trường Thịnh -->
    <!-- ======================================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-soft border-y border-slate-200">
      <div class="pv-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10 sm:mb-12">
          <div class="lg:col-span-6">
            <h2 class="flatsome-title flatsome-title-left text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase text-brand-primary mb-4">
              CÔNG TY TNHH GPXD PHÚC VINH
            </h2>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-3">
              <strong>CÔNG TY TNHH GPXD PHÚC VINH</strong> (website: <strong>phucvinh.com</strong>) là đơn vị chuyên sâu trong lĩnh vực <strong>Thiết kế – Thi công nhà trọn gói, Sơn nước, Chống thấm và Cung cấp – Thi công Trần, Sàn, Ốp nhựa</strong> tại thành phố Đà Nẵng và các tỉnh miền Trung.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-5">
              Với phương châm đặt chất lượng và uy tín lên hàng đầu, đội ngũ kỹ sư cùng thợ thi công tay nghề cao của Phúc Vinh luôn đảm bảo mỗi công trình đạt chuẩn <strong>An toàn – Thẩm mỹ – Bền vững – Đúng tiến độ</strong> với mức chi phí tối ưu nhất cho chủ đầu tư.
            </p>
            <div class="grid grid-cols-3 gap-3 text-center">
              <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200">
                <div class="text-lg sm:text-2xl font-extrabold text-brand-accent">100+</div>
                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Công trình Đà Nẵng</div>
              </div>
              <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200">
                <div class="text-lg sm:text-2xl font-extrabold text-brand-accent">100%</div>
                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Vật tư chính hãng</div>
              </div>
              <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200">
                <div class="text-lg sm:text-2xl font-extrabold text-brand-accent">24/7</div>
                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Khảo sát &amp; Tư vấn</div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-6">
            <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
              <img
                src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1200"
                alt="Hình ảnh thi công thực tế CÔNG TY TNHH GPXD PHÚC VINH"
                class="w-full aspect-[16/10] object-cover"
                onerror="handleImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'THI+CONG+PHUC+VINH')"
              />
            </div>
          </div>
        </div>

        <!-- 6 Thế mạnh của chúng tôi (Giống web mẫu) -->
        <div class="text-center mb-6 sm:mb-8">
          <h3 class="flatsome-title text-lg sm:text-xl lg:text-2xl font-bold uppercase text-brand-primary">
            Thế Mạnh Của Chúng Tôi
          </h3>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 font-bold">01</div>
            <div>
              <h4 class="text-sm font-bold text-brand-primary mb-1">Đội ngũ kỹ sư, thợ lành nghề</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Kỹ sư giám sát giàu kinh nghiệm cùng đội thợ xây dựng, sơn chống thấm và lắp đặt nội thất nhựa tận tâm.</p>
            </div>
          </div>
          <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 font-bold">02</div>
            <div>
              <h4 class="text-sm font-bold text-brand-primary mb-1">Vật liệu hiện đại, chính hãng</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Cập nhật liên tục vật tư mới: tấm nhựa Nano, lam sóng, sàn SPC chịu nước, sơn chống thấm bền thời tiết miền Trung.</p>
            </div>
          </div>
          <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 font-bold">03</div>
            <div>
              <h4 class="text-sm font-bold text-brand-primary mb-1">Giám sát tiến độ chuẩn xác</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Báo cáo tiến độ thường xuyên, cam kết hoàn thành và bàn giao đúng thời hạn đã ký kết với gia chủ.</p>
            </div>
          </div>
          <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 font-bold">04</div>
            <div>
              <h4 class="text-sm font-bold text-brand-primary mb-1">Bảo hành công trình lâu dài</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu, chống thấm và trần sàn ốp nhựa rõ ràng, hỗ trợ nhanh chóng khi khách hàng cần.</p>
            </div>
          </div>
          <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 font-bold">05</div>
            <div>
              <h4 class="text-sm font-bold text-brand-primary mb-1">Báo giá minh bạch, hợp lý</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục ngay từ đầu, không phát sinh chi phí bất hợp lý trong quá trình thi công.</p>
            </div>
          </div>
          <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
            <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0 font-bold">06</div>
            <div>
              <h4 class="text-sm font-bold text-brand-primary mb-1">Khảo sát &amp; tư vấn miễn phí</h4>
              <p class="text-xs text-slate-600 leading-relaxed">Hỗ trợ khảo sát thực tế tận nơi tại Đà Nẵng, mang mẫu vật tư trần sàn ốp nhựa và bảng màu sơn miễn phí.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: DANH MỤC SẢN PHẨM & THI CÔNG THỰC TẾ]                 -->
    <!-- Dùng 9 ảnh thực tế từ Google Drive | 2 cột trên điện thoại | Không nhãn dán -->
    <!-- Danh mục nhỏ gọn, viết liền 1 hàng không xuống dòng tên danh mục         -->
    <!-- ======================================================================= -->
    <section id="san-pham" class="py-10 sm:py-14 bg-white">
      <div class="pv-container">
        <div class="text-center mb-6 sm:mb-8">
          <h2 class="flatsome-title text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase text-brand-primary">
            Danh Mục Sản Phẩm &amp; Thi Công Thực Tế
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            Hình ảnh thi công thực tế và các dòng sản phẩm xây dựng, sơn chống thấm, trần nhựa, sàn nhựa, tấm ốp nhựa do GPXD Phúc Vinh trực tiếp cung cấp và lắp đặt.
          </p>
        </div>

        <!-- Thanh Danh Mục Sản Phẩm: Chữ nhỏ gọn, từng tên danh mục không xuống dòng -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-7" id="productCategoryTabs">
          <button type="button" onclick="filterProducts('all')" data-cat="all" class="product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-brand-primary text-white border-brand-primary">
            Tất cả
          </button>
          <button type="button" onclick="filterProducts('xay-nha')" data-cat="xay-nha" class="product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Thi công nhà trọn gói
          </button>
          <button type="button" onclick="filterProducts('son-chong-tham')" data-cat="son-chong-tham" class="product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Sơn &amp; Chống thấm
          </button>
          <button type="button" onclick="filterProducts('tran-nhua')" data-cat="tran-nhua" class="product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Trần nhựa Nano
          </button>
          <button type="button" onclick="filterProducts('san-op-nhua')" data-cat="san-op-nhua" class="product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Sàn nhựa &amp; Ốp lam sóng
          </button>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 3-4 cột máy tính, không nhãn dán -->
        <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render động bằng JavaScript từ dữ liệu 9 ảnh thực tế -->
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: CÁC DỰ ÁN TẠI ĐÀ NẴNG]                                -->
    <!-- Dùng đầy đủ 10 ảnh thực tế các dự án Đà Nẵng | 2 cột Mobile | Không nhãn dán -->
    <!-- ======================================================================= -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-soft border-t border-slate-200">
      <div class="pv-container">
        <div class="text-center mb-6 sm:mb-8">
          <h2 class="flatsome-title text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase text-brand-primary">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            Tổng hợp các công trình xây dựng nhà phố, biệt thự, sơn chống thấm và hoàn thiện trần sàn ốp nhựa thực tế của Phúc Vinh tại Đà Nẵng.
          </p>
        </div>

        <!-- Danh mục lọc Dự án Đà Nẵng: Chữ nhỏ gọn, từng mục không xuống dòng -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-7" id="projectCategoryTabs">
          <button type="button" onclick="filterProjects('all')" data-pcat="all" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-brand-primary text-white border-brand-primary">
            Tất cả dự án
          </button>
          <button type="button" onclick="filterProjects('nha-pho')" data-pcat="nha-pho" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Nhà phố – Biệt thự
          </button>
          <button type="button" onclick="filterProjects('hoan-thien')" data-pcat="hoan-thien" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Sơn &amp; Chống thấm
          </button>
          <button type="button" onclick="filterProjects('noi-that-nhua')" data-pcat="noi-that-nhua" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary">
            Trần, Sàn &amp; Ốp nhựa
          </button>
        </div>

        <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 5 cột trên máy tính lớn -->
        <div id="projectGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render động bằng JavaScript từ dữ liệu 10 ảnh dự án Đà Nẵng -->
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ]              -->
    <!-- ======================================================================= -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-primary text-white">
      <div class="pv-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <div class="lg:col-span-5">
            <p class="text-xs font-bold uppercase tracking-widest text-brand-accent mb-2">Miễn phí khảo sát &amp; lập dự toán</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase leading-snug mb-4">
              Đăng Ký Yêu Cầu Tư Vấn &amp; Nhận Báo Giá Nhanh
            </h2>
            <p class="text-sm text-slate-200 leading-relaxed mb-5">
              Quý khách cần báo giá xây nhà trọn gói, thi công sơn chống thấm hay lắp đặt trần nhựa Nano, sàn nhựa SPC, ốp lam sóng tại Đà Nẵng? Hãy để lại thông tin, kỹ sư của <strong>GPXD Phúc Vinh</strong> sẽ liên hệ tư vấn chi tiết trong 15 phút.
            </p>
            <div class="space-y-2.5 text-sm text-slate-100">
              <div class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-brand-accent text-white flex items-center justify-center text-xs font-bold shrink-0">✓</span>
                <span>Khảo sát hiện trạng và mang mẫu thực tế tận nơi miễn phí</span>
              </div>
              <div class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-brand-accent text-white flex items-center justify-center text-xs font-bold shrink-0">✓</span>
                <span>Bảng giá rõ ràng từng hạng mục, cam kết không phát sinh</span>
              </div>
              <div class="flex items-center gap-2.5">
                <span class="w-6 h-6 rounded-full bg-brand-accent text-white flex items-center justify-center text-xs font-bold shrink-0">✓</span>
                <span>Hotline trực tiếp: <a href="tel:0353826625" class="font-bold text-brand-accent underline">0353.826.625</a></span>
              </div>
            </div>
          </div>

          <div class="lg:col-span-7">
            <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                  <input type="text" id="qName" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary" />
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                  <input type="tel" id="qPhone" required placeholder="Ví dụ: 0353.826.625" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary" />
                </div>
                <div>
                  <label for="qService" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình / Hạng mục</label>
                  <select id="qService" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary">
                    <option value="Thiết kế & Thi công nhà trọn gói">Thiết kế &amp; Thi công nhà trọn gói</option>
                    <option value="Thi công sơn nước & Chống thấm">Thi công sơn nước &amp; Chống thấm</option>
                    <option value="Cung cấp & Thi công trần nhựa Nano">Cung cấp &amp; Thi công trần nhựa Nano</option>
                    <option value="Thi công sàn nhựa SPC & Ốp lam sóng">Thi công sàn nhựa SPC &amp; Ốp lam sóng</option>
                    <option value="Cải tạo, sửa chữa nhà ở">Cải tạo, sửa chữa nhà ở</option>
                  </select>
                </div>
                <div>
                  <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                  <select id="qBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary">
                    <option value="Chưa xác định">Chưa xác định / Cần tư vấn</option>
                    <option value="Dưới 100 triệu">Dưới 100 triệu (Sơn, chống thấm, trần sàn)</option>
                    <option value="100 - 500 triệu">100 triệu – 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="Trên 2 tỷ">Trên 2 tỷ</option>
                  </select>
                </div>
                <div class="sm:col-span-2">
                  <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Địa điểm &amp; Ghi chú yêu cầu</label>
                  <textarea id="qNote" rows="3" placeholder="Nhập diện tích (m2), khu vực thi công tại Đà Nẵng hoặc yêu cầu cụ thể..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary"></textarea>
                </div>
              </div>

              <div class="mt-4 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm uppercase tracking-wide transition-colors">
                  Gửi Yêu Cầu Báo Giá
                </button>
                <span class="text-xs text-slate-500">Thông tin của quý khách được bảo mật tuyệt đối.</span>
              </div>

              <!-- Thông báo gửi form thành công thay cho alert() -->
              <div id="quoteSuccessBox" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium">
                Cảm ơn quý khách đã gửi yêu cầu báo giá đến CÔNG TY TNHH GPXD PHÚC VINH. Chúng tôi sẽ gọi lại tư vấn qua số điện thoại bạn cung cấp trong thời gian sớm nhất!
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: TIN TỨC & BÀI VIẾT TRANG CHỦ]                         -->
    <!-- ======================================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
      <div class="pv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase text-brand-primary">
            Tin Tức &amp; Kinh Nghiệm Xây Dựng
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
            Chia sẻ kiến thức thực tế về thiết kế nhà phố, chống thấm mùa mưa Đà Nẵng và kinh nghiệm lựa chọn trần, sàn, ốp nhựa bền đẹp.
          </p>
        </div>

        <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render động 4 bài viết chuyên sâu -->
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ]                         -->
    <!-- ======================================================================= -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-brand-soft border-y border-slate-200">
      <div class="pv-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-title text-xl sm:text-2xl font-extrabold uppercase text-brand-primary">
            Đối Tác &amp; Thương Hiệu Đồng Hành
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm mt-3">
            GPXD Phúc Vinh cam kết sử dụng vật tư xây dựng, sơn chống thấm và tấm ốp nhựa chính hãng từ các thương hiệu hàng đầu.
          </p>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#00338D] tracking-tight">DULUX</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Sơn chính hãng</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#1E3A8A] tracking-tight">JOTUN</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#C8102E] tracking-tight">SIKA</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Chống thấm chuẩn</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#0F766E] tracking-tight">KOVA</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Sơn chống thấm</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#B45309] tracking-tight">KOSMOS</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Sàn &amp; Ốp nhựa</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#0E3A5D] tracking-tight">NGÂN HOA</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Trần Nano &amp; Phào</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#1D4ED8] tracking-tight">HÒA PHÁT</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-sm sm:text-base font-extrabold text-[#334155] tracking-tight">VĨNH TƯỜNG</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Khung xương trần</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================= -->
    <!-- [FLATSOME SECTION: GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ]        -->
    <!-- ======================================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white">
      <div class="pv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title text-xl sm:text-2xl lg:text-3xl font-extrabold uppercase text-brand-primary">
            Bản Đồ Chỉ Đường &amp; Fanpage Chính Thức
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm mt-3">
            Trụ sở: Thôn An Ngãi Đông, Phường Hòa Khánh, TP Đà Nẵng • Hotline/Zalo: 0353.826.625
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
          <!-- Cột Trái: Google Map hiển thị trực tiếp ngoài trang chủ -->
          <div class="lg:col-span-7 flex flex-col">
            <div class="bg-brand-soft rounded-xl border border-slate-200 overflow-hidden flex-1 flex flex-col">
              <div class="px-4 py-3 bg-brand-primary text-white flex items-center justify-between gap-2">
                <span class="text-xs sm:text-sm font-bold">Bản đồ Google Map – CÔNG TY TNHH GPXD PHÚC VINH</span>
                <a href="https://maps.google.com/?q=Th%C3%B4n+An+Ng%C3%A3i+%C4%90%C3%B4ng,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs text-brand-accent hover:underline font-semibold whitespace-nowrap">
                  Mở bản đồ lớn
                </a>
              </div>
              <div class="w-full h-[300px] sm:h-[360px] flex-1 bg-slate-100">
                <iframe
                  title="Bản đồ CÔNG TY TNHH GPXD PHÚC VINH - Thôn An Ngãi Đông, Phường Hòa Khánh, TP Đà Nẵng"
                  src="https://maps.google.com/maps?q=Th%C3%B4n%20An%20Ng%C3%A3i%20%C4%90%C3%B4ng,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                  class="w-full h-full border-0"
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                  allowfullscreen
                ></iframe>
              </div>
            </div>
          </div>

          <!-- Cột Phải: Fanpage Facebook hiển thị trực tiếp ngoài trang chủ -->
          <div class="lg:col-span-5 flex flex-col">
            <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex-1 flex flex-col">
              <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
                <div class="flex items-center gap-2">
                  <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.691v-3.622h3.13V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
                  <span class="text-xs sm:text-sm font-bold">Fanpage Facebook Chính Thức</span>
                </div>
                <span class="text-[11px] text-white/90">Cập nhật công trình mới</span>
              </div>

              <!-- Khối hiển thị Fanpage trực quan (luôn đẹp trên mọi trình duyệt & dễ thay URL Page Plugin trong Flatsome) -->
              <div class="relative h-36 sm:h-40 w-full overflow-hidden bg-brand-dark">
                <img
                  src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
                  alt="Ảnh bìa Fanpage CÔNG TY TNHH GPXD PHÚC VINH"
                  class="w-full h-full object-cover opacity-85"
                  onerror="handleImgError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'FANPAGE+GPXD+PHUC+VINH')"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                  <img
                    src="https://drive.google.com/thumbnail?id=1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl&sz=w300"
                    alt="Avatar Fanpage Phúc Vinh"
                    class="w-14 h-14 rounded-lg bg-white p-1 object-contain border-2 border-white shadow shrink-0"
                    onerror="handleImgError(this, '1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl', 'PV')"
                  />
                  <div class="text-white min-w-0">
                    <div class="font-bold text-sm sm:text-base leading-tight break-words">CÔNG TY TNHH GPXD PHÚC VINH</div>
                    <div class="text-[11px] text-slate-200 mt-0.5">Xây dựng trọn gói • Sơn chống thấm • Trần sàn ốp nhựa</div>
                  </div>
                </div>
              </div>

              <div class="p-4 flex-1 flex flex-col justify-between bg-slate-50">
                <div class="space-y-2 text-xs text-slate-700 mb-4">
                  <p class="leading-relaxed">
                    Theo dõi Fanpage <strong>GPXD Phúc Vinh</strong> để xem tiến độ thi công thực tế hàng ngày tại Đà Nẵng, bảng mẫu trần nhựa Nano – lam sóng mới nhất và nhận ưu đãi thi công trọn gói.
                  </p>
                  <div class="flex items-center gap-4 pt-1 text-[11px] text-slate-500 font-medium">
                    <span>Đà Nẵng, Việt Nam</span>
                    <span>•</span>
                    <span>Phản hồi nhanh 24/7</span>
                  </div>
                </div>

                <div class="grid grid-cols-2 gap-2.5">
                  <a
                    href="https://www.facebook.com/search/top?q=C%C3%94NG%20TY%20TNHH%20GPXD%20PH%C3%9AC%20VINH"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center justify-center gap-1.5 px-3 py-2.5 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white text-xs font-bold transition-colors"
                  >
                    <span>Theo dõi Fanpage</span>
                  </a>
                  <a
                    href="https://zalo.me/0353826625"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center justify-center gap-1.5 px-3 py-2.5 rounded-lg bg-white hover:bg-slate-100 text-brand-primary border border-slate-300 text-xs font-bold transition-colors"
                  >
                    <span>Nhắn tin Zalo</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ======================================================================= -->
  <!-- [FLATSOME FOOTER] Thông tin công ty, lĩnh vực và liên kết nhanh          -->
  <!-- ======================================================================= -->
  <footer class="bg-brand-dark text-slate-200 pt-12 pb-6 border-t-4 border-brand-accent">
    <div class="pv-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-2">
          <div class="flex items-center gap-3 mb-4">
            <img
              src="https://drive.google.com/thumbnail?id=1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl&sz=w300"
              alt="Logo GPXD Phúc Vinh"
              class="h-11 w-auto bg-white rounded-md p-1 object-contain"
              onerror="handleImgError(this, '1mUx7MFAkTlJUfYbwIAb2y-Qf8ufMoKYl', 'PHUC+VINH')"
            />
            <div>
              <h3 class="text-white font-extrabold text-sm sm:text-base uppercase">CÔNG TY TNHH GPXD PHÚC VINH</h3>
              <p class="text-xs text-brand-accent font-medium">Website: phucvinh.com</p>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><strong class="text-white">Trụ sở:</strong> Thôn An Ngãi Đông, Phường Hòa Khánh, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0353826625" class="text-brand-accent font-bold hover:underline">0353.826.625</a></li>
            <li><strong class="text-white">Mã số thuế:</strong> 0402106704</li>
            <li><strong class="text-white">Email:</strong> lienhe@phucvinh.com</li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div>
          <h4 class="text-white font-bold uppercase text-sm mb-3 pb-2 border-b border-white/15">Lĩnh Vực Hoạt Động</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#san-pham" onclick="filterProducts('xay-nha')" class="hover:text-brand-accent transition-colors">Thiết kế &amp; Thi công nhà trọn gói</a></li>
            <li><a href="#san-pham" onclick="filterProducts('son-chong-tham')" class="hover:text-brand-accent transition-colors">Thi công sơn nước nội ngoại thất</a></li>
            <li><a href="#san-pham" onclick="filterProducts('son-chong-tham')" class="hover:text-brand-accent transition-colors">Xử lý chống thấm chuyên nghiệp</a></li>
            <li><a href="#san-pham" onclick="filterProducts('tran-nhua')" class="hover:text-brand-accent transition-colors">Cung cấp &amp; Thi công trần nhựa Nano</a></li>
            <li><a href="#san-pham" onclick="filterProducts('san-op-nhua')" class="hover:text-brand-accent transition-colors">Thi công sàn nhựa SPC &amp; Ốp lam sóng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Hỗ trợ khách hàng -->
        <div>
          <h4 class="text-white font-bold uppercase text-sm mb-3 pb-2 border-b border-white/15">Liên Kết Nhanh</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-brand-accent transition-colors">Giới thiệu công ty</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-accent transition-colors">Các dự án tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-accent transition-colors">Đăng ký nhận báo giá</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-accent transition-colors">Tin tức &amp; Kinh nghiệm xây nhà</a></li>
            <li><a href="#lien-he" class="hover:text-brand-accent transition-colors">Bản đồ &amp; Fanpage Facebook</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <p>Copyright 2026 © CÔNG TY TNHH GPXD PHÚC VINH (phucvinh.com). All rights reserved.</p>
        <p>Chuyên Thiết Kế – Xây Dựng Trọn Gói – Sơn Chống Thấm – Trần Sàn Ốp Nhựa Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ======================================================================= -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Tương thích PC & Mobile) -->
  <!-- ======================================================================= -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/search/top?q=C%C3%94NG%20TY%20TNHH%20GPXD%20PH%C3%9AC%20VINH"
      target="_blank"
      rel="noopener noreferrer"
      title="Facebook GPXD Phúc Vinh"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
    >
      <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.691v-3.622h3.13V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0353826625"
      target="_blank"
      rel="noopener noreferrer"
      title="Chat Zalo 0353.826.625"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] text-[10px] font-extrabold flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline -->
    <a
      href="tel:0353826625"
      title="Gọi Hotline 0353.826.625"
      class="btn-hotline-pulse flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition-all"
    >
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0353.826.625</span>
    </a>
  </div>

  <!-- ======================================================================= -->
  <!-- MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT                          -->
  <!-- ======================================================================= -->
  <div id="detailModal" class="hidden fixed inset-0 z-50 bg-black/65 backdrop-blur-xs flex items-center justify-center p-3 sm:p-5" onclick="closeModalOnBackdrop(event)">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-primary pr-4">Chi tiết</h3>
        <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0" aria-label="Đóng">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div class="p-5">
        <div class="rounded-xl overflow-hidden mb-4 bg-slate-100">
          <img id="modalImage" src="" alt="" class="w-full max-h-[360px] object-cover" />
        </div>
        <p id="modalSubtitle" class="text-xs font-semibold text-brand-accent uppercase mb-2"></p>
        <div id="modalBody" class="text-sm text-slate-700 leading-relaxed space-y-2.5"></div>
        <div class="mt-5 pt-4 border-t border-slate-200 flex flex-wrap items-center gap-3">
          <button type="button" onclick="requestQuoteFromModal()" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm transition-colors">
            Nhận báo giá hạng mục này
          </button>
          <a href="tel:0353826625" class="px-5 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-bold text-xs sm:text-sm transition-colors">
            Gọi 0353.826.625
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- JAVASCRIPT QUẢN LÝ SLIDER, DỮ LIỆU ẢNH GOOGLE DRIVE, BỘ LỌC & MODAL     -->
  <!-- ======================================================================= -->
  <script>
    /**
     * Cơ chế dự phòng tải ảnh từ Google Drive:
     * Bước 1: drive.google.com/thumbnail?id=...&sz=w1000
     * Bước 2: lh3.googleusercontent.com/d/...=w1000
     * Bước 3: placehold.co dự phòng nếu file chưa mở quyền công khai
     */
    function getDriveImgUrl(id, size) {
      var sz = size || 900;
      return "https://drive.google.com/thumbnail?id=" + id + "&sz=w" + sz;
    }

    function handleImgError(imgEl, driveId, fallbackText) {
      try {
        var step = parseInt(imgEl.getAttribute("data-fallback-step") || "0", 10);
        if (step === 0 && driveId) {
          imgEl.setAttribute("data-fallback-step", "1");
          imgEl.src = "https://lh3.googleusercontent.com/d/" + driveId + "=w1000";
        } else if (step === 1) {
          imgEl.setAttribute("data-fallback-step", "2");
          imgEl.src = "https://placehold.co/800x600/0E3A5D/FFFFFF?text=" + encodeURIComponent(fallbackText || "GPXD PHUC VINH");
        }
      } catch (e) {
        console.error("Image fallback error:", e);
      }
    }

    /* -----------------------------------------------------------------------
     * 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG & SẢN PHẨM (Từ các link Google Drive)
     * ----------------------------------------------------------------------- */
    var productsData = [
      {
        id: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
        category: "xay-nha",
        categoryLabel: "Thi công nhà trọn gói",
        name: "Thi Công Xây Dựng Nhà Phố Trọn Gói (Phần Thô & Hoàn Thiện)",
        price: "Liên hệ báo giá",
        desc: "Dịch vụ xây nhà trọn gói chìa khóa trao tay từ xin phép xây dựng, thiết kế kiến trúc, thi công phần thô chuẩn kết cấu đến hoàn thiện nội ngoại thất đồng bộ."
      },
      {
        id: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
        category: "son-chong-tham",
        categoryLabel: "Sơn & Chống thấm",
        name: "Thi Công Sơn Nước Ngoại Thất & Nội Thất Chính Hãng",
        price: "Liên hệ báo giá",
        desc: "Thi công sơn bả matit, sơn lót kháng kiềm và sơn phủ bền màu Dulux, Jotun, Kova giúp tường nhà láng mịn, chống bám bụi và chịu thời tiết nắng mưa khắc nghiệt."
      },
      {
        id: "1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv",
        category: "son-chong-tham",
        categoryLabel: "Sơn & Chống thấm",
        name: "Chống Thấm Sân Thượng, Sàn Mái & Tường Đứng Triệt Để",
        price: "Liên hệ báo giá",
        desc: "Xử lý chống thấm chuyên sâu bằng vật liệu Sika, Kova gốc xi măng polyme và màng chống thấm đàn hồi, ngăn ngừa thấm dột, ố vàng hiệu quả mùa mưa Đà Nẵng."
      },
      {
        id: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
        category: "tran-nhua",
        categoryLabel: "Trần nhựa Nano",
        name: "Tấm Ốp Trần Nhựa Nano PVC Giả Gỗ Chống Ẩm Mốc",
        price: "Liên hệ báo giá",
        desc: "Tấm trần nhựa Nano nguyên sinh kết hợp bột đá, hệ hèm khóa âm dương khít mạch, kháng nước 100%, không mối mọt, cách nhiệt và dễ vệ sinh."
      },
      {
        id: "1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO",
        category: "san-op-nhua",
        categoryLabel: "Sàn nhựa & Ốp lam sóng",
        name: "Tấm Ốp Tường Lam Sóng Nhựa 3 Sóng & 5 Sóng Cao Cấp",
        price: "Liên hệ báo giá",
        desc: "Ốp vách tivi phòng khách, tường phòng ngủ và quầy lễ tân bằng thanh lam sóng giả gỗ sang trọng, thi công khô gọn gàng không bụi bẩn."
      },
      {
        id: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
        category: "san-op-nhua",
        categoryLabel: "Sàn nhựa & Ốp lam sóng",
        name: "Sàn Nhựa Hèm Khóa SPC Giả Gỗ Chịu Nước & Chống Trầy",
        price: "Liên hệ báo giá",
        desc: "Sàn nhựa hèm khóa SPC cốt đá nguyên sinh độ dày 4mm – 6mm, chống cong vênh, chống trơn trượt và kháng nước tuyệt đối cho nhà phố, căn hộ."
      },
      {
        id: "1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_",
        category: "tran-nhua",
        categoryLabel: "Trần nhựa Nano",
        name: "Thi Công Trần Nhựa Nano Giật Cấp Kết Hợp Đèn LED Hắt",
        price: "Liên hệ báo giá",
        desc: "Thiết kế và lắp đặt khung xương sắt hộp mạ kẽm chắc chắn kết hợp tấm nhựa Nano giật cấp, phào chỉ cổ trần tinh tế, nâng tầm không gian phòng khách."
      },
      {
        id: "1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT",
        category: "san-op-nhua",
        categoryLabel: "Sàn nhựa & Ốp lam sóng",
        name: "Tấm Nhựa Ốp Tường PVC Vân Đá Cẩm Thạch Sang Trọng",
        price: "Liên hệ báo giá",
        desc: "Tấm PVC vân đá phủ UV bóng gương sắc nét, trọng lượng nhẹ, chống ẩm tường hiệu quả và tiết kiệm chi phí hơn nhiều so với đá tự nhiên."
      },
      {
        id: "1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn",
        category: "xay-nha",
        categoryLabel: "Thi công nhà trọn gói",
        name: "Cải Tạo Sửa Chữa & Hoàn Thiện Nội Ngoại Thất Nhà Ở",
        price: "Liên hệ báo giá",
        desc: "Nhận cải tạo nâng tầng, thay mới hệ trần sàn ốp nhựa, sơn sửa chống thấm và làm mới không gian nhà ở cũ trọn gói nhanh gọn tại Đà Nẵng."
      }
    ];

    /* -----------------------------------------------------------------------
     * 2. DỮ LIỆU 10 DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG (Từ các link Google Drive)
     * ----------------------------------------------------------------------- */
    var projectsData = [
      {
        id: "157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT",
        category: "nha-pho",
        location: "Phường Hòa Khánh, TP Đà Nẵng",
        name: "Thi Công Nhà Phố 3 Tầng Trọn Gói – Hòa Khánh, Đà Nẵng",
        desc: "Công trình nhà phố hiện đại được GPXD Phúc Vinh thiết kế và thi công trọn gói từ móng đến hoàn thiện nội ngoại thất."
      },
      {
        id: "1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff",
        category: "nha-pho",
        location: "Khu Đô Thị Hòa Xuân, Đà Nẵng",
        name: "Hoàn Thiện Nhà Phố Hiện Đại – Hòa Xuân, Đà Nẵng",
        desc: "Hạng mục xây dựng hoàn thiện mặt tiền, sơn ngoại thất cao cấp và bố trí công năng tối ưu ánh sáng tự nhiên."
      },
      {
        id: "1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz",
        category: "noi-that-nhua",
        location: "Quận Liên Chiểu, TP Đà Nẵng",
        name: "Thi Công Trần Nhựa Nano & Lam Sóng – Liên Chiểu, Đà Nẵng",
        desc: "Ốp trần nhựa Nano giật cấp kết hợp lam sóng giả gỗ vách phòng khách, hoàn thiện sắc nét trong 2 ngày thi công."
      },
      {
        id: "1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k",
        category: "hoan-thien",
        location: "Quận Cẩm Lệ, TP Đà Nẵng",
        name: "Sơn Ngoại Thất & Chống Thấm Nhà Phố – Cẩm Lệ, Đà Nẵng",
        desc: "Xử lý chống thấm sân thượng, tường biên và sơn phủ ngoại thất 2 lớp bền màu chống rong rêu."
      },
      {
        id: "1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N",
        category: "nha-pho",
        location: "Quận Thanh Khê, TP Đà Nẵng",
        name: "Thiết Kế & Thi Công Nhà Ở 2 Tầng – Thanh Khê, Đà Nẵng",
        desc: "Giải pháp xây dựng nhà phố diện tích tối ưu, kết cấu vững chắc và bàn giao đúng tiến độ cam kết."
      },
      {
        id: "1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML",
        category: "noi-that-nhua",
        location: "Quận Hải Châu, TP Đà Nẵng",
        name: "Thi Công Sàn Nhựa SPC & Ốp Tường PVC – Hải Châu, Đà Nẵng",
        desc: "Lắp đặt sàn nhựa hèm khóa SPC vân gỗ sồi và tấm PVC vân đá chống ẩm cho không gian phòng khách trung tâm."
      },
      {
        id: "1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF",
        category: "nha-pho",
        location: "Khu vực Hòa Vang, TP Đà Nẵng",
        name: "Xây Dựng Nhà Trọn Gói Chìa Khóa Trao Tay – Hòa Vang, Đà Nẵng",
        desc: "Công trình nhà ở gia đình không gian thoáng đãng, vật tư chính hãng, bảo hành kết cấu dài hạn."
      },
      {
        id: "1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A",
        category: "hoan-thien",
        location: "Quận Sơn Trà, TP Đà Nẵng",
        name: "Cải Tạo, Sơn Sửa & Chống Thấm Căn Hộ – Sơn Trà, Đà Nẵng",
        desc: "Chống thấm khu vực ban công ven biển và sơn hoàn thiện chống muối mặn cho nhà ở khu vực Sơn Trà."
      },
      {
        id: "1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80",
        category: "noi-that-nhua",
        location: "Quận Ngũ Hành Sơn, TP Đà Nẵng",
        name: "Thi Công Ốp Trần & Vách Lam Sóng – Ngũ Hành Sơn, Đà Nẵng",
        desc: "Trang trí trần nhựa Nano phối lam sóng vân gỗ ấm cúng, chống ẩm tuyệt đối cho biệt thự phố."
      },
      {
        id: "1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4",
        category: "hoan-thien",
        location: "Khu Nam Việt Á, TP Đà Nẵng",
        name: "Hoàn Thiện Nội Ngoại Thất Nhà Phố – Nam Việt Á, Đà Nẵng",
        desc: "Thi công đồng bộ hạng mục sơn nước, chống thấm và ốp nhựa trang trí phòng khách – cầu thang."
      }
    ];

    /* -----------------------------------------------------------------------
     * 3. DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ
     * ----------------------------------------------------------------------- */
    var newsData = [
      {
        id: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
        date: "Kinh nghiệm xây nhà",
        title: "Kinh nghiệm xây nhà trọn gói tại Đà Nẵng giúp tối ưu chi phí và tránh phát sinh",
        summary: "Những lưu ý quan trọng về hồ sơ thiết kế, lựa chọn vật tư phần thô và hợp đồng thi công minh bạch trước khi khởi công.",
        content: "Để quá trình xây nhà trọn gói tại Đà Nẵng diễn ra thuận lợi, chủ đầu tư nên chuẩn bị rõ nhu cầu công năng, khảo sát đơn giá vật tư chính hãng và ký kết hợp đồng chi tiết từng hạng mục. CÔNG TY TNHH GPXD PHÚC VINH luôn hỗ trợ lập bảng dự toán rõ ràng ngay từ đầu giúp gia chủ kiểm soát ngân sách tối ưu."
      },
      {
        id: "1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv",
        date: "Kỹ thuật chống thấm",
        title: "Quy trình chống thấm sân thượng và tường đứng đạt chuẩn cho mùa mưa miền Trung",
        summary: "Hướng dẫn xử lý bề mặt bê tông, cổ ống thoát nước và thi công lớp chống thấm đàn hồi giúp công trình bền vững nhiều năm.",
        content: "Khí hậu mưa bão tại Đà Nẵng dễ khiến sàn mái, sân thượng và tường hướng Tây bị thấm dột nếu xử lý không đúng kỹ thuật. Quy trình chuẩn gồm vệ sinh mài sạch bề mặt, trám keo PU các vết nứt, quét lót tạo bám dính và phủ tối thiểu 2–3 lớp chống thấm chuyên dụng kết hợp ngâm thử nước 24 giờ."
      },
      {
        id: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
        date: "Vật liệu trần – ốp nhựa",
        title: "So sánh trần nhựa Nano với trần thạch cao: Nên chọn loại nào cho nhà phố?",
        summary: "Phân tích ưu nhược điểm về khả năng kháng nước, chống ẩm mốc, tốc độ thi công và độ bền của trần nhựa Nano giả gỗ.",
        content: "Trần nhựa Nano PVC ngày càng được nhiều gia đình tại Đà Nẵng ưa chuộng nhờ khả năng kháng nước 100%, không bị ố vàng hay võng trần khi mái tôn gặp ẩm, thi công nhanh trong 1–2 ngày và rất ít bụi bẩn. Khi kết hợp thêm đèn LED âm trần và phào chỉ đồng màu, không gian trở nên vô cùng hiện đại và sang trọng."
      },
      {
        id: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
        date: "Hoàn thiện nội thất",
        title: "Hướng dẫn chọn sàn nhựa hèm khóa SPC và tấm ốp lam sóng phù hợp phòng khách",
        summary: "Cách phối màu sàn nhựa giả gỗ cùng vách lam sóng PVC giúp không gian phòng khách rộng rãi, ấm cúng và dễ vệ sinh.",
        content: "Sàn nhựa hèm khóa SPC cốt đá có ưu điểm chịu nước tuyệt đối, không mối mọt và đi êm chân. Đối với phòng khách nhà phố diện tích vừa phải, gia chủ nên chọn sàn vân gỗ sồi sáng phối cùng vách tivi ốp PVC vân đá và lam sóng tông ấm để tạo điểm nhấn hài hòa, hiện đại."
      }
    ];

    /* -----------------------------------------------------------------------
     * RENDER SẢN PHẨM (2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN, KHÔNG CẮT CHỮ)
     * ----------------------------------------------------------------------- */
    function renderProducts(filterCat) {
      var grid = document.getElementById("productGrid");
      if (!grid) return;

      var list = filterCat === "all"
        ? productsData
        : productsData.filter(function(item) { return item.category === filterCat; });

      var html = list.map(function(item, idx) {
        var originalIdx = productsData.indexOf(item);
        return (
          '<article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md hover:border-brand-accent transition-all flex flex-col">' +
            '<div class="w-full aspect-[4/3] overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal(' + originalIdx + ')">' +
              '<img src="' + getDriveImgUrl(item.id, 800) + '" alt="' + item.name + '" loading="lazy" class="w-full h-full object-cover hover:scale-105 transition-transform duration-300" onerror="handleImgError(this, \'' + item.id + '\', \'SAN+PHAM+PHUC+VINH\')" />' +
            '</div>' +
            '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<div>' +
                '<h3 onclick="openProductModal(' + originalIdx + ')" class="text-xs sm:text-sm font-bold text-brand-primary hover:text-brand-accent cursor-pointer leading-snug break-words mb-1.5">' +
                  item.name +
                '</h3>' +
                '<p class="text-[11px] sm:text-xs text-slate-500 leading-relaxed hidden sm:block mb-2.5">' +
                  item.desc +
                '</p>' +
              '</div>' +
              '<div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-2">' +
                '<span class="text-xs sm:text-sm font-extrabold text-brand-accent">' + item.price + '</span>' +
                '<button type="button" onclick="openProductModal(' + originalIdx + ')" class="text-[11px] sm:text-xs font-semibold text-brand-primary hover:underline whitespace-nowrap">Chi tiết</button>' +
              '</div>' +
            '</div>' +
          '</article>'
        );
      }).join("");

      grid.innerHTML = html;
    }

    function filterProducts(cat) {
      renderProducts(cat);
      var tabs = document.querySelectorAll(".product-tab");
      tabs.forEach(function(btn) {
        if (btn.getAttribute("data-cat") === cat) {
          btn.className = "product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-brand-primary text-white border-brand-primary";
        } else {
          btn.className = "product-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary";
        }
      });
    }

    /* -----------------------------------------------------------------------
     * RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN)
     * ----------------------------------------------------------------------- */
    function renderProjects(filterCat) {
      var grid = document.getElementById("projectGrid");
      if (!grid) return;

      var list = filterCat === "all"
        ? projectsData
        : projectsData.filter(function(item) { return item.category === filterCat; });

      var html = list.map(function(item) {
        var originalIdx = projectsData.indexOf(item);
        return (
          '<article onclick="openProjectModal(' + originalIdx + ')" class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md hover:border-brand-accent transition-all cursor-pointer flex flex-col">' +
            '<div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">' +
              '<img src="' + getDriveImgUrl(item.id, 800) + '" alt="' + item.name + '" loading="lazy" class="w-full h-full object-cover hover:scale-105 transition-transform duration-300" onerror="handleImgError(this, \'' + item.id + '\', \'DU+AN+DA+NANG\')" />' +
            '</div>' +
            '<div class="p-3 flex-1 flex flex-col justify-between">' +
              '<h3 class="text-xs sm:text-[13px] font-bold text-brand-primary leading-snug break-words mb-1.5">' +
                item.name +
              '</h3>' +
              '<p class="text-[11px] text-slate-500 font-medium break-words">' + item.location + '</p>' +
            '</div>' +
          '</article>'
        );
      }).join("");

      grid.innerHTML = html;
    }

    function filterProjects(cat) {
      renderProjects(cat);
      var tabs = document.querySelectorAll(".project-tab");
      tabs.forEach(function(btn) {
        if (btn.getAttribute("data-pcat") === cat) {
          btn.className = "project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-brand-primary text-white border-brand-primary";
        } else {
          btn.className = "project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[12px] sm:text-[13px] font-semibold border transition-colors bg-white text-slate-700 border-slate-300 hover:border-brand-primary hover:text-brand-primary";
        }
      });
    }

    /* -----------------------------------------------------------------------
     * RENDER TIN TỨC TRANG CHỦ
     * ----------------------------------------------------------------------- */
    function renderNews() {
      var grid = document.getElementById("newsGrid");
      if (!grid) return;

      grid.innerHTML = newsData.map(function(post, idx) {
        return (
          '<article onclick="openNewsModal(' + idx + ')" class="bg-white rounded-xl border border-slate-200 overflow-hidden hover:shadow-md hover:border-brand-accent transition-all cursor-pointer flex flex-col">' +
            '<div class="w-full aspect-[16/10] overflow-hidden bg-slate-100">' +
              '<img src="' + getDriveImgUrl(post.id, 700) + '" alt="' + post.title + '" loading="lazy" class="w-full h-full object-cover hover:scale-105 transition-transform duration-300" onerror="handleImgError(this, \'' + post.id + '\', \'TIN+TUC+PHUC+VINH\')" />' +
            '</div>' +
            '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<div>' +
                '<div class="text-[11px] font-semibold text-brand-accent mb-1">' + post.date + '</div>' +
                '<h3 class="text-xs sm:text-sm font-bold text-brand-primary leading-snug break-words mb-2">' + post.title + '</h3>' +
                '<p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">' + post.summary + '</p>' +
              '</div>' +
              '<div class="mt-2.5 text-xs font-semibold text-brand-primary hover:text-brand-accent">Đọc bài viết →</div>' +
            '</div>' +
          '</article>'
        );
      }).join("");
    }

    /* -----------------------------------------------------------------------
     * SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
     * ----------------------------------------------------------------------- */
    var currentSlide = 0;
    var totalSlides = 2;
    var sliderTimer = null;

    function updateSliderUI() {
      var track = document.getElementById("heroTrack");
      if (!track) return;
      track.style.transform = "translateX(-" + (currentSlide * 50) + "%)";

      for (var i = 0; i < totalSlides; i++) {
        var dot = document.getElementById("dot-" + i);
        if (!dot) continue;
        if (i === currentSlide) {
          dot.className = "w-6 h-2 rounded-full bg-brand-accent transition-all";
        } else {
          dot.className = "w-2.5 h-2 rounded-full bg-white/60 transition-all";
        }
      }
    }

    function moveSlide(step) {
      currentSlide = (currentSlide + step + totalSlides) % totalSlides;
      updateSliderUI();
      resetSliderTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSliderUI();
      resetSliderTimer();
    }

    function resetSliderTimer() {
      if (sliderTimer) clearInterval(sliderTimer);
      sliderTimer = setInterval(function() {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSliderUI();
      }, 5000);
    }

    /* -----------------------------------------------------------------------
     * MODAL CHI TIẾT & TÍCH HỢP ĐIỀN FORM BÁO GIÁ
     * ----------------------------------------------------------------------- */
    var activeModalItemTitle = "";

    function showModal(title, subtitle, imgId, bodyText) {
      activeModalItemTitle = title;
      document.getElementById("modalTitle").textContent = title;
      document.getElementById("modalSubtitle").textContent = subtitle;
      var imgEl = document.getElementById("modalImage");
      imgEl.removeAttribute("data-fallback-step");
      imgEl.src = getDriveImgUrl(imgId, 1000);
      imgEl.alt = title;
      imgEl.onerror = function() { handleImgError(imgEl, imgId, "GPXD PHUC VINH"); };
      document.getElementById("modalBody").innerHTML = "<p>" + bodyText + "</p>";
      document.getElementById("detailModal").classList.remove("hidden");
      document.body.style.overflow = "hidden";
    }

    function openProductModal(idx) {
      var item = productsData[idx];
      if (!item) return;
      showModal(item.name, item.categoryLabel + " • " + item.price, item.id, item.desc + " Liên hệ CÔNG TY TNHH GPXD PHÚC VINH qua số 0353.826.625 để nhận bảng mẫu thực tế và báo giá thi công trọn gói tốt nhất tại Đà Nẵng.");
    }

    function openProjectModal(idx) {
      var item = projectsData[idx];
      if (!item) return;
      showModal(item.name, "Địa điểm: " + item.location, item.id, item.desc + " Công trình được đội ngũ kỹ sư GPXD Phúc Vinh trực tiếp giám sát chất lượng và tiến độ.");
    }

    function openNewsModal(idx) {
      var post = newsData[idx];
      if (!post) return;
      showModal(post.title, post.date + " • GPXD Phúc Vinh", post.id, post.content);
    }

    function closeDetailModal() {
      document.getElementById("detailModal").classList.add("hidden");
      document.body.style.overflow = "";
    }

    function closeModalOnBackdrop(event) {
      if (event.target && event.target.id === "detailModal") {
        closeDetailModal();
      }
    }

    function requestQuoteFromModal() {
      closeDetailModal();
      var noteEl = document.getElementById("qNote");
      if (noteEl && activeModalItemTitle) {
        noteEl.value = "Tôi muốn tư vấn và nhận báo giá cho mục: " + activeModalItemTitle;
      }
      var quoteSection = document.getElementById("bao-gia");
      if (quoteSection) {
        quoteSection.scrollIntoView({ behavior: "smooth" });
      }
    }

    /* -----------------------------------------------------------------------
     * XỬ LÝ FORM BÁO GIÁ & MENU MOBILE
     * ----------------------------------------------------------------------- */
    function submitQuoteForm(event) {
      event.preventDefault();
      var successBox = document.getElementById("quoteSuccessBox");
      if (successBox) {
        successBox.classList.remove("hidden");
      }
      event.target.reset();
    }

    function toggleMobileMenu() {
      var drawer = document.getElementById("mobileMenuDrawer");
      if (drawer) {
        drawer.classList.toggle("hidden");
      }
    }

    function closeMobileMenu() {
      var drawer = document.getElementById("mobileMenuDrawer");
      if (drawer) {
        drawer.classList.add("hidden");
      }
    }

    /* Khởi chạy toàn bộ dữ liệu khi tải trang */
    document.addEventListener("DOMContentLoaded", function() {
      renderProducts("all");
      renderProjects("all");
      renderNews();
      updateSliderUI();
      resetSliderTimer();
    });
  </script>
</body>
</html>
