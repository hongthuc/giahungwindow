<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Công Ty TNHH Sản Xuất TM&DV Gia Hưng Window | Cửa Nhôm Xingfa Đà Nẵng</title>
  <meta name="description" content="Công ty TNHH Sản Xuất TM&DV Gia Hưng Window - Chuyên thiết kế, sản xuất, thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Hotline: 0965.656.469" />

  <!-- Meta Open Graph / Thumbnail Logo khi chia sẻ đường link website -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://giahungwindow.com/" />
  <meta property="og:site_name" content="Gia Hưng Window" />
  <meta property="og:title" content="Công Ty TNHH Sản Xuất TM&DV Gia Hưng Window - Cửa Nhôm Xingfa Đà Nẵng" />
  <meta property="og:description" content="Chuyên thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa tự động, Cầu thang kính, Kính ốp bếp, Phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0965.656.469" />
  <meta property="og:image" content="https://giahungwindow.com/assets/logo-giahungwindow-thumbnail.png" />
  <meta property="og:image:alt" content="Logo Công ty TNHH Sản Xuất TM&DV Gia Hưng Window" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Gia Hưng Window - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng" />
  <meta name="twitter:description" content="Địa chỉ: Thôn Phú Thượng, Hòa Vang, Đà Nẵng. Hotline/Zalo: 0965.656.469" />
  <meta name="twitter:image" content="https://giahungwindow.com/assets/logo-giahungwindow-thumbnail.png" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS -->
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
              navy: '#0E3A66',
              dark: '#092847',
              blue: '#16528E',
              gold: '#D98A1A',
              goldHover: '#B87212',
              light: '#F4F7FA',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Đảm bảo chống tràn viền ngang và không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      scroll-behavior: smooth;
      background-color: #ffffff;
      color: #1e293b;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% màn hình, trên điện thoại gọn gàng 100% */
    .container-95 {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề Section phong cách Flatsome */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 1.5rem;
    }

    .flatsome-section-title::before,
    .flatsome-section-title::after {
      content: "";
      flex: 1;
      height: 2px;
      background: linear-gradient(90deg, rgba(14,58,102,0.08), rgba(14,58,102,0.35), rgba(14,58,102,0.08));
      max-width: 240px;
    }

    /* Dropdown Menu Desktop chuẩn Flatsome */
    .nav-dropdown-wrap {
      position: relative;
    }

    .nav-dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 225px;
      z-index: 60;
    }

    .nav-dropdown-wrap:hover .nav-dropdown-menu,
    .nav-dropdown-wrap:focus-within .nav-dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Banner Slider 2 slide đồng nhất chiều cao bằng CSS Grid chồng lớp */
    .hero-slider-grid {
      display: grid;
      grid-template-columns: 1fr;
    }

    .hero-slide-item {
      grid-column: 1 / 2;
      grid-row: 1 / 2;
      transition: opacity 0.65s ease, visibility 0.65s ease;
    }

    .hero-slide-active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    .hero-slide-hidden {
      opacity: 0;
      visibility: hidden;
      z-index: 1;
      pointer-events: none;
    }

    /* Hiệu ứng rung nhẹ cho nút liên hệ nổi */
    @keyframes pulseRing {
      0% { transform: scale(1); opacity: 0.7; }
      70% { transform: scale(1.35); opacity: 0; }
      100% { transform: scale(1.35); opacity: 0; }
    }

    .fab-pulse::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background-color: inherit;
      z-index: -1;
      animation: pulseRing 2.2s infinite;
    }

    /* Hiệu ứng hover ảnh Flatsome */
    .img-zoom {
      transition: transform 0.4s ease;
    }

    .group:hover .img-zoom {
      transform: scale(1.05);
    }
  </style>
</head>

<body class="bg-white text-slate-800 antialiased">

  <!-- ==================== 1. TOP BAR (UX Builder: Header Top Bar) ==================== -->
  <div class="bg-brand-dark text-slate-100 text-xs py-2 border-b border-white/10">
    <div class="container-95 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-gold"></i>
          <span>Thôn Phú Thượng, Hòa Vang, Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-regular fa-clock text-brand-gold"></i>
          <span>Tư vấn & Thi công 24/7</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <a href="tel:0965656469" class="inline-flex items-center gap-1.5 hover:text-brand-gold transition font-medium">
          <i class="fa-solid fa-phone text-brand-gold"></i>
          <span>0965.656.469</span>
        </a>
        <span class="text-white/30">|</span>
        <a href="https://www.facebook.com/profile.php?id=61575187401153" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition" aria-label="Fanpage Facebook Gia Hưng Window">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
        <a href="https://zalo.me/0965656469" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition font-bold" aria-label="Zalo Gia Hưng Window">
          Zalo
        </a>
      </div>
    </div>
  </div>

  <!-- ==================== 2. HEADER & NAVIGATION (UX Builder: Header Main) ==================== -->
  <!-- Lưu ý: Không đặt nút Gọi Ngay trên Header để tránh tràn viền; Logo nhỏ gọn; Tên danh mục viết liền không xuống dòng -->
  <header class="sticky top-0 z-50 bg-white shadow-sm border-b border-slate-200">
    <div class="container-95 py-2.5 flex items-center justify-between gap-2">

      <!-- Logo Công ty Gia Hưng Window (Thiết kế SVG gọn nhỏ chuyên nghiệp) -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Gia Hưng Window - Trang chủ">
        <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Gia Hưng Window">
          <!-- Khung kiến trúc cửa nhôm cao cấp -->
          <rect x="4" y="4" width="56" height="56" rx="12" fill="#0E3A66"/>
          <rect x="9" y="9" width="46" height="46" rx="8" stroke="#D98A1A" stroke-width="2.5"/>
          <!-- Cánh cửa 3D mở góc kiến trúc -->
          <path d="M17 17H31V47H17V17Z" fill="#16528E" stroke="#FFFFFF" stroke-width="2"/>
          <path d="M31 17L47 13V51L31 47V17Z" fill="#D98A1A"/>
          <!-- Chi tiết đố kính chữ H/G cách điệu -->
          <line x1="24" y1="17" x2="24" y2="47" stroke="#FFFFFF" stroke-width="1.5" stroke-opacity="0.7"/>
          <line x1="17" y1="32" x2="31" y2="32" stroke="#FFFFFF" stroke-width="1.5" stroke-opacity="0.7"/>
          <circle cx="35" cy="32" r="2" fill="#0E3A66"/>
        </svg>
        <div class="leading-tight">
          <div class="text-sm lg:text-[15px] font-extrabold tracking-tight text-brand-navy whitespace-nowrap">
            GIA HƯNG <span class="text-brand-gold">WINDOW</span>
          </div>
          <div class="text-[9px] lg:text-[10px] font-medium text-slate-500 tracking-wide uppercase whitespace-nowrap">
            Cửa Nhôm Kính Cao Cấp
          </div>
        </div>
      </a>

      <!-- Menu Chính Desktop: Chữ nhỏ gọn, viết liền trên 1 hàng, không ngắt dòng bên trong tên danh mục -->
      <nav class="hidden lg:flex items-center justify-end flex-1" aria-label="Danh mục chính">
        <ul class="flex flex-wrap items-center justify-end gap-x-0.5 xl:gap-x-1.5 gap-y-1">
          <li>
            <a href="#trang-chu" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-brand-navy hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Trang chủ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Giới thiệu
            </a>
          </li>

          <!-- Dropdown: Cửa nhôm Xingfa -->
          <li class="nav-dropdown-wrap">
            <a href="#san-pham-xingfa" onclick="filterProducts('xingfa')" class="flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              <span>Cửa nhôm xingfa</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <ul class="nav-dropdown-menu bg-white rounded-lg shadow-xl border border-slate-100 py-1.5">
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-1')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-2')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-3')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-4')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-5')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li>
            <a href="#danh-muc-san-pham" onclick="filterCategoryScroll('kinh-cuong-luc')" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Dropdown: Sản phẩm -->
          <li class="nav-dropdown-wrap">
            <a href="#danh-muc-san-pham" class="flex items-center gap-1 px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              <span>Sản phẩm</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <ul class="nav-dropdown-menu bg-white rounded-lg shadow-xl border border-slate-100 py-1.5">
              <li><a href="#san-pham-xingfa" onclick="filterProducts('xingfa')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('nhua-loi-thep')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Phòng tắm kính</a></li>
            </ul>
          </li>

          <li>
            <a href="#cong-trinh" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Công trình
            </a>
          </li>
          <li>
            <a href="#bao-gia" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Báo giá
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Tin tức
            </a>
          </li>
          <li>
            <a href="#lien-he" class="block px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition whitespace-nowrap rounded-md hover:bg-slate-50">
              Liên hệ
            </a>
          </li>
        </ul>
      </nav>

      <!-- Nút mở Menu Mobile -->
      <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-brand-light transition" aria-label="Mở menu danh mục">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Thanh Menu Danh Mục Mobile trượt xuống đẹp, rõ ràng -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg max-h-[80vh] overflow-y-auto">
      <div class="px-4 py-3 space-y-1">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-brand-navy bg-brand-light">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-light">Giới thiệu</a>

        <!-- Accordion: Cửa nhôm xingfa -->
        <div class="rounded-lg border border-slate-100 overflow-hidden">
          <button type="button" onclick="toggleMobileSub('subXingfa', 'iconXingfa')" class="w-full flex items-center justify-between px-3 py-2.5 text-sm font-semibold text-slate-700 hover:bg-brand-light">
            <span>Cửa nhôm xingfa</span>
            <i id="iconXingfa" class="fa-solid fa-chevron-down text-xs text-slate-500 transition-transform"></i>
          </button>
          <div id="subXingfa" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 border-t border-slate-100">
            <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-1')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 1 cánh</a>
            <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-2')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 2 cánh</a>
            <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-3')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 3 cánh</a>
            <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-4')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 4 cánh</a>
            <a href="#san-pham-xingfa" onclick="closeMobileMenu(); highlightProduct('xingfa-5')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa 5 cánh</a>
          </div>
        </div>

        <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-light">Cửa kính cường lực</a>

        <!-- Accordion: Sản phẩm -->
        <div class="rounded-lg border border-slate-100 overflow-hidden">
          <button type="button" onclick="toggleMobileSub('subSanPham', 'iconSanPham')" class="w-full flex items-center justify-between px-3 py-2.5 text-sm font-semibold text-slate-700 hover:bg-brand-light">
            <span>Sản phẩm</span>
            <i id="iconSanPham" class="fa-solid fa-chevron-down text-xs text-slate-500 transition-transform"></i>
          </button>
          <div id="subSanPham" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 border-t border-slate-100">
            <a href="#san-pham-xingfa" onclick="closeMobileMenu()" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhôm xingfa</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); openCategoryDetail('nhua-loi-thep')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa nhựa lõi thép</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); openCategoryDetail('cua-tu-dong')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cửa kính tự động</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); openCategoryDetail('cau-thang-kinh')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Cầu thang kính</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); openCategoryDetail('kinh-op-bep')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Kính ốp bếp</a>
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu(); openCategoryDetail('phong-tam-kinh')" class="block py-2 pl-3 text-xs font-medium text-slate-600 hover:text-brand-navy">+ Phòng tắm kính</a>
          </div>
        </div>

        <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-light">Công trình</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-light">Báo giá</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-light">Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg text-sm font-semibold text-slate-700 hover:bg-brand-light">Liên hệ</a>
      </div>
    </div>
  </header>

  <!-- ==================== 3. HERO BANNER SLIDER - 2 ẢNH TỰ TRƯỢT BẰNG NHAU (UX Builder: Slider) ==================== -->
  <!-- Đảm bảo: 2 banner kích thước bằng nhau 100%, chữ và hình nằm trọn trong banner, lề xa viền, không mất chữ trên mọi màn hình -->
  <section id="trang-chu" class="py-3 lg:py-4 bg-brand-light">
    <div class="container-95">
      <div class="relative rounded-2xl overflow-hidden shadow-md bg-brand-dark">
        <div id="heroSlider" class="hero-slider-grid">

          <!-- BANNER 1 -->
          <div class="hero-slide-item hero-slide-active relative bg-gradient-to-br from-[#092847] via-[#0E3A66] to-[#16528E] text-white">
            <div class="w-full h-full px-8 sm:px-14 md:px-20 lg:px-24 py-9 sm:py-12 md:py-16 flex flex-col md:flex-row items-center justify-between gap-6 md:gap-10">
              <!-- Nội dung chữ cách xa viền banner -->
              <div class="w-full md:w-3/5 text-center md:text-left space-y-3 sm:space-y-4">
                <p class="text-xs sm:text-sm font-semibold tracking-wider uppercase text-amber-300">
                  CÔNG TY TNHH SẢN XUẤT TM&amp;DV GIA HƯNG WINDOW
                </p>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  THI CÔNG CỬA NHÔM XINGFA CHÍNH HÃNG TẠI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl mx-auto md:mx-0">
                  Sản xuất trực tiếp tại xưởng Hòa Vang – Nhôm Xingfa nhập khẩu tem đỏ, phụ kiện Kinlong đồng bộ, cách âm cách nhiệt vượt trội, bảo hành dài hạn.
                </p>
                <div class="pt-2 flex flex-wrap items-center justify-center md:justify-start gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs sm:text-sm font-bold shadow transition">
                    Nhận Báo Giá Ngay
                  </a>
                  <a href="#san-pham-xingfa" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                    Xem Sản Phẩm
                  </a>
                </div>
              </div>
              <!-- Hình ảnh thực tế nằm gọn bên trong banner -->
              <div class="w-full max-w-[260px] sm:max-w-[320px] md:w-2/5 md:max-w-none">
                <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-lg aspect-[4/3] bg-white/10">
                  <img
                    src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w1000"
                    data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                    alt="Cửa đi mở quay 4 cánh nhôm Xingfa Gia Hưng Window"
                    class="w-full h-full object-cover drive-img"
                  />
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="hero-slide-item hero-slide-hidden relative bg-gradient-to-br from-[#0B2E52] via-[#134678] to-[#0E3A66] text-white">
            <div class="w-full h-full px-8 sm:px-14 md:px-20 lg:px-24 py-9 sm:py-12 md:py-16 flex flex-col md:flex-row items-center justify-between gap-6 md:gap-10">
              <!-- Nội dung chữ cách xa viền banner -->
              <div class="w-full md:w-3/5 text-center md:text-left space-y-3 sm:space-y-4">
                <p class="text-xs sm:text-sm font-semibold tracking-wider uppercase text-amber-300">
                  GIẢI PHÁP CỬA ĐẸP CHO NHÀ PHỐ – BIỆT THỰ – KHÁCH SẠN
                </p>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  CỬA KÍNH CƯỜNG LỰC &amp; HẠNG MỤC NHÔM KÍNH TRỌN GÓI
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl mx-auto md:mx-0">
                  Thi công chuyên nghiệp Cửa kính tự động, Cầu thang kính, Phòng tắm kính, Kính ốp bếp tại Đà Nẵng và khu vực Miền Trung. Khảo sát tận nơi miễn phí.
                </p>
                <div class="pt-2 flex flex-wrap items-center justify-center md:justify-start gap-3">
                  <a href="#cong-trinh" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-xs sm:text-sm font-bold shadow transition">
                    Xem Công Trình Thực Tế
                  </a>
                  <a href="tel:0965656469" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                    Tư Vấn: 0965.656.469
                  </a>
                </div>
              </div>
              <!-- Hình ảnh thực tế nằm gọn bên trong banner -->
              <div class="w-full max-w-[260px] sm:max-w-[320px] md:w-2/5 md:max-w-none">
                <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-lg aspect-[4/3] bg-white/10">
                  <img
                    src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
                    data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                    alt="Dự án thi công nhôm kính cao cấp Gia Hưng Window Đà Nẵng"
                    class="w-full h-full object-cover drive-img"
                  />
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút chuyển slide trái / phải đặt sát mép ngoài vùng chữ -->
        <button type="button" onclick="prevSlide()" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition" aria-label="Banner trước">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button type="button" onclick="nextSlide()" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition" aria-label="Banner tiếp theo">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Dấu chấm chỉ báo 2 slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-brand-gold transition-all" aria-label="Chuyển tới banner 1"></button>
          <button type="button" onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/50 transition-all" aria-label="Chuyển tới banner 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 4. DANH MỤC SẢN PHẨM NỔI BẬT (UX Builder: Section Categories) ==================== -->
  <section id="danh-muc-san-pham" class="py-8 lg:py-12 bg-white">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center whitespace-nowrap">
          Danh Mục Sản Phẩm
        </h2>
      </div>

      <!-- 2 cột trên điện thoại, 3 cột trên tablet, 6 cột trên máy tính -->
      <div id="categoryGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- Dữ liệu danh mục render từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 5. SẢN PHẨM CỬA NHÔM XINGFA & GIÁ BÁN (UX Builder: Section Products) ==================== -->
  <!-- Đảm bảo: 2 cột trên điện thoại, giá & giảm giá % góc trên bên trái, tên sản phẩm không bị tràn hay thiếu chữ -->
  <section id="san-pham-xingfa" class="py-8 lg:py-12 bg-brand-light">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Sản Phẩm Cửa Nhôm Xingfa
        </h2>
      </div>

      <!-- Bộ lọc danh mục con gọn nhẹ -->
      <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
        <button type="button" onclick="filterProducts('all')" data-filter="all" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-navy text-white transition whitespace-nowrap">
          Tất cả sản phẩm
        </button>
        <button type="button" onclick="filterProducts('mo-quay')" data-filter="mo-quay" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition whitespace-nowrap">
          Cửa đi mở quay
        </button>
        <button type="button" onclick="filterProducts('xep-truot')" data-filter="xep-truot" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition whitespace-nowrap">
          Cửa đi xếp trượt
        </button>
        <button type="button" onclick="filterProducts('cua-so')" data-filter="cua-so" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition whitespace-nowrap">
          Cửa sổ mở hất
        </button>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên mobile, 3 cột trên desktop -->
      <div id="productGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-2.5 sm:gap-5">
        <!-- Dữ liệu sản phẩm render từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 6. GIỚI THIỆU CÔNG TY & THÔNG SỐ (UX Builder: Section About) ==================== -->
  <section id="gioi-thieu" class="py-8 lg:py-12 bg-white">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Về Gia Hưng Window
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
        <!-- Cột nội dung giới thiệu -->
        <div class="lg:col-span-7 space-y-4">
          <h3 class="text-lg sm:text-xl font-bold text-brand-navy">
            CÔNG TY TNHH SẢN XUẤT TM&amp;DV GIA HƯNG WINDOW – ĐÀ NẴNG
          </h3>
          <p class="text-sm sm:text-base text-slate-600 leading-relaxed">
            <strong>Gia Hưng Window</strong> là đơn vị chuyên thiết kế, sản xuất trực tiếp và thi công lắp đặt trọn gói các hạng mục nhôm kính chất lượng cao tại Đà Nẵng và các tỉnh miền Trung.
          </p>
          <p class="text-sm sm:text-base text-slate-600 leading-relaxed">
            Các dòng sản phẩm chủ lực bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu chính hãng</strong>, Cửa kính cường lực, Cửa nhựa lõi thép uPVC, Cửa kính tự động, Cầu thang kính, Phòng tắm kính và Kính ốp bếp cường lực. Với phương châm <em>"Cửa đẹp cho mọi công trình – Bền vững cùng thời gian"</em>, chúng tôi cam kết vật tư chuẩn nguồn gốc, giá xưởng cạnh tranh và bảo hành tận tâm.
          </p>

          <!-- 4 Cam kết gọn gàng dạng lưới 2x2 -->
          <div class="grid grid-cols-2 gap-3 pt-2">
            <div class="p-3 rounded-xl bg-brand-light border border-slate-100">
              <div class="text-xs font-bold text-brand-navy mb-0.5"><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Vật tư chính hãng</div>
              <p class="text-xs text-slate-600">Nhôm Xingfa dày chuẩn, phụ kiện đồng bộ 100%.</p>
            </div>
            <div class="p-3 rounded-xl bg-brand-light border border-slate-100">
              <div class="text-xs font-bold text-brand-navy mb-0.5"><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Giá trực tiếp tại xưởng</div>
              <p class="text-xs text-slate-600">Sản xuất tại Hòa Vang, tối ưu chi phí cho khách hàng.</p>
            </div>
            <div class="p-3 rounded-xl bg-brand-light border border-slate-100">
              <div class="text-xs font-bold text-brand-navy mb-0.5"><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Lắp đặt chuẩn kỹ thuật</div>
              <p class="text-xs text-slate-600">Kín khít, cách âm, chống thấm nước mưa gió bão.</p>
            </div>
            <div class="p-3 rounded-xl bg-brand-light border border-slate-100">
              <div class="text-xs font-bold text-brand-navy mb-0.5"><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Bảo hành chu đáo</div>
              <p class="text-xs text-slate-600">Bảo trì định kỳ, hỗ trợ kỹ thuật nhanh trong 24h.</p>
            </div>
          </div>
        </div>

        <!-- Cột 4 chỉ số nổi bật chuẩn Flatsome -->
        <div class="lg:col-span-5">
          <div class="grid grid-cols-2 gap-3 sm:gap-4">
            <div class="bg-brand-navy text-white p-5 rounded-xl text-center shadow-sm">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-gold">150+</div>
              <div class="text-xs sm:text-sm text-slate-200 mt-1">Dự án hoàn thành</div>
            </div>
            <div class="bg-brand-navy text-white p-5 rounded-xl text-center shadow-sm">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-gold">50+</div>
              <div class="text-xs sm:text-sm text-slate-200 mt-1">Kỹ thuật kinh nghiệm</div>
            </div>
            <div class="bg-brand-navy text-white p-5 rounded-xl text-center shadow-sm">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-gold">100+</div>
              <div class="text-xs sm:text-sm text-slate-200 mt-1">Mẫu cửa chất lượng</div>
            </div>
            <div class="bg-brand-navy text-white p-5 rounded-xl text-center shadow-sm">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand-gold">100%</div>
              <div class="text-xs sm:text-sm text-slate-200 mt-1">Khách hàng hài lòng</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 7. CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (UX Builder: Section Projects) ==================== -->
  <section id="cong-trinh" class="py-8 lg:py-12 bg-brand-light">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Các Dự Án Tiêu Biểu Tại Đà Nẵng
        </h2>
      </div>

      <!-- 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="projectGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu dự án render từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 8. BẢNG BÁO GIÁ & FORM YÊU CẦU BÁO GIÁ (UX Builder: Section Quote Form) ==================== -->
  <section id="bao-gia" class="py-8 lg:py-12 bg-white">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Báo Giá &amp; Đăng Ký Tư Vấn
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">
        <!-- Cột Trái: Bảng giá tham khảo nhanh -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
          <div class="bg-brand-navy text-white px-4 py-3 font-bold text-sm sm:text-base flex items-center justify-between">
            <span>BẢNG BÁO GIÁ CỬA NHÔM XINGFA THAM KHẢO</span>
            <span class="text-xs font-normal text-amber-300">ĐVT: VNĐ/m²</span>
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-slate-100 text-brand-navy font-semibold border-b border-slate-200">
                  <th class="py-2.5 px-3">STT</th>
                  <th class="py-2.5 px-3">Hạng mục cửa</th>
                  <th class="py-2.5 px-3">Độ dày nhôm</th>
                  <th class="py-2.5 px-3 text-right">Đơn giá ưu đãi</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-100">
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">01</td>
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi mở quay 1 cánh Xingfa hệ 55</td>
                  <td class="py-2.5 px-3 text-slate-600">2.0 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-red-600">2.050.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">02</td>
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi mở quay 2 cánh Xingfa hệ 55</td>
                  <td class="py-2.5 px-3 text-slate-600">2.0 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-red-600">2.050.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">03</td>
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi mở quay 3 – 4 cánh Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">2.0 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-red-600">2.100.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">04</td>
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi xếp trượt nhôm Xingfa hệ 63</td>
                  <td class="py-2.5 px-3 text-slate-600">1.8 – 2.5 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-red-600">2.200.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">05</td>
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa sổ mở hất 2 cánh Xingfa hệ 55</td>
                  <td class="py-2.5 px-3 text-slate-600">1.4 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-red-600">1.900.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">06</td>
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa kính cường lực 10mm – 12mm</td>
                  <td class="py-2.5 px-3 text-slate-600">Kính Hải Long/Việt Nhật</td>
                  <td class="py-2.5 px-3 text-right font-bold text-red-600">Liên hệ</td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="px-4 py-2.5 bg-slate-50 text-xs text-slate-500 border-t border-slate-100">
            * Báo giá đã bao gồm kính cường lực tiêu chuẩn, vận chuyển và lắp đặt nội thành Đà Nẵng. Chiết khấu thêm cho công trình khối lượng lớn.
          </div>
        </div>

        <!-- Cột Phải: Form Yêu Cầu & Báo Giá Trang Chủ -->
        <div class="lg:col-span-5 bg-brand-light rounded-xl border border-slate-200 p-5 sm:p-6 shadow-sm">
          <h3 class="text-base sm:text-lg font-extrabold text-brand-navy uppercase mb-1">
            Đăng Ký Nhận Báo Giá Miễn Phí
          </h3>
          <p class="text-xs sm:text-sm text-slate-600 mb-4">
            Để lại thông tin, kỹ thuật viên Gia Hưng Window sẽ khảo sát và gửi báo giá chi tiết trong 15 phút.
          </p>

          <form id="quoteForm" class="space-y-3" novalidate>
            <div>
              <label for="customerName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
              <input type="text" id="customerName" required placeholder="Nhập họ và tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy focus:border-brand-navy" />
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label for="customerPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input type="tel" id="customerPhone" required placeholder="VD: 0965.656.469" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy focus:border-brand-navy" />
              </div>
              <div>
                <label for="customerCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                <select id="customerCategory" class="w-full px-3 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy focus:border-brand-navy">
                  <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                </select>
              </div>
            </div>

            <div>
              <label for="customerNote" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình &amp; Ghi chú kích thước</label>
              <textarea id="customerNote" rows="3" placeholder="VD: Nhà phố tại Hòa Vang, cần làm cửa đi 4 cánh và 3 cửa sổ..." class="w-full px-3.5 py-2 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy focus:border-brand-navy"></textarea>
            </div>

            <button type="submit" class="w-full py-3 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm uppercase tracking-wide shadow transition">
              <i class="fa-solid fa-paper-plane mr-1.5"></i> Gửi Yêu Cầu Báo Giá
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 9. DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ (UX Builder: Blog Posts) ==================== -->
  <section id="tin-tuc" class="py-8 lg:py-12 bg-brand-light">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Tin Tức &amp; Kiến Thức Nhôm Kính
        </h2>
      </div>

      <!-- 2 cột trên mobile, 4 cột trên desktop -->
      <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Dữ liệu bài viết render từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 10. ĐỐI TÁC CỦA CHÚNG TÔI (UX Builder: Logo Partner Grid) ==================== -->
  <section class="py-8 lg:py-10 bg-white border-t border-slate-100">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Đối Tác Của Chúng Tôi
        </h2>
      </div>

      <div id="partnerGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
        <!-- 6 ảnh đối tác Google Drive render từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 11. GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ (UX Builder: Map & Social) ==================== -->
  <section id="lien-he" class="py-8 lg:py-12 bg-brand-light border-t border-slate-200">
    <div class="container-95">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-navy text-center">
          Bản Đồ &amp; Kết Nối Fanpage
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-6 items-stretch">
        <!-- Cột Google Map địa chỉ Thôn Phú Thượng, Hòa Vang, Đà Nẵng -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="px-4 py-3 bg-brand-navy text-white flex flex-wrap items-center justify-between gap-2">
            <div class="text-xs sm:text-sm font-bold flex items-center gap-2">
              <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
              <span>Bản đồ: Thôn Phú Thượng, Hòa Vang, Đà Nẵng</span>
            </div>
            <a href="https://www.google.com/maps/search/?api=1&query=Thôn+Phú+Thượng,+Hòa+Vang,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-amber-300 hover:underline">
              Chỉ đường Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
            </a>
          </div>
          <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
            <iframe
              title="Bản đồ Công ty TNHH Sản Xuất TM&DV Gia Hưng Window - Thôn Phú Thượng, Hòa Vang, Đà Nẵng"
              src="https://maps.google.com/maps?q=Th%C3%B4n+Ph%C3%BA+Th%C6%B0%E1%BB%A3ng,+H%C3%B2a+Vang,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen>
            </iframe>
          </div>
        </div>

        <!-- Cột Fanpage Facebook đưa ra ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
          <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
            <div class="text-xs sm:text-sm font-bold flex items-center gap-2">
              <i class="fa-brands fa-facebook"></i>
              <span>Fanpage Gia Hưng Window</span>
            </div>
            <a href="https://www.facebook.com/profile.php?id=61575187401153" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold bg-white/20 hover:bg-white/30 px-2.5 py-1 rounded transition">
              Theo dõi trang
            </a>
          </div>

          <!-- Khung nhúng Fanpage + Thẻ hiển thị trực quan đảm bảo luôn đẹp ngay cả khi trình duyệt chặn iframe Facebook -->
          <div class="p-4 flex-1 flex flex-col justify-between gap-4">
            <!-- Header Card Fanpage -->
            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
              <div class="h-24 bg-gradient-to-r from-brand-navy to-brand-blue relative p-3 flex items-end">
                <div class="flex items-center gap-3">
                  <div class="w-12 h-12 rounded-xl bg-white p-1 shadow-md flex items-center justify-center shrink-0">
                    <svg class="w-10 h-10" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <rect x="4" y="4" width="56" height="56" rx="12" fill="#0E3A66"/>
                      <rect x="9" y="9" width="46" height="46" rx="8" stroke="#D98A1A" stroke-width="2.5"/>
                      <path d="M17 17H31V47H17V17Z" fill="#16528E" stroke="#FFFFFF" stroke-width="2"/>
                      <path d="M31 17L47 13V51L31 47V17Z" fill="#D98A1A"/>
                    </svg>
                  </div>
                  <div class="text-white leading-tight">
                    <div class="font-bold text-sm">Gia Hưng Window – Đà Nẵng</div>
                    <div class="text-[11px] text-slate-200">Công ty TNHH Sản Xuất TM&amp;DV</div>
                  </div>
                </div>
              </div>

              <div class="p-3.5 space-y-2.5">
                <p class="text-xs text-slate-600 leading-relaxed">
                  Cập nhật hình ảnh thi công thực tế cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính và các chương trình ưu đãi mới nhất tại Đà Nẵng.
                </p>
                <div class="grid grid-cols-3 gap-2">
                  <img src="https://drive.google.com/thumbnail?id=1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm&sz=w400" data-drive-id="1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm" alt="Mẫu cửa Gia Hưng Window" class="w-full aspect-square object-cover rounded-lg drive-img" />
                  <img src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w400" data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ" alt="Công trình Gia Hưng Window" class="w-full aspect-square object-cover rounded-lg drive-img" />
                  <img src="https://drive.google.com/thumbnail?id=1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ&sz=w400" data-drive-id="1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ" alt="Cửa xếp trượt Xingfa" class="w-full aspect-square object-cover rounded-lg drive-img" />
                </div>
              </div>
            </div>

            <!-- Nhúng plugin Facebook Page chính thức (hiển thị bổ sung nếu trình duyệt cho phép) -->
            <div class="flex flex-wrap items-center gap-2.5">
              <a href="https://www.facebook.com/profile.php?id=61575187401153" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-2 py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs sm:text-sm font-bold transition">
                <i class="fa-brands fa-facebook-f"></i> Truy Cập Fanpage Facebook
              </a>
              <a href="https://zalo.me/0965656469" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-4 rounded-lg bg-brand-navy hover:bg-brand-dark text-white text-xs sm:text-sm font-bold transition">
                <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 12. FOOTER CHUẨN FLATSOME ==================== -->
  <footer class="bg-brand-dark text-slate-300 pt-10 pb-6 border-t-4 border-brand-gold">
    <div class="container-95">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="4" width="56" height="56" rx="12" fill="#0E3A66"/>
              <rect x="9" y="9" width="46" height="46" rx="8" stroke="#D98A1A" stroke-width="2.5"/>
              <path d="M17 17H31V47H17V17Z" fill="#16528E" stroke="#FFFFFF" stroke-width="2"/>
              <path d="M31 17L47 13V51L31 47V17Z" fill="#D98A1A"/>
            </svg>
            <div>
              <div class="text-sm font-extrabold text-white">GIA HƯNG <span class="text-brand-gold">WINDOW</span></div>
              <div class="text-[10px] text-slate-400 uppercase">Công ty TNHH Sản Xuất TM&amp;DV</div>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brand-gold mt-1"></i>
              <span>Địa chỉ: Thôn Phú Thượng, Hòa Vang, Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-brand-gold"></i>
              <a href="tel:0965656469" class="hover:text-brand-gold transition font-semibold text-white">Hotline: 0965.656.469</a>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-brand-gold"></i>
              <span>Website: giahungwindow.com</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-brand-gold"></i>
              <a href="https://www.facebook.com/profile.php?id=61575187401153" target="_blank" rel="noopener noreferrer" class="hover:text-brand-gold transition">Fanpage Gia Hưng Window</a>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-1')" class="hover:text-brand-gold transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-2')" class="hover:text-brand-gold transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-3')" class="hover:text-brand-gold transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-4')" class="hover:text-brand-gold transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="highlightProduct('xingfa-5')" class="hover:text-brand-gold transition">Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
            Danh Mục Dịch Vụ
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#san-pham-xingfa" class="hover:text-brand-gold transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('nhua-loi-thep')" class="hover:text-brand-gold transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')" class="hover:text-brand-gold transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')" class="hover:text-brand-gold transition">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')" class="hover:text-brand-gold transition">Kính ốp bếp màu cường lực</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')" class="hover:text-brand-gold transition">Phòng tắm kính cường lực</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
            Liên Kết Nhanh
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#gioi-thieu" class="hover:text-brand-gold transition">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-brand-gold transition">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-gold transition">Bảng báo giá mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-gold transition">Tin tức &amp; Tư vấn</a></li>
            <li><a href="#lien-he" class="hover:text-brand-gold transition">Bản đồ &amp; Liên hệ</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <p>© 2026 Công ty TNHH Sản Xuất TM&amp;DV Gia Hưng Window (giahungwindow.com). Bảo lưu mọi quyền.</p>
        <p>Địa chỉ: Thôn Phú Thượng, Hòa Vang, Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ==================== 13. CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE ==================== -->
  <!-- Tương thích 100% trên cả điện thoại và máy tính, gọn gàng không che nội dung, không tràn ngang -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/profile.php?id=61575187401153" target="_blank" rel="noopener noreferrer"
       class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465CC] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-3.5 transition"
       aria-label="Facebook Gia Hưng Window">
      <i class="fa-brands fa-facebook-f text-base sm:text-lg w-5 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0965656469" target="_blank" rel="noopener noreferrer"
       class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-3.5 transition"
       aria-label="Chat Zalo 0965.656.469">
      <span class="font-extrabold text-xs sm:text-sm w-5 text-center leading-none">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0965656469"
       class="relative fab-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-xl px-3.5 py-2.5 sm:px-4 transition"
       aria-label="Gọi Hotline 0965.656.469">
      <i class="fa-solid fa-phone-volume text-base sm:text-lg w-5 text-center"></i>
      <span class="text-xs sm:text-sm font-extrabold tracking-tight">0965.656.469</span>
    </a>
  </div>

  <!-- ==================== 14. MODAL XEM CHI TIẾT (Sản phẩm / Dự án / Tin tức / Thông báo) ==================== -->
  <div id="detailModal" class="fixed inset-0 z-[70] hidden items-center justify-center bg-black/60 p-3 sm:p-5">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-brand-navy text-white px-5 py-3.5 flex items-center justify-between z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold pr-4">Chi tiết</h3>
        <button type="button" onclick="closeModal()" class="w-8 h-8 rounded-full bg-white/15 hover:bg-white/25 flex items-center justify-center text-white transition" aria-label="Đóng hộp thoại">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="modalBody" class="p-5 space-y-4">
        <!-- Nội dung động -->
      </div>
    </div>
  </div>

  <!-- Hộp thông báo Toast (Thay thế hoàn toàn alert) -->
  <div id="toastBox" class="fixed top-20 right-4 z-[80] hidden max-w-sm bg-brand-navy text-white px-4 py-3 rounded-xl shadow-xl border-l-4 border-brand-gold text-xs sm:text-sm">
    <div class="flex items-start gap-2.5">
      <i class="fa-solid fa-circle-check text-brand-gold text-base mt-0.5"></i>
      <div id="toastMessage"></div>
    </div>
  </div>

  <!-- ==================== 15. JAVASCRIPT XỬ LÝ DỮ LIỆU & TƯƠNG TÁC ==================== -->
  <script>
    /**
     * Hàm tạo URL ảnh từ Google Drive ID ổn định với fallback 2 tầng
     */
    function driveUrl(id, size = 1000) {
      return `https://drive.google.com/thumbnail?id=${id}&sz=w${size}`;
    }

    function bindImageFallbacks() {
      document.querySelectorAll('img.drive-img').forEach((img) => {
        if (img.dataset.bound === '1') return;
        img.dataset.bound = '1';
        img.addEventListener('error', function () {
          const id = this.dataset.driveId;
          const step = Number(this.dataset.errStep || '0');
          if (step === 0 && id) {
            this.dataset.errStep = '1';
            this.src = `https://lh3.googleusercontent.com/d/${id}`;
          } else if (step === 1) {
            this.dataset.errStep = '2';
            const label = encodeURIComponent(this.alt || 'Gia Hung Window');
            this.src = `https://placehold.co/600x450/0e3a66/ffffff?text=${label}`;
          }
        });
      });
    }

    /**
     * DỮ LIỆU 6 DANH MỤC SẢN PHẨM (Ảnh thực tế từ Google Drive)
     */
    const categoriesData = [
      {
        id: 'xingfa',
        name: 'Cửa nhôm Xingfa',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        desc: 'Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông hệ 55, hệ 63, hệ 93, kết hợp phụ kiện Kinlong đồng bộ, kính cường lực an toàn cách âm cách nhiệt vượt trội.'
      },
      {
        id: 'nhua-loi-thep',
        name: 'Cửa nhựa lõi thép',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        desc: 'Cửa nhựa lõi thép uPVC gia cường lõi thép mạ kẽm, chống cong vênh mối mọt, cách âm tốt, thẩm mỹ hiện đại và giá thành hợp lý cho nhà ở.'
      },
      {
        id: 'cua-tu-dong',
        name: 'Cửa kính tự động',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Cửa kính trượt tự động cảm biến mắt thần Hàn Quốc, Nhật Bản vận hành êm ái, sang trọng cho khách sạn, showroom, siêu thị và văn phòng.'
      },
      {
        id: 'cau-thang-kinh',
        name: 'Cầu thang kính',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        desc: 'Cầu thang kính cường lực 10mm – 12mm kết hợp tay vịn gỗ căm xe hoặc inox 304, mở rộng không gian thoáng sáng và sang trọng cho ngôi nhà.'
      },
      {
        id: 'kinh-op-bep',
        name: 'Kính ốp bếp',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        desc: 'Kính màu ốp bếp cường lực chịu nhiệt cao, bề mặt phẳng mịn chống bám dầu mỡ, dễ dàng vệ sinh với bảng màu đa dạng hợp phong thủy.'
      },
      {
        id: 'phong-tam-kinh',
        name: 'Phòng tắm kính',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        desc: 'Vách tắm kính cường lực 10mm phụ kiện inox 304 chống gỉ sét, ngăn nước tuyệt đối, giúp phòng tắm luôn khô ráo, sạch sẽ và đẳng cấp.'
      }
    ];

    /**
     * DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA (Kèm giá bán và % giảm giá góc trên bên trái)
     */
    const productsData = [
      {
        id: 'xingfa-1',
        name: 'Cửa đi quay mở 1 cánh nhôm Xingfa',
        category: 'mo-quay',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.450.000 ₫',
        price: '2.050.000 ₫/m²',
        discount: '-16%',
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm – 10mm, gioăng EPDM kép kín khít, phụ kiện Kinlong chính hãng. Phù hợp cửa phòng ngủ, cửa thông phòng, cửa ban công.'
      },
      {
        id: 'xingfa-2',
        name: 'Cửa đi quay mở 2 cánh nhôm Xingfa',
        category: 'mo-quay',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.400.000 ₫',
        price: '2.050.000 ₫/m²',
        discount: '-15%',
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, mở quay linh hoạt vào trong hoặc ra ngoài, chốt đa điểm chắc chắn, sơn tĩnh điện bền màu chịu khí hậu biển Đà Nẵng.'
      },
      {
        id: 'xingfa-3',
        name: 'Cửa đi quay mở 3 cánh nhôm Xingfa',
        category: 'mo-quay',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.450.000 ₫',
        price: '2.100.000 ₫/m²',
        discount: '-14%',
        specs: 'Thiết kế 3 cánh nhôm Xingfa nhập khẩu độ cứng vững cao, tạo không gian mặt tiền thoáng rộng, chống gió giật hiệu quả, thích hợp nhà phố và biệt thự.'
      },
      {
        id: 'xingfa-4',
        name: 'Cửa đi quay mở 4 cánh nhôm Xingfa',
        category: 'mo-quay',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.500.000 ₫',
        price: '2.100.000 ₫/m²',
        discount: '-16%',
        specs: 'Mẫu cửa chính 4 cánh sang trọng hàng đầu cho nhà phố Đà Nẵng. Khung nhôm hệ 55 dày 2.0mm, bản lề 3D chịu lực lớn, khóa đa điểm an toàn chống trộm.'
      },
      {
        id: 'xingfa-5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xep-truot',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.650.000 ₫',
        price: '2.200.000 ₫/m²',
        discount: '-17%',
        specs: 'Nhôm Xingfa hệ 63 chuyên dụng xếp trượt (từ 3 cánh, 4 cánh, 5 cánh đến 6 cánh), ray trượt bánh xe treo êm ái, mở tối đa 100% diện tích ô cửa cho resort, villa, mặt tiền lớn.'
      },
      {
        id: 'xingfa-6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'cua-so',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.250.000 ₫',
        price: '1.900.000 ₫/m²',
        discount: '-15%',
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh định vị góc mở tối đa 45 độ chống va đập gió bão, mở thoáng ngay cả khi trời mưa nhỏ, đảm bảo an toàn tuyệt đối.'
      }
    ];

    /**
     * DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Ảnh Google Drive thực tế)
     */
    const projectsData = [
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        location: 'Đà Nẵng',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        summary: 'Thi công toàn bộ hệ thống cửa đi nhôm Xingfa, vách kính mặt dựng và phòng tắm kính cường lực đạt chuẩn cách âm khách sạn.'
      },
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        location: 'Quảng Nam – Đà Nẵng',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        summary: 'Hạng mục cửa đi xếp trượt nhôm Xingfa view thiên nhiên, cửa sổ mở hất và hệ thống kính cường lực cao cấp chuẩn nghỉ dưỡng 4 sao.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        location: 'Đà Nẵng',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        summary: 'Cung cấp và lắp đặt đồng bộ cửa nhôm Xingfa chịu gió biển, cửa kính tự động sảnh lễ tân và lan can kính cường lực.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        location: 'Đà Nẵng',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        summary: 'Thi công trọn gói hệ cửa nhôm kính mặt tiền, cửa phòng và vách kính tắm sang trọng, đảm bảo tiến độ bàn giao vượt kỳ vọng.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        location: 'Đà Nẵng',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        summary: 'Thiết kế và thi công hệ vách kính lớn, cửa nhôm Xingfa hệ 55 và cầu thang kính hiện đại tạo điểm nhấn kiến trúc nổi bật.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        location: 'Biển Mỹ Khê, Đà Nẵng',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        summary: 'Hệ thống cửa nhôm Xingfa sơn tĩnh điện chống ăn mòn muối biển, kính hộp cách âm mang lại không gian yên tĩnh cho du khách.'
      }
    ];

    /**
     * DỮ LIỆU 6 ĐỐI TÁC (Ảnh Google Drive thực tế)
     */
    const partnersData = [
      { name: 'Đối tác nhôm kính 1', driveId: '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk' },
      { name: 'Đối tác nhôm kính 2', driveId: '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq' },
      { name: 'Đối tác nhôm kính 3', driveId: '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn' },
      { name: 'Đối tác nhôm kính 4', driveId: '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT' },
      { name: 'Đối tác nhôm kính 5', driveId: '1SDcarhnX0yypmqdbawICjYBRtFnKngn-' },
      { name: 'Đối tác nhôm kính 6', driveId: '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg' }
    ];

    /**
     * DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ
     */
    const newsData = [
      {
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
        date: '18/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Khí hậu miền Trung có gió bão và hơi muối biển đòi hỏi vật liệu cửa bền bỉ, không oxy hóa. Tìm hiểu lý do nhôm Xingfa được ưa chuộng...',
        content: 'Nhôm Xingfa nhập khẩu được xử lý bề mặt và sơn tĩnh điện ngoài trời cao cấp, có khả năng chống ăn mòn muối biển và không bị cong vênh dưới nắng gắt miền Trung. Kết hợp gioăng EPDM kép và phụ kiện Kinlong giúp cửa kín nước tuyệt đối trong mùa mưa bão Đà Nẵng.'
      },
      {
        title: 'Cách phân biệt cửa nhôm Xingfa nhập khẩu chính hãng tem đỏ',
        date: '12/11/2026',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        excerpt: 'Hướng dẫn kiểm tra mã QR tem đỏ, độ dày thanh profile 1.4mm – 2.0mm và màu ánh kim bên trong khoang nhôm chuẩn chính hãng...',
        content: 'Để tránh mua phải hàng giả kém chất lượng, khách hàng cần kiểm tra 4 yếu tố: (1) Tem đỏ sắc nét có mã QR kiểm tra nguồn gốc, (2) Độ dày chuẩn 2.0mm cho cửa đi và 1.4mm cho cửa sổ, (3) Mặt cắt bên trong có lớp mạ crom ánh đồng chống oxy hóa, (4) Ép góc ke nhảy kín khít bằng máy chuyên dụng tại xưởng Gia Hưng Window.'
      },
      {
        title: 'Nên chọn cửa nhôm Xingfa hay cửa nhựa lõi thép cho nhà phố?',
        date: '05/11/2026',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        excerpt: 'So sánh chi tiết về độ bền, khả năng chịu lực, tính thẩm mỹ và chi phí đầu tư giữa cửa nhôm Xingfa và cửa nhựa lõi thép uPVC...',
        content: 'Cả hai dòng cửa đều cách âm tốt hơn cửa truyền thống. Cửa nhôm Xingfa nổi trội về độ cứng vững, khung thanh mảnh sang trọng, bền màu hàng chục năm nên rất lý tưởng cho cửa mặt tiền và cửa chịu nắng mưa trực tiếp. Cửa nhựa lõi thép uPVC có ưu điểm chi phí tiết kiệm, phù hợp cửa phòng ngủ và không gian cần cách âm cao.'
      },
      {
        title: 'Kinh nghiệm chọn kính cường lực cho phòng tắm và cầu thang an toàn',
        date: '28/10/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        excerpt: 'Tư vấn chọn độ dày kính 10mm hay 12mm, phụ kiện inox 304 chống gỉ và quy trình lắp đặt đạt chuẩn an toàn cho gia đình...',
        content: 'Với phòng tắm kính nên dùng kính cường lực 10mm kết hợp bản lề kẹp inox 304 cao cấp để chống gỉ trong môi trường ẩm ướt. Với cầu thang kính và lan can ban công nên sử dụng kính cường lực 10mm – 12mm được mài cạnh tinh xảo, đảm bảo chịu lực và an toàn tuyệt đối cho trẻ nhỏ.'
      }
    ];

    /**
     * RENDER DANH MỤC SẢN PHẨM
     */
    function renderCategories() {
      const container = document.getElementById('categoryGrid');
      container.innerHTML = categoriesData.map(cat => `
        <div onclick="openCategoryDetail('${cat.id}')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-navy transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="${driveUrl(cat.driveId, 700)}" data-drive-id="${cat.driveId}" alt="${cat.name}" class="w-full h-full object-cover img-zoom drive-img" loading="lazy" />
          </div>
          <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center bg-white">
            <h3 class="text-xs sm:text-[13px] font-bold uppercase text-brand-navy group-hover:text-brand-gold transition leading-snug">
              ${cat.name}
            </h3>
          </div>
        </div>
      `).join('');
      bindImageFallbacks();
    }

    /**
     * RENDER SẢN PHẨM (2 cột trên mobile, không mất chữ tên sản phẩm, có giá & giảm giá % góc trên bên trái)
     */
    function renderProducts(filterType = 'all') {
      const container = document.getElementById('productGrid');
      const filtered = filterType === 'all'
        ? productsData
        : productsData.filter(p => p.category === filterType);

      container.innerHTML = filtered.map(p => `
        <article id="card-${p.id}" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col h-full">
          <!-- Khung ảnh sản phẩm + Nhãn giảm giá % ở góc trên bên trái -->
          <div onclick="openProductDetail('${p.id}')" class="relative aspect-[4/3] overflow-hidden bg-slate-100 cursor-pointer">
            <span class="absolute top-2 left-2 z-10 bg-red-600 text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow">
              ${p.discount}
            </span>
            <img src="${driveUrl(p.driveId, 800)}" data-drive-id="${p.driveId}" alt="${p.name}" class="w-full h-full object-cover img-zoom drive-img" loading="lazy" />
          </div>

          <!-- Nội dung sản phẩm tối ưu cho 2 cột trên điện thoại: không bị tràn hay thiếu chữ -->
          <div class="p-2.5 sm:p-4 flex flex-col flex-1">
            <h3 onclick="openProductDetail('${p.id}')" class="cursor-pointer text-xs sm:text-sm md:text-[15px] font-bold text-slate-800 group-hover:text-brand-navy leading-snug break-words mb-2">
              ${p.name}
            </h3>

            <div class="mt-auto space-y-2.5">
              <!-- Giá gốc & Giá khuyến mãi -->
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-sm sm:text-base font-extrabold text-red-600">${p.price}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.oldPrice}</span>
              </div>

              <!-- Nút hành động -->
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5">
                <button type="button" onclick="openProductDetail('${p.id}')" class="w-full py-1.5 sm:py-2 px-2 rounded-lg border border-brand-navy text-brand-navy hover:bg-brand-navy hover:text-white text-[11px] sm:text-xs font-semibold transition">
                  Xem chi tiết
                </button>
                <button type="button" onclick="requestProductQuote('${p.name}')" class="w-full py-1.5 sm:py-2 px-2 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white text-[11px] sm:text-xs font-bold transition">
                  Báo giá ngay
                </button>
              </div>
            </div>
          </div>
        </article>
      `).join('');

      bindImageFallbacks();
    }

    /**
     * RENDER DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
     */
    function renderProjects() {
      const container = document.getElementById('projectGrid');
      container.innerHTML = projectsData.map((proj, idx) => `
        <article onclick="openProjectDetail(${idx})" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col h-full">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="${driveUrl(proj.driveId, 900)}" data-drive-id="${proj.driveId}" alt="${proj.title}" class="w-full h-full object-cover img-zoom drive-img" loading="lazy" />
          </div>
          <div class="p-3 sm:p-4 flex flex-col flex-1">
            <div class="text-[11px] font-semibold text-brand-gold mb-1">
              <i class="fa-solid fa-location-dot mr-1"></i>${proj.location}
            </div>
            <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words mb-1.5">
              ${proj.title}
            </h3>
            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed mt-auto">
              ${proj.summary}
            </p>
          </div>
        </article>
      `).join('');
      bindImageFallbacks();
    }

    /**
     * RENDER BÀI VIẾT TIN TỨC
     */
    function renderNews() {
      const container = document.getElementById('newsGrid');
      container.innerHTML = newsData.map((post, idx) => `
        <article onclick="openNewsDetail(${idx})" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col h-full">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="${driveUrl(post.driveId, 700)}" data-drive-id="${post.driveId}" alt="${post.title}" class="w-full h-full object-cover img-zoom drive-img" loading="lazy" />
          </div>
          <div class="p-3 sm:p-4 flex flex-col flex-1">
            <div class="text-[11px] text-slate-400 mb-1">
              <i class="fa-regular fa-calendar mr-1"></i>${post.date}
            </div>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-navy transition leading-snug break-words mb-2">
              ${post.title}
            </h3>
            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed mb-3 flex-1">
              ${post.excerpt}
            </p>
            <span class="text-xs font-semibold text-brand-gold mt-auto inline-flex items-center gap-1">
              Xem thêm <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </span>
          </div>
        </article>
      `).join('');
      bindImageFallbacks();
    }

    /**
     * RENDER ĐỐI TÁC
     */
    function renderPartners() {
      const container = document.getElementById('partnerGrid');
      container.innerHTML = partnersData.map(partner => `
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-navy transition">
          <img src="${driveUrl(partner.driveId, 500)}" data-drive-id="${partner.driveId}" alt="${partner.name}" class="max-h-full max-w-full object-contain drive-img" loading="lazy" />
        </div>
      `).join('');
      bindImageFallbacks();
    }

    /**
     * LỌC SẢN PHẨM & HIGHLIGHT KHI BẤM TỪ MENU
     */
    function filterProducts(type) {
      renderProducts(type === 'xingfa' ? 'all' : type);
      document.querySelectorAll('.filter-btn').forEach(btn => {
        const active = btn.dataset.filter === (type === 'xingfa' ? 'all' : type);
        btn.className = active
          ? 'filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-navy text-white transition whitespace-nowrap'
          : 'filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition whitespace-nowrap';
      });
    }

    function highlightProduct(productId) {
      filterProducts('all');
      setTimeout(() => {
        const card = document.getElementById(`card-${productId}`);
        if (card) {
          card.scrollIntoView({ behavior: 'smooth', block: 'center' });
          card.classList.add('ring-2', 'ring-brand-gold');
          setTimeout(() => card.classList.remove('ring-2', 'ring-brand-gold'), 2200);
        }
      }, 150);
    }

    function filterCategoryScroll(key) {
      const el = document.getElementById('danh-muc-san-pham');
      if (el) el.scrollIntoView({ behavior: 'smooth' });
    }

    /**
     * ĐIỀN TỰ ĐỘNG VÀO FORM BÁO GIÁ
     */
    function requestProductQuote(productName) {
      closeModal();
      const noteField = document.getElementById('customerNote');
      if (noteField) {
        noteField.value = `Tôi cần tư vấn và báo giá sản phẩm: ${productName}`;
      }
      const section = document.getElementById('bao-gia');
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }
      setTimeout(() => {
        const nameInput = document.getElementById('customerName');
        if (nameInput) nameInput.focus();
      }, 450);
    }

    /**
     * MODAL CHI TIẾT (Sản phẩm / Danh mục / Dự án / Tin tức)
     */
    function openModal(title, htmlContent) {
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalBody').innerHTML = htmlContent;
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      bindImageFallbacks();
    }

    function closeModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function openProductDetail(id) {
      const p = productsData.find(item => item.id === id);
      if (!p) return;
      openModal(p.name, `
        <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <span class="absolute top-3 left-3 bg-red-600 text-white text-xs font-extrabold px-2.5 py-1 rounded-md shadow">${p.discount}</span>
          <img src="${driveUrl(p.driveId, 1000)}" data-drive-id="${p.driveId}" alt="${p.name}" class="w-full h-full object-cover drive-img" />
        </div>
        <div class="flex flex-wrap items-baseline gap-3">
          <span class="text-xl font-extrabold text-red-600">${p.price}</span>
          <span class="text-sm text-slate-400 line-through">${p.oldPrice}</span>
        </div>
        <p class="text-sm text-slate-600 leading-relaxed">${p.specs}</p>
        <div class="p-3.5 rounded-xl bg-brand-light text-xs sm:text-sm text-slate-700 space-y-1">
          <div><strong class="text-brand-navy">Đơn vị thi công:</strong> Công ty TNHH Sản Xuất TM&amp;DV Gia Hưng Window</div>
          <div><strong class="text-brand-navy">Địa chỉ xưởng:</strong> Thôn Phú Thượng, Hòa Vang, Đà Nẵng</div>
          <div><strong class="text-brand-navy">Hotline / Zalo tư vấn:</strong> <a href="tel:0965656469" class="text-red-600 font-bold">0965.656.469</a></div>
        </div>
        <div class="flex flex-wrap gap-2.5 pt-1">
          <button type="button" onclick="requestProductQuote('${p.name}')" class="flex-1 py-2.5 px-4 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm transition">
            Nhận Báo Giá Sản Phẩm Này
          </button>
          <a href="tel:0965656469" class="py-2.5 px-4 rounded-lg bg-brand-navy hover:bg-brand-dark text-white font-bold text-sm transition">
            Gọi 0965.656.469
          </a>
        </div>
      `);
    }

    function openCategoryDetail(catId) {
      if (catId === 'xingfa') {
        const el = document.getElementById('san-pham-xingfa');
        if (el) el.scrollIntoView({ behavior: 'smooth' });
        return;
      }
      const cat = categoriesData.find(c => c.id === catId);
      if (!cat) return;
      openModal(`Danh mục: ${cat.name}`, `
        <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <img src="${driveUrl(cat.driveId, 1000)}" data-drive-id="${cat.driveId}" alt="${cat.name}" class="w-full h-full object-cover drive-img" />
        </div>
        <p class="text-sm text-slate-600 leading-relaxed">${cat.desc}</p>
        <div class="flex flex-wrap gap-2.5 pt-2">
          <button type="button" onclick="requestProductQuote('${cat.name}')" class="flex-1 py-2.5 px-4 rounded-lg bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm transition">
            Yêu Cầu Tư Vấn &amp; Báo Giá
          </button>
          <a href="https://zalo.me/0965656469" target="_blank" rel="noopener noreferrer" class="py-2.5 px-4 rounded-lg bg-[#0068FF] text-white font-bold text-sm transition">
            Chat Zalo Ngay
          </a>
        </div>
      `);
    }

    function openProjectDetail(idx) {
      const proj = projectsData[idx];
      if (!proj) return;
      openModal(proj.title, `
        <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <img src="${driveUrl(proj.driveId, 1000)}" data-drive-id="${proj.driveId}" alt="${proj.title}" class="w-full h-full object-cover drive-img" />
        </div>
        <div class="text-xs font-semibold text-brand-gold"><i class="fa-solid fa-location-dot mr-1"></i>Địa điểm: ${proj.location}</div>
        <p class="text-sm text-slate-600 leading-relaxed">${proj.summary}</p>
        <div class="pt-1 flex flex-wrap gap-2.5">
          <button type="button" onclick="requestProductQuote('Thi công công trình tương tự ${proj.title}')" class="flex-1 py-2.5 px-4 rounded-lg bg-brand-navy hover:bg-brand-dark text-white font-bold text-sm transition">
            Liên Hệ Thi Công Công Trình
          </button>
        </div>
      `);
    }

    function openNewsDetail(idx) {
      const post = newsData[idx];
      if (!post) return;
      openModal(post.title, `
        <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
          <img src="${driveUrl(post.driveId, 900)}" data-drive-id="${post.driveId}" alt="${post.title}" class="w-full h-full object-cover drive-img" />
        </div>
        <div class="text-xs text-slate-400">Đăng ngày: ${post.date} • Gia Hưng Window Đà Nẵng</div>
        <p class="text-sm text-slate-700 leading-relaxed">${post.content}</p>
        <div class="p-3.5 rounded-xl bg-brand-light text-xs sm:text-sm text-slate-700">
          Quý khách cần tư vấn kỹ thuật trực tiếp vui lòng gọi <strong>0965.656.469</strong> hoặc ghé xưởng sản xuất tại <strong>Thôn Phú Thượng, Hòa Vang, Đà Nẵng</strong>.
        </div>
      `);
    }

    /**
     * SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
     */
    let currentSlide = 0;
    const totalSlides = 2;
    let slideTimer = null;

    function updateSlideUI() {
      const slides = document.querySelectorAll('#heroSlider .hero-slide-item');
      slides.forEach((slide, index) => {
        if (index === currentSlide) {
          slide.classList.remove('hero-slide-hidden');
          slide.classList.add('hero-slide-active');
        } else {
          slide.classList.remove('hero-slide-active');
          slide.classList.add('hero-slide-hidden');
        }
      });

      for (let i = 0; i < totalSlides; i++) {
        const dot = document.getElementById(`dot-${i}`);
        if (dot) {
          dot.className = i === currentSlide
            ? 'w-6 h-2 rounded-full bg-brand-gold transition-all'
            : 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
        }
      }
    }

    function nextSlide() {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateSlideUI();
      resetSlideTimer();
    }

    function prevSlide() {
      currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      updateSlideUI();
      resetSlideTimer();
    }

    function goToSlide(index) {
      currentSlide = index;
      updateSlideUI();
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideTimer) clearInterval(slideTimer);
      slideTimer = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateSlideUI();
      }, 5500);
    }

    /**
     * MENU MOBILE & ACCORDION
     */
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenuDrawer = document.getElementById('mobileMenuDrawer');

    mobileMenuBtn.addEventListener('click', () => {
      mobileMenuDrawer.classList.toggle('hidden');
    });

    function closeMobileMenu() {
      mobileMenuDrawer.classList.add('hidden');
    }

    function toggleMobileSub(subId, iconId) {
      const sub = document.getElementById(subId);
      const icon = document.getElementById(iconId);
      sub.classList.toggle('hidden');
      icon.classList.toggle('rotate-180');
    }

    /**
     * THÔNG BÁO TOAST & XỬ LÝ FORM YÊU CẦU BÁO GIÁ
     */
    let toastTimeout = null;
    function showToast(msg) {
      const box = document.getElementById('toastBox');
      document.getElementById('toastMessage').textContent = msg;
      box.classList.remove('hidden');
      if (toastTimeout) clearTimeout(toastTimeout);
      toastTimeout = setTimeout(() => {
        box.classList.add('hidden');
      }, 4500);
    }

    document.getElementById('quoteForm').addEventListener('submit', function (e) {
      e.preventDefault();
      const name = document.getElementById('customerName').value.trim();
      const phone = document.getElementById('customerPhone').value.trim();
      const category = document.getElementById('customerCategory').value;

      if (!name || !phone) {
        showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Gia Hưng Window liên hệ báo giá.');
        return;
      }

      showToast(`Cảm ơn ${name}! Yêu cầu báo giá "${category}" đã được ghi nhận. Chúng tôi sẽ gọi lại số ${phone} trong ít phút.`);
      this.reset();
    });

    // Đóng modal khi bấm nền tối hoặc phím ESC
    document.getElementById('detailModal').addEventListener('click', function (e) {
      if (e.target === this) closeModal();
    });
    document.addEventListener('keydown', function (e) {
      if (e.key === 'Escape') closeModal();
    });

    // Hỗ trợ vuốt cảm ứng (Swipe) trên banner điện thoại
    let touchStartX = 0;
    const heroSliderEl = document.getElementById('heroSlider');
    heroSliderEl.addEventListener('touchstart', (e) => {
      touchStartX = e.changedTouches[0].screenX;
    }, { passive: true });
    heroSliderEl.addEventListener('touchend', (e) => {
      const diff = e.changedTouches[0].screenX - touchStartX;
      if (Math.abs(diff) > 45) {
        if (diff < 0) nextSlide();
        else prevSlide();
      }
    }, { passive: true });

    // Khởi chạy toàn bộ nội dung khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderCategories();
      renderProducts('all');
      renderProjects();
      renderNews();
      renderPartners();
      bindImageFallbacks();
      resetSlideTimer();
    });
  </script>
</body>
</html>
