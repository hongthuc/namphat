<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>NAM PHÁT - Công Ty TNHH Thương Mại Xây Dựng Và Cơ Khí Nam Phát | namphat.com</title>
  <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT chuyên Thiết kế - Thi công Xây dựng - Gia công Cơ khí & Kết cấu thép uy tín tại Đà Nẵng. Địa chỉ: 78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng. Hotline: 0916.193.575">

  <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://namphat.com/">
  <meta property="og:site_name" content="namphat.com - Xây Dựng & Cơ Khí Nam Phát">
  <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT">
  <meta property="og:description" content="Chuyên Thiết kế - Thi công Xây dựng - Nội thất - Gia công Cơ khí & Kết cấu thép tại Đà Nẵng. Hotline: 0916.193.575">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w1200">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT - namphat.com">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w1200">

  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brandBlue: '#0d3b66',
            brandBlueDark: '#082542',
            brandBlueLight: '#175691',
            brandGold: '#e67e22',
            brandGoldHover: '#d35400',
            brandBg: '#f8fafc'
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            heading: ['Montserrat', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền, không lệch phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      padding-left: 12px;
      padding-right: 12px;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95vw;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Danh mục trên máy tính: viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng từng mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 4px 14px;
      list-style: none;
      margin: 0;
      padding: 0;
    }
    .desktop-nav-item {
      white-space: nowrap;
      font-size: 12.5px;
      font-weight: 600;
      line-height: 1.8;
      letter-spacing: -0.01em;
      transition: color 0.2s ease;
    }

    /* Danh mục lọc ở trang chủ nhỏ gọn, không xuống dòng chữ bên trong */
    .category-pill {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      padding: 6px 12px;
      border-radius: 6px;
      transition: all 0.2s ease;
      cursor: pointer;
      border: 1px solid #cbd5e1;
      background: #ffffff;
      color: #0d3b66;
    }
    .category-pill.active, .category-pill:hover {
      background: #0d3b66;
      color: #ffffff;
      border-color: #0d3b66;
    }

    /* Tên sản phẩm đầy đủ, không bị cắt chữ hay tràn ra ngoài */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.4;
    }

    /* Tiêu đề Section chuẩn Flatsome UX Builder */
    .section-title-wrap {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 1.5rem;
      width: 100%;
    }
    .section-title-line {
      flex: 1;
      height: 2px;
      background-color: #e2e8f0;
    }
    .section-title-text {
      padding: 0 16px;
      font-family: 'Montserrat', sans-serif;
      font-weight: 800;
      text-transform: uppercase;
      color: #0d3b66;
      text-align: center;
    }

    /* Hiệu ứng mượt cho slider banner */
    .banner-slide {
      display: none;
      animation: fadeSlide 0.5s ease-in-out;
    }
    .banner-slide.active {
      display: block;
    }
    @keyframes fadeSlide {
      from { opacity: 0.4; }
      to { opacity: 1; }
    }

    /* Nút nổi liên hệ góc màn hình */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 126, 34, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(230, 126, 34, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 126, 34, 0); }
    }
    .floating-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800">

  <!-- ================= TOP BAR (CHUẨN FLATSOME) ================= -->
  <div class="bg-brandBlueDark text-white text-xs py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 truncate">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brandGold"></i>
          <span>78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-block text-white/30">|</span>
        <span class="hidden md:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-brandGold"></i>
          <span>Website: namphat.com</span>
        </span>
      </div>
      <div class="flex items-center gap-3 ml-auto">
        <a href="tel:0916193575" class="hover:text-brandGold transition flex items-center gap-1 font-medium">
          <i class="fa-solid fa-phone-volume text-brandGold"></i>
          <span>0916.193.575</span>
        </a>
        <span class="text-white/30">|</span>
        <a href="https://www.facebook.com/matcam.gjak/" target="_blank" rel="noopener noreferrer" class="hover:text-brandGold transition flex items-center gap-1">
          <i class="fa-brands fa-facebook text-brandGold"></i>
          <span>Fanpage Nam Phát</span>
        </a>
      </div>
    </div>
  </div>

  <!-- ================= HEADER (LOGO NHỎ GỌN + MENU 1 HÀNG, KHÔNG CÓ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
    <div class="flatsome-container py-2.5">
      <div class="flex items-center justify-between gap-3">
        
        <!-- Logo thiết kế mới chuyên nghiệp, chỉnh gọn nhỏ lại -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
          <div class="w-10 h-10 rounded-lg bg-brandBlue flex items-center justify-center shadow-sm border border-brandGold/40 shrink-0">
            <!-- SVG Logo Nam Phát: Biểu tượng Mái Công Trình Xây Dựng + Bánh Răng Cơ Khí Chính Xác -->
            <svg class="w-7 h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <!-- Vòng bánh răng cơ khí bên ngoài -->
              <path d="M32 6L35.5 10.5L41 9L42.5 14.5L48 15.5L47 21L52 24.5L49 29.5L52 34.5L47 38L48 43.5L42.5 44.5L41 50L35.5 48.5L32 53L28.5 48.5L23 50L21.5 44.5L16 43.5L17 38L12 34.5L15 29.5L12 24.5L17 21L16 15.5L21.5 14.5L23 9L28.5 10.5L32 6Z" stroke="#e67e22" stroke-width="2.5" stroke-linejoin="round"/>
              <!-- Khối tòa nhà & khung thép xây dựng bên trong -->
              <path d="M22 42V24L32 17L42 24V42H22Z" fill="#0d3b66" stroke="#ffffff" stroke-width="2"/>
              <path d="M27 42V29H37V42" stroke="#e67e22" stroke-width="2.5"/>
              <path d="M18 42H46" stroke="#ffffff" stroke-width="2.5" stroke-linecap="round"/>
            </svg>
          </div>
          <div class="leading-tight">
            <div class="flex items-center gap-1.5">
              <span class="font-heading font-extrabold text-base sm:text-lg tracking-tight text-brandBlue">NAM PHÁT</span>
              <span class="text-[10px] font-bold px-1.5 py-0.5 rounded bg-brandGold/15 text-brandGold border border-brandGold/30">namphat.com</span>
            </div>
            <p class="text-[10px] sm:text-[11px] font-semibold text-slate-600 uppercase tracking-tight">Xây Dựng &amp; Cơ Khí Chuyên Nghiệp</p>
          </div>
        </a>

        <!-- Menu Danh Mục Máy Tính: Viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng chữ từng danh mục -->
        <nav class="hidden lg:block flex-1 px-2" aria-label="Menu chính trên máy tính">
          <ul class="desktop-nav-list">
            <li><a href="#trang-chu" class="desktop-nav-item text-brandGold hover:text-brandBlue">TRANG CHỦ</a></li>
            <li><a href="#gioi-thieu" class="desktop-nav-item text-slate-700 hover:text-brandGold">GIỚI THIỆU</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="desktop-nav-item text-slate-700 hover:text-brandGold">LĨNH VỰC HOẠT ĐỘNG</a></li>
            <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item text-slate-700 hover:text-brandGold">CÔNG TRÌNH THỰC TẾ</a></li>
            <li><a href="#san-pham-co-khi" class="desktop-nav-item text-slate-700 hover:text-brandGold">SẢN PHẨM &amp; CƠ KHÍ</a></li>
            <li><a href="#mau-thiet-ke" class="desktop-nav-item text-slate-700 hover:text-brandGold">MẪU THIẾT KẾ</a></li>
            <li><a href="#du-an-da-nang" class="desktop-nav-item text-slate-700 hover:text-brandGold">DỰ ÁN ĐÀ NẴNG</a></li>
            <li><a href="#bang-bao-gia" class="desktop-nav-item text-slate-700 hover:text-brandGold">BÁO GIÁ</a></li>
            <li><a href="#tin-tuc" class="desktop-nav-item text-slate-700 hover:text-brandGold">TIN TỨC</a></li>
            <li><a href="#lien-he-bao-gia" class="desktop-nav-item text-slate-700 hover:text-brandGold">LIÊN HỆ</a></li>
          </ul>
        </nav>

        <!-- Nút mở Menu trên Điện Thoại (Không để nút Gọi ngay trên Header để tránh tràn viền) -->
        <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center p-2 rounded-lg border border-slate-200 text-brandBlue hover:bg-slate-100 focus:outline-none">
          <i id="mobileMenuIcon" class="fa-solid fa-bars text-lg"></i>
          <span class="ml-1.5 text-xs font-bold">DANH MỤC</span>
        </button>

      </div>

      <!-- Thanh Danh Mục Nhanh Trên Điện Thoại (Vuốt ngang gọn đẹp, không tràn viền) -->
      <div class="lg:hidden mt-2 pt-2 border-t border-slate-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
        <a href="#trang-chu" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-brandBlue text-white">Trang chủ</a>
        <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Lĩnh vực</a>
        <a href="#cong-trinh-thuc-te" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Dự án Đà Nẵng</a>
        <a href="#bang-bao-gia" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Báo giá</a>
        <a href="#lien-he-bao-gia" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-slate-700">Liên hệ</a>
      </div>

      <!-- Menu Xổ Xuống Chi Tiết Trên Điện Thoại -->
      <div id="mobileMenuDropdown" class="hidden lg:hidden mt-2 pt-2 border-t border-slate-200 bg-white rounded-lg">
        <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
          <a href="#trang-chu" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-house mr-1.5 text-brandGold"></i>Trang chủ</a>
          <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-building mr-1.5 text-brandGold"></i>Giới thiệu</a>
          <a href="#linh-vuc-hoat-dong" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-helmet-safety mr-1.5 text-brandGold"></i>Lĩnh vực hoạt động</a>
          <a href="#cong-trinh-thuc-te" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-city mr-1.5 text-brandGold"></i>Công trình thực tế</a>
          <a href="#san-pham-co-khi" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-gears mr-1.5 text-brandGold"></i>Sản phẩm &amp; Cơ khí</a>
          <a href="#mau-thiet-ke" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-compass-drafting mr-1.5 text-brandGold"></i>Mẫu thiết kế</a>
          <a href="#du-an-da-nang" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-location-dot mr-1.5 text-brandGold"></i>Dự án Đà Nẵng</a>
          <a href="#bang-bao-gia" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-file-invoice-dollar mr-1.5 text-brandGold"></i>Bảng báo giá</a>
          <a href="#tin-tuc" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-newspaper mr-1.5 text-brandGold"></i>Tin tức xây dựng</a>
          <a href="#lien-he-bao-gia" class="mobile-nav-link px-3 py-2 rounded bg-slate-50 text-brandBlue hover:bg-brandBlue hover:text-white"><i class="fa-solid fa-envelope-open-text mr-1.5 text-brandGold"></i>Yêu cầu báo giá</a>
        </div>
      </div>
    </div>
  </header>

  <!-- ================= HERO BANNER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU, THIẾT KẾ RIÊNG Biệt CHO MÁY TÍNH & ĐIỆN THOẠI) ================= -->
  <section id="trang-chu" class="py-3">
    <div class="flatsome-container">
      <div class="relative rounded-xl overflow-hidden shadow-md border border-slate-200 bg-brandBlueDark">

        <!-- ================= SLIDE 1 ================= -->
        <div class="banner-slide active" data-slide="0">
          <!-- Bố cục Banner 1 dành riêng cho MÁY TÍNH (Chữ gọn trong khung, kích thước cố định 400px bằng nhau) -->
          <div class="hidden md:grid md:grid-cols-12 h-[400px] w-full relative overflow-hidden bg-gradient-to-r from-brandBlueDark via-brandBlue to-brandBlueLight">
            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 z-10">
              <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brandGold/20 border border-brandGold/40 text-brandGold text-xs font-bold w-fit mb-2.5">
                <i class="fa-solid fa-certificate"></i>
                <span>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT</span>
              </div>
              <h1 class="font-heading font-extrabold text-white text-xl lg:text-2xl xl:text-3xl leading-snug mb-2.5">
                THIẾT KẾ - THI CÔNG XÂY DỰNG &amp; GIA CÔNG KẾT CẤU CƠ KHÍ TRỌN GÓI
              </h1>
              <p class="text-slate-200 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                Chuyên thi công Khách sạn, Biệt thự, Nhà phố, Văn phòng, Nhà thép tiền chế &amp; Gia công cơ khí chính xác tại Đà Nẵng. Cam kết: <strong class="text-brandGold">An Toàn – Chất Lượng – Đúng Tiến Độ</strong>.
              </p>
              <div class="flex flex-wrap items-center gap-3 text-xs">
                <a href="#lien-he-bao-gia" class="px-4 py-2.5 rounded-lg bg-brandGold hover:bg-brandGoldHover text-white font-bold transition shadow">
                  <i class="fa-solid fa-calculator mr-1.5"></i>NHẬN BÁO GIÁ MIỄN PHÍ
                </a>
                <a href="#cong-trinh-thuc-te" class="px-4 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white font-semibold border border-white/25 transition">
                  <i class="fa-solid fa-images mr-1.5"></i>XEM 16+ HẠNG MỤC THỰC TẾ
                </a>
              </div>
              <div class="mt-4 pt-3 border-t border-white/15 flex items-center gap-5 text-[11px] text-slate-200">
                <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>78 Nguyễn Đình, P. An Hải, TP Đà Nẵng</span>
                <span><i class="fa-solid fa-phone text-brandGold mr-1"></i>Hotline: 0916.193.575</span>
              </div>
            </div>
            <div class="col-span-5 relative h-full overflow-hidden">
              <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w1000"
                   onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w1000';"
                   alt="Công trình xây dựng và cơ khí Nam Phát"
                   class="w-full h-full object-cover object-center opacity-90">
              <div class="absolute inset-0 bg-gradient-to-r from-brandBlue via-brandBlue/30 to-transparent"></div>
            </div>
          </div>

          <!-- Bố cục Banner 1 thiết kế mới dành riêng cho ĐIỆN THOẠI (Chữ thu nhỏ nằm gọn 100% trong ảnh banner, chiều cao cố định 290px) -->
          <div class="md:hidden relative h-[290px] w-full overflow-hidden bg-brandBlueDark flex flex-col justify-between p-4">
            <img src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800';"
                 alt="Banner Mobile Nam Phát 1"
                 class="absolute inset-0 w-full h-full object-cover opacity-30">
            <div class="absolute inset-0 bg-gradient-to-b from-brandBlueDark/90 via-brandBlueDark/80 to-brandBlueDark/95"></div>

            <div class="relative z-10">
              <span class="inline-block px-2 py-0.5 rounded bg-brandGold text-white text-[10px] font-bold uppercase">
                namphat.com • Đà Nẵng
              </span>
              <h2 class="font-heading font-extrabold text-white text-sm leading-snug mt-1.5">
                CÔNG TY TNHH TM XÂY DỰNG &amp; CƠ KHÍ NAM PHÁT
              </h2>
              <p class="text-slate-200 text-[11px] leading-normal mt-1">
                Thiết kế &amp; Thi công Nhà phố, Biệt thự, Khách sạn, Nhà xưởng kết cấu thép và Gia công cơ khí trọn gói tại Đà Nẵng.
              </p>
            </div>

            <div class="relative z-10 bg-white/10 backdrop-blur-sm rounded-lg p-2.5 border border-white/15 text-[11px] text-white space-y-1">
              <div class="truncate"><i class="fa-solid fa-location-dot text-brandGold mr-1.5"></i>78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng</div>
              <div class="flex items-center justify-between pt-1">
                <span class="font-bold text-brandGold"><i class="fa-solid fa-phone mr-1"></i>0916.193.575</span>
                <a href="#lien-he-bao-gia" class="px-2.5 py-1 rounded bg-brandGold text-white text-[10px] font-bold">Báo giá ngay</a>
              </div>
            </div>
          </div>
        </div>

        <!-- ================= SLIDE 2 (KÍCH THƯỚC BẰNG HỆT SLIDE 1) ================= -->
        <div class="banner-slide" data-slide="1">
          <!-- Bố cục Banner 2 dành riêng cho MÁY TÍNH (Chiều cao 400px bằng Slide 1) -->
          <div class="hidden md:grid md:grid-cols-12 h-[400px] w-full relative overflow-hidden bg-gradient-to-r from-slate-900 via-brandBlueDark to-brandBlue">
            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 z-10">
              <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brandGold/20 border border-brandGold/40 text-brandGold text-xs font-bold w-fit mb-2.5">
                <i class="fa-solid fa-gears"></i>
                <span>NHÀ XƯỞNG TIỀN CHẾ - CƠ KHÍ XÂY DỰNG - NỘI NGOẠI THẤT</span>
              </div>
              <h2 class="font-heading font-extrabold text-white text-xl lg:text-2xl xl:text-3xl leading-snug mb-2.5">
                GIẢI PHÁP CƠ KHÍ &amp; KẾT CẤU THÉP BỀN VỮNG CHO MỌI CÔNG TRÌNH
              </h2>
              <p class="text-slate-200 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                Gia công lắp dựng khung kèo thép, mái tôn, cổng cửa sắt mỹ thuật CNC, cầu thang, lan can và cung ứng vật tư cơ khí xây dựng đạt chuẩn kỹ thuật cao.
              </p>
              <div class="flex flex-wrap items-center gap-3 text-xs">
                <a href="#san-pham-co-khi" class="px-4 py-2.5 rounded-lg bg-brandGold hover:bg-brandGoldHover text-white font-bold transition shadow">
                  <i class="fa-solid fa-screwdriver-wrench mr-1.5"></i>DANH MỤC SẢN PHẨM CƠ KHÍ
                </a>
                <a href="#du-an-da-nang" class="px-4 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white font-semibold border border-white/25 transition">
                  <i class="fa-solid fa-map-location-dot mr-1.5"></i>DỰ ÁN TẠI ĐÀ NẴNG
                </a>
              </div>
              <div class="mt-4 pt-3 border-t border-white/15 flex items-center gap-5 text-[11px] text-slate-200">
                <span><i class="fa-solid fa-shield-halved text-brandGold mr-1"></i>Bảo hành kết cấu dài hạn</span>
                <span><i class="fa-solid fa-headset text-brandGold mr-1"></i>Tư vấn khảo sát tận nơi 24/7: 0916.193.575</span>
              </div>
            </div>
            <div class="col-span-5 relative h-full overflow-hidden">
              <img src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW=w1000"
                   onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w1000';"
                   alt="Gia công cơ khí và thi công xây dựng Nam Phát"
                   class="w-full h-full object-cover object-center opacity-90">
              <div class="absolute inset-0 bg-gradient-to-r from-brandBlueDark via-brandBlueDark/30 to-transparent"></div>
            </div>
          </div>

          <!-- Bố cục Banner 2 thiết kế mới dành riêng cho ĐIỆN THOẠI (Chiều cao 290px bằng Slide 1) -->
          <div class="md:hidden relative h-[290px] w-full overflow-hidden bg-slate-900 flex flex-col justify-between p-4">
            <img src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800';"
                 alt="Banner Mobile Nam Phát 2"
                 class="absolute inset-0 w-full h-full object-cover opacity-30">
            <div class="absolute inset-0 bg-gradient-to-b from-slate-900/90 via-brandBlueDark/85 to-slate-900/95"></div>

            <div class="relative z-10">
              <span class="inline-block px-2 py-0.5 rounded bg-brandGold text-white text-[10px] font-bold uppercase">
                Gia Công Cơ Khí &amp; Kết Cấu Thép
              </span>
              <h2 class="font-heading font-extrabold text-white text-sm leading-snug mt-1.5">
                THI CÔNG NHÀ XƯỞNG &amp; CƠ KHÍ DÂN DỤNG ĐÀ NẴNG
              </h2>
              <p class="text-slate-200 text-[11px] leading-normal mt-1">
                Chuyên gia công khung thép tiền chế, mái kính, cổng sắt CNC, lan can cầu thang và xây dựng trọn gói tối ưu chi phí.
              </p>
            </div>

            <div class="relative z-10 bg-white/10 backdrop-blur-sm rounded-lg p-2.5 border border-white/15 text-[11px] text-white space-y-1">
              <div class="truncate"><i class="fa-solid fa-check-circle text-brandGold mr-1.5"></i>Khảo sát &amp; Báo giá tận nơi miễn phí 24/7</div>
              <div class="flex items-center justify-between pt-1">
                <span class="font-bold text-brandGold"><i class="fa-solid fa-phone mr-1"></i>0916.193.575</span>
                <a href="#cong-trinh-thuc-te" class="px-2.5 py-1 rounded bg-brandBlueLight text-white text-[10px] font-bold">Xem công trình</a>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng 2 Banner tự trượt -->
        <button id="prevBannerBtn" type="button" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-brandGold text-white flex items-center justify-center transition z-20">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button id="nextBannerBtn" type="button" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-brandGold text-white flex items-center justify-center transition z-20">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button type="button" class="banner-dot w-6 h-2 rounded-full bg-brandGold transition-all" data-dot="0" aria-label="Banner 1"></button>
          <button type="button" class="banner-dot w-2 h-2 rounded-full bg-white/60 transition-all" data-dot="1" aria-label="Banner 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- ================= DỊCH VỤ & LĨNH VỰC HOẠT ĐỘNG (THEO MẪU TINTRUONGTHINH.COM) ================= -->
  <section id="linh-vuc-hoat-dong" class="py-6">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">LĨNH VỰC HOẠT ĐỘNG CHÍNH</h2>
        <div class="section-title-line"></div>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính, không dán nhãn đè lên ảnh -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm hover:shadow-md transition flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brandBlue/10 text-brandBlue flex items-center justify-center mb-3">
              <i class="fa-solid fa-compass-drafting text-xl"></i>
            </div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-1.5 product-title-full">
              THIẾT KẾ KIẾN TRÚC &amp; NỘI THẤT
            </h3>
            <p class="text-slate-600 text-xs leading-relaxed">
              Tư vấn thiết kế bản vẽ kiến trúc, kết cấu, điện nước ME và phối cảnh 3D nội ngoại thất cho Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng.
            </p>
          </div>
          <a href="#lien-he-bao-gia" class="mt-3 inline-flex items-center text-xs font-bold text-brandGold hover:underline">
            Nhận tư vấn thiết kế <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
          </a>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm hover:shadow-md transition flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brandGold/15 text-brandGold flex items-center justify-center mb-3">
              <i class="fa-solid fa-trowel-bricks text-xl"></i>
            </div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-1.5 product-title-full">
              THI CÔNG PHẦN THÔ &amp; TRỌN GÓI
            </h3>
            <p class="text-slate-600 text-xs leading-relaxed">
              Thi công xây dựng phần thô, thi công hoàn thiện chìa khóa trao tay các công trình dân dụng, thương mại tại Đà Nẵng đúng tiến độ cam kết.
            </p>
          </div>
          <a href="#bang-bao-gia" class="mt-3 inline-flex items-center text-xs font-bold text-brandGold hover:underline">
            Xem đơn giá thi công <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
          </a>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm hover:shadow-md transition flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brandBlue/10 text-brandBlue flex items-center justify-center mb-3">
              <i class="fa-solid fa-gears text-xl"></i>
            </div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-1.5 product-title-full">
              GIA CÔNG CƠ KHÍ &amp; KẾT CẤU THÉP
            </h3>
            <p class="text-slate-600 text-xs leading-relaxed">
              Sản xuất, gia công và lắp dựng nhà xưởng thép tiền chế, mái tôn, mái kính, cổng cửa sắt CNC, cầu thang, lan can inox – sắt mỹ thuật.
            </p>
          </div>
          <a href="#san-pham-co-khi" class="mt-3 inline-flex items-center text-xs font-bold text-brandGold hover:underline">
            Xem hạng mục cơ khí <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
          </a>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm hover:shadow-md transition flex flex-col justify-between">
          <div>
            <div class="w-11 h-11 rounded-lg bg-brandGold/15 text-brandGold flex items-center justify-center mb-3">
              <i class="fa-solid fa-couch text-xl"></i>
            </div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-1.5 product-title-full">
              THI CÔNG NỘI THẤT &amp; CẢI TẠO
            </h3>
            <p class="text-slate-600 text-xs leading-relaxed">
              Thi công hoàn thiện nội thất gỗ công nghiệp, nhôm kính, cơ khí nội thất và sửa chữa, nâng tầng, cải tạo nhà ở, văn phòng, showroom.
            </p>
          </div>
          <a href="#cong-trinh-thuc-te" class="mt-3 inline-flex items-center text-xs font-bold text-brandGold hover:underline">
            Xem dự án hoàn thiện <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH (THEO MẪU TINTRUONGTHINH.COM) ================= -->
  <section id="gioi-thieu" class="py-6 bg-white border-y border-slate-200">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        <!-- Cột thông tin Giới thiệu -->
        <div class="lg:col-span-5 space-y-3">
          <p class="text-xs font-bold uppercase tracking-wider text-brandGold">Về chúng tôi • namphat.com</p>
          <h2 class="font-heading font-extrabold text-brandBlue text-base sm:text-xl leading-snug">
            CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT
          </h2>
          <p class="text-slate-600 text-xs sm:text-sm leading-relaxed">
            <strong>NAM PHÁT</strong> chuyên Thiết kế – Thi công Xây dựng – Nội thất và Gia công Cơ khí Kết cấu thép cho các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố và Nhà xưởng tại khu vực TP Đà Nẵng &amp; miền Trung.
          </p>
          <p class="text-slate-600 text-xs sm:text-sm leading-relaxed">
            Đặt chữ <strong>“TÂM”</strong> và tiêu chuẩn kỹ thuật lên hàng đầu, mỗi công trình do Nam Phát thực hiện đều hướng tới 4 giá trị cốt lõi: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>.
          </p>
          <div class="bg-slate-50 p-3.5 rounded-xl border border-slate-200 text-xs space-y-1.5">
            <div><strong class="text-brandBlue">Tên doanh nghiệp:</strong> CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT</div>
            <div><strong class="text-brandBlue">Mã số thuế:</strong> 0402260375</div>
            <div><strong class="text-brandBlue">Trụ sở chính:</strong> 78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng</div>
            <div><strong class="text-brandBlue">Điện thoại / Zalo:</strong> <a href="tel:0916193575" class="text-brandGold font-bold">0916.193.575</a></div>
            <div><strong class="text-brandBlue">Website:</strong> namphat.com</div>
          </div>
        </div>

        <!-- Cột 6 Thế mạnh của Nam Phát (giống bố cục Thế mạnh của chúng tôi trên web mẫu) -->
        <div class="lg:col-span-7">
          <div class="grid grid-cols-2 sm:grid-cols-3 gap-3">
            <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200">
              <i class="fa-solid fa-user-tie text-brandGold text-lg mb-2"></i>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm mb-1 product-title-full">Đội ngũ KTS &amp; Kỹ sư giỏi</h3>
              <p class="text-slate-600 text-[11px] leading-relaxed">Kỹ sư xây dựng và thợ cơ khí lành nghề, giàu kinh nghiệm thực chiến tại Đà Nẵng.</p>
            </div>
            <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200">
              <i class="fa-solid fa-microchip text-brandGold text-lg mb-2"></i>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm mb-1 product-title-full">Công nghệ thi công hiện đại</h3>
              <p class="text-slate-600 text-[11px] leading-relaxed">Ứng dụng máy móc gia công cơ khí chính xác và vật liệu xây dựng đạt chuẩn.</p>
            </div>
            <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200">
              <i class="fa-solid fa-calendar-check text-brandGold text-lg mb-2"></i>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm mb-1 product-title-full">Giám sát tiến độ chuẩn xác</h3>
              <p class="text-slate-600 text-[11px] leading-relaxed">Báo cáo khối lượng công việc định kỳ, cam kết bàn giao công trình đúng hẹn.</p>
            </div>
            <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200">
              <i class="fa-solid fa-shield-heart text-brandGold text-lg mb-2"></i>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm mb-1 product-title-full">Bảo hành công trình lâu dài</h3>
              <p class="text-slate-600 text-[11px] leading-relaxed">Chế độ hậu mãi tận tâm, bảo hành kết cấu xây dựng và hạng mục cơ khí dài hạn.</p>
            </div>
            <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200">
              <i class="fa-solid fa-hand-holding-dollar text-brandGold text-lg mb-2"></i>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm mb-1 product-title-full">Giá cả hợp lý minh bạch</h3>
              <p class="text-slate-600 text-[11px] leading-relaxed">Dự toán bóc tách chi tiết từng hạng mục, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
            </div>
            <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200">
              <i class="fa-solid fa-headset text-brandGold text-lg mb-2"></i>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm mb-1 product-title-full">Tư vấn miễn phí 24/7</h3>
              <p class="text-slate-600 text-[11px] leading-relaxed">Khảo sát thực tế tại Đà Nẵng và lên phương án thiết kế, báo giá nhanh chóng.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= CÔNG TRÌNH THỰC TẾ & SẢN PHẨM CƠ KHÍ XÂY DỰNG (16 ẢNH THỰC TẾ GOOGLE DRIVE) ================= -->
  <section id="cong-trinh-thuc-te" class="py-7">
    <div id="san-pham-co-khi"></div>
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">SẢN PHẨM CƠ KHÍ &amp; CÔNG TRÌNH THỰC TẾ</h2>
        <div class="section-title-line"></div>
      </div>

      <!-- Thanh lọc danh mục nhỏ gọn, viết liền trên 1 hàng chữ, không bị gãy dòng -->
      <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
        <button type="button" class="category-pill active" data-filter="all">Tất cả (16)</button>
        <button type="button" class="category-pill" data-filter="khach-san-can-ho">Khách sạn – Căn hộ – Phòng trọ</button>
        <button type="button" class="category-pill" data-filter="biet-thu-nha-pho">Biệt thự – Nhà phố</button>
        <button type="button" class="category-pill" data-filter="van-phong-nha-xuong">Văn phòng – Nhà xưởng tiền chế</button>
        <button type="button" class="category-pill" data-filter="co-khi-ket-cau">Gia công Cơ khí – Kết cấu thép</button>
      </div>

      <!-- Lưới sản phẩm / công trình: Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính, KHÔNG ĐỂ NHÃN DÁN, tên đầy đủ không cắt chữ -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Tự động render từ mảng 16 ảnh thực tế Google Drive bên dưới bằng JS để code gọn sạch, dễ chuyển qua UX Builder -->
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC MẪU THIẾT KẾ (THEO WEB MẪU TINTRUONGTHINH.COM) ================= -->
  <section id="mau-thiet-ke" class="py-6 bg-white border-y border-slate-200">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">MẪU THIẾT KẾ KIẾN TRÚC &amp; BẢN VẼ CƠ KHÍ</h2>
        <div class="section-title-line"></div>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w800';"
                 alt="Mẫu thiết kế nhà phố hiện đại Đà Nẵng"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Mẫu Thiết Kế Nhà Phố Hiện Đại 3 Tầng Mặt Tiền 5m
              </h3>
              <p class="text-slate-600 text-[11px] mt-1">Bố trí công năng thông thoáng, kết hợp hệ lam sắt cơ khí thẩm mỹ cao.</p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-2.5 text-[11px] font-bold text-brandGold hover:underline">Nhận bản vẽ tham khảo →</a>
          </div>
        </div>

        <div class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800';"
                 alt="Mẫu thiết kế biệt thự và căn hộ cho thuê"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Mẫu Thiết Kế Căn Hộ Dịch Vụ &amp; Khách Sạn Mini
              </h3>
              <p class="text-slate-600 text-[11px] mt-1">Giải pháp tối ưu diện tích khai thác phòng cho thuê tại khu vực biển Sơn Trà – An Hải.</p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-2.5 text-[11px] font-bold text-brandGold hover:underline">Nhận bản vẽ tham khảo →</a>
          </div>
        </div>

        <div class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ng7_50Be4LsQqNa28KBn8rSCicz40ir9&sz=w800';"
                 alt="Mẫu thiết kế nhà xưởng khung thép tiền chế"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Mẫu Thiết Kế Nhà Xưởng Khung Thép Tiền Chế &amp; Showroom
              </h3>
              <p class="text-slate-600 text-[11px] mt-1">Kết cấu vượt nhịp lớn, thi công lắp dựng nhanh, tiết kiệm đến 30% chi phí đầu tư.</p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-2.5 text-[11px] font-bold text-brandGold hover:underline">Nhận bản vẽ tham khảo →</a>
          </div>
        </div>

        <div class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w800';"
                 alt="Mẫu thiết kế nội thất và cơ khí hoàn thiện"
                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Mẫu Thiết Kế Nội Thất &amp; Hạng Mục Sắt Mỹ Thuật CNC
              </h3>
              <p class="text-slate-600 text-[11px] mt-1">Phối cảnh đồng bộ giữa không gian nội thất hiện đại và cầu thang, lan can, cổng CNC.</p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-2.5 text-[11px] font-bold text-brandGold hover:underline">Nhận bản vẽ tham khảo →</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC DỰ ÁN TIÊU BIỂU Ở ĐÀ NẴNG ================= -->
  <section id="du-an-da-nang" class="py-7">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">DỰ ÁN THI CÔNG THỰC TẾ TẠI ĐÀ NẴNG</h2>
        <div class="section-title-line"></div>
      </div>

      <p class="text-center text-slate-600 text-xs sm:text-sm max-w-2xl mx-auto mb-5">
        Các dự án xây dựng dân dụng, nhà xưởng kết cấu thép và gia công cơ khí tiêu biểu do <strong>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT</strong> trực tiếp triển khai tại các quận, phường thuộc TP Đà Nẵng.
      </p>

      <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính, không nhãn dán đè lên ảnh -->
      <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w800';"
                 alt="Dự án An Hải Sơn Trà Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Dự Án Thi Công Nhà Phố &amp; Hệ Cổng Mái Cơ Khí – Phường An Hải, TP Đà Nẵng
              </h3>
              <p class="text-slate-600 text-[11px] sm:text-xs mt-1.5 leading-relaxed">
                Hạng mục: Thi công xây dựng trọn gói và lắp đặt toàn bộ hệ cửa cổng sắt CNC, khung bảo vệ, mái kính cường lực.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
              <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>P. An Hải, Đà Nẵng</span>
              <span class="font-semibold text-brandBlue">Hoàn thiện 100%</span>
            </div>
          </div>
        </div>

        <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi&sz=w800';"
                 alt="Dự án căn hộ cho thuê Sơn Trà Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Dự Án Căn Hộ Cho Thuê &amp; Kết Cấu Cầu Thang Thép – Quận Sơn Trà, TP Đà Nẵng
              </h3>
              <p class="text-slate-600 text-[11px] sm:text-xs mt-1.5 leading-relaxed">
                Hạng mục: Thi công phần thô, hoàn thiện nội thất và gia công hệ cầu thang thoát hiểm, lan can ban công sắt sơn tĩnh điện.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
              <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>Sơn Trà, Đà Nẵng</span>
              <span class="font-semibold text-brandBlue">Hoàn thiện 100%</span>
            </div>
          </div>
        </div>

        <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq&sz=w800';"
                 alt="Dự án nhà xưởng Hòa Xuân Cẩm Lệ Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Dự Án Nhà Xưởng Khung Thép Tiền Chế &amp; Kho Bãi – Khu Đô Thị Hòa Xuân, Đà Nẵng
              </h3>
              <p class="text-slate-600 text-[11px] sm:text-xs mt-1.5 leading-relaxed">
                Hạng mục: Gia công lắp dựng cột kèo thép chữ I, lợp tôn chống nóng, hệ thống thông gió và nền bê tông chịu lực.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
              <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>Hòa Xuân, Đà Nẵng</span>
              <span class="font-semibold text-brandBlue">Hoàn thiện 100%</span>
            </div>
          </div>
        </div>

        <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1fqJikC677z_7x28XQaAx3VQD7zqWtiUy=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1fqJikC677z_7x28XQaAx3VQD7zqWtiUy&sz=w800';"
                 alt="Dự án biệt thự Ngũ Hành Sơn Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Dự Án Biệt Thự Nghỉ Dưỡng &amp; Hạng Mục Cơ Khí Ngoại Thất – Ngũ Hành Sơn, Đà Nẵng
              </h3>
              <p class="text-slate-600 text-[11px] sm:text-xs mt-1.5 leading-relaxed">
                Hạng mục: Xây dựng hoàn thiện biệt thự 3 tầng, thi công mái che pergola thép hộp mạ kẽm và cổng tự động.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
              <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>Ngũ Hành Sơn, Đà Nẵng</span>
              <span class="font-semibold text-brandBlue">Hoàn thiện 100%</span>
            </div>
          </div>
        </div>

        <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x&sz=w800';"
                 alt="Dự án văn phòng Hải Châu Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Dự Án Cải Tạo Tòa Nhà Văn Phòng &amp; Mặt Dựng Nhôm Kính – Hải Châu, Đà Nẵng
              </h3>
              <p class="text-slate-600 text-[11px] sm:text-xs mt-1.5 leading-relaxed">
                Hạng mục: Gia cố kết cấu thép cơi nới tầng, lắp đặt vách kính mặt dựng và hoàn thiện nội thất văn phòng làm việc.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
              <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>Hải Châu, Đà Nẵng</span>
              <span class="font-semibold text-brandBlue">Hoàn thiện 100%</span>
            </div>
          </div>
        </div>

        <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ&sz=w800';"
                 alt="Dự án cơ khí tổng hợp Liên Chiểu Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Dự Án Gia Công Lắp Đặt Hệ Thống Mái Tôn &amp; Kết Cấu Nhà Kho – Liên Chiểu, Đà Nẵng
              </h3>
              <p class="text-slate-600 text-[11px] sm:text-xs mt-1.5 leading-relaxed">
                Hạng mục: Chế tạo vì kèo thép, xà gồ mạ kẽm, máng xối inox và thi công chống thấm, lợp tôn công nghiệp.
              </p>
            </div>
            <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
              <span><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>Liên Chiểu, Đà Nẵng</span>
              <span class="font-semibold text-brandBlue">Hoàn thiện 100%</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= BẢNG BÁO GIÁ THAM KHẢO (LẤY DANH MỤC BÁO GIÁ TỪ WEB MẪU TINTRUONGTHINH.COM) ================= -->
  <section id="bang-bao-gia" class="py-7 bg-white border-y border-slate-200">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">BẢNG BÁO GIÁ XÂY DỰNG &amp; CƠ KHÍ NAM PHÁT</h2>
        <div class="section-title-line"></div>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="rounded-xl border border-slate-200 bg-slate-50 p-4 flex flex-col justify-between">
          <div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-2 product-title-full">
              BÁO GIÁ THIẾT KẾ KIẾN TRÚC
            </h3>
            <div class="text-brandGold font-extrabold text-sm sm:text-lg mb-2">120.000đ – 180.000đ/m²</div>
            <ul class="text-slate-600 text-[11px] sm:text-xs space-y-1.5">
              <li>• Hồ sơ bản vẽ kiến trúc &amp; phối cảnh 3D</li>
              <li>• Bản vẽ kết cấu &amp; điện nước ME</li>
              <li>• Miễn phí 100% khi ký HĐ thi công trọn gói</li>
            </ul>
          </div>
          <a href="#lien-he-bao-gia" class="mt-4 block text-center py-2 rounded-lg bg-brandBlue text-white text-xs font-bold hover:bg-brandGold transition">
            Yêu cầu báo giá
          </a>
        </div>

        <div class="rounded-xl border border-slate-200 bg-slate-50 p-4 flex flex-col justify-between">
          <div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-2 product-title-full">
              BÁO GIÁ THI CÔNG PHẦN THÔ
            </h3>
            <div class="text-brandGold font-extrabold text-sm sm:text-lg mb-2">3.500.000đ – 3.900.000đ/m²</div>
            <ul class="text-slate-600 text-[11px] sm:text-xs space-y-1.5">
              <li>• Vật tư chuẩn (Thép Hòa Phát, Xi măng...)</li>
              <li>• Nhân công xây tô, ốp lát, điện nước âm</li>
              <li>• Bảo hành kết cấu công trình lên đến 5 năm</li>
            </ul>
          </div>
          <a href="#lien-he-bao-gia" class="mt-4 block text-center py-2 rounded-lg bg-brandBlue text-white text-xs font-bold hover:bg-brandGold transition">
            Yêu cầu báo giá
          </a>
        </div>

        <div class="rounded-xl border border-slate-200 bg-slate-50 p-4 flex flex-col justify-between">
          <div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-2 product-title-full">
              BÁO GIÁ THI CÔNG TRỌN GÓI
            </h3>
            <div class="text-brandGold font-extrabold text-sm sm:text-lg mb-2">5.500.000đ – 6.800.000đ/m²</div>
            <ul class="text-slate-600 text-[11px] sm:text-xs space-y-1.5">
              <li>• Chìa khóa trao tay từ A - Z</li>
              <li>• Hỗ trợ thủ tục xin phép xây dựng Đà Nẵng</li>
              <li>• Cam kết không phát sinh chi phí</li>
            </ul>
          </div>
          <a href="#lien-he-bao-gia" class="mt-4 block text-center py-2 rounded-lg bg-brandBlue text-white text-xs font-bold hover:bg-brandGold transition">
            Yêu cầu báo giá
          </a>
        </div>

        <div class="rounded-xl border border-slate-200 bg-slate-50 p-4 flex flex-col justify-between">
          <div>
            <h3 class="font-heading font-bold text-brandBlue text-xs sm:text-sm mb-2 product-title-full">
              BÁO GIÁ GIA CÔNG CƠ KHÍ
            </h3>
            <div class="text-brandGold font-extrabold text-sm sm:text-lg mb-2">Theo bản vẽ &amp; khối lượng</div>
            <ul class="text-slate-600 text-[11px] sm:text-xs space-y-1.5">
              <li>• Nhà thép tiền chế, mái tôn, mái kính</li>
              <li>• Cổng sắt CNC, cầu thang, lan can inox</li>
              <li>• Khảo sát đo đạc báo giá trực tiếp tại chỗ</li>
            </ul>
          </div>
          <a href="#lien-he-bao-gia" class="mt-4 block text-center py-2 rounded-lg bg-brandBlue text-white text-xs font-bold hover:bg-brandGold transition">
            Yêu cầu báo giá
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FACEBOOK + GOOGLE MAP NGOÀI TRANG CHỦ ================= -->
  <section id="lien-he-bao-gia" class="py-8 bg-slate-100">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">ĐĂNG KÝ TƯ VẤN &amp; NHẬN BÁO GIÁ MIỄN PHÍ</h2>
        <div class="section-title-line"></div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
        <!-- Cột 1: Form Yêu Cầu Và Báo Giá Trang Chủ (Theo mẫu MIỄN PHÍ TƯ VẤN của tintruongthinh.com) -->
        <div class="lg:col-span-6 bg-white rounded-xl shadow-sm border border-slate-200 p-5 sm:p-6">
          <h3 class="font-heading font-extrabold text-brandBlue text-sm sm:text-base uppercase mb-1">
            GỬI YÊU CẦU BÁO GIÁ XÂY DỰNG &amp; CƠ KHÍ
          </h3>
          <p class="text-slate-600 text-xs mb-4">
            Quý khách vui lòng điền thông tin bên dưới, kỹ sư Nam Phát sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết qua số điện thoại / Zalo trong vòng 15 phút.
          </p>

          <form id="quoteRequestForm" class="space-y-3 text-xs sm:text-sm">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Họ và tên Quý khách *</label>
                <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2.5 rounded-lg border border-slate-300 focus:border-brandBlue focus:outline-none">
              </div>
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input type="tel" id="custPhone" required placeholder="Ví dụ: 0916193575" class="w-full px-3 py-2.5 rounded-lg border border-slate-300 focus:border-brandBlue focus:outline-none">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Loại công trình / Hạng mục</label>
                <select id="projectType" class="w-full px-3 py-2.5 rounded-lg border border-slate-300 focus:border-brandBlue focus:outline-none bg-white">
                  <option value="Nhà phố - Biệt thự trọn gói">Nhà phố – Biệt thự trọn gói</option>
                  <option value="Khách sạn - Căn hộ cho thuê - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                  <option value="Nhà xưởng khung thép tiền chế">Nhà xưởng khung thép tiền chế</option>
                  <option value="Gia công Cơ khí (Cổng CNC, Mái tôn, Cầu thang...)">Gia công Cơ khí (Cổng CNC, Mái tôn, Cầu thang...)</option>
                  <option value="Văn phòng - Cải tạo sửa chữa">Văn phòng – Cải tạo sửa chữa</option>
                </select>
              </div>
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="budgetLevel" class="w-full px-3 py-2.5 rounded-lg border border-slate-300 focus:border-brandBlue focus:outline-none bg-white">
                  <option value="Báo giá theo khối lượng thực tế">Báo giá theo khối lượng thực tế</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                  <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
            </div>

            <div>
              <label class="block font-semibold text-slate-700 mb-1">Địa điểm xây dựng / lắp đặt tại Đà Nẵng</label>
              <input type="text" id="projectLocation" placeholder="Ví dụ: Phường An Hải, Quận Sơn Trà, TP Đà Nẵng..." class="w-full px-3 py-2.5 rounded-lg border border-slate-300 focus:border-brandBlue focus:outline-none">
            </div>

            <div>
              <label class="block font-semibold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
              <textarea id="projectNote" rows="3" placeholder="Nhập diện tích đất, số tầng hoặc hạng mục cơ khí cần báo giá..." class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-brandBlue focus:outline-none"></textarea>
            </div>

            <button type="submit" class="w-full py-3 rounded-lg bg-brandGold hover:bg-brandGoldHover text-white font-heading font-bold text-xs sm:text-sm uppercase tracking-wide transition shadow">
              <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
            </button>

            <div id="formSuccessMessage" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium">
              <!-- Thông báo gửi thành công -->
            </div>
          </form>
        </div>

        <!-- Cột 2: Đưa Facebook Fanpage & Bản Đồ Google Map Ra Ngoài Trang Chủ -->
        <div class="lg:col-span-6 space-y-5">
          
          <!-- Khối Kết Nối Facebook Chính Thức Ngoài Trang Chủ -->
          <div class="bg-white rounded-xl shadow-sm border border-slate-200 p-4 sm:p-5">
            <div class="flex items-center justify-between gap-2 mb-3">
              <div class="flex items-center gap-2.5">
                <div class="w-10 h-10 rounded-full bg-blue-600 text-white flex items-center justify-center shrink-0">
                  <i class="fa-brands fa-facebook-f text-lg"></i>
                </div>
                <div>
                  <h3 class="font-bold text-brandBlue text-xs sm:text-sm">KẾT NỐI FACEBOOK TRANG CHỦ</h3>
                  <p class="text-[11px] text-slate-500">Cập nhật hình ảnh thi công thực tế hàng ngày</p>
                </div>
              </div>
              <a href="https://www.facebook.com/matcam.gjak/" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold shrink-0">
                <i class="fa-brands fa-facebook mr-1"></i>Mở Facebook
              </a>
            </div>
            <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 text-xs space-y-1.5">
              <div class="font-semibold text-brandBlue">CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT</div>
              <div class="text-slate-600 break-all">
                <i class="fa-solid fa-link text-brandGold mr-1"></i>Link Facebook:
                <a href="https://www.facebook.com/matcam.gjak/" target="_blank" rel="noopener noreferrer" class="text-blue-600 font-semibold hover:underline">
                  https://www.facebook.com/matcam.gjak/
                </a>
              </div>
              <div class="text-slate-600">
                <i class="fa-solid fa-phone text-brandGold mr-1"></i>Hotline / Zalo trực tiếp: <strong>0916.193.575</strong>
              </div>
            </div>
          </div>

          <!-- Khối Đưa Ảnh & Bản Đồ Google Map Ra Ngoài Trang Chủ -->
          <div class="bg-white rounded-xl shadow-sm border border-slate-200 p-4 sm:p-5">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
              <div>
                <h3 class="font-bold text-brandBlue text-xs sm:text-sm uppercase">
                  <i class="fa-solid fa-map-location-dot text-brandGold mr-1.5"></i>VỊ TRÍ GOOGLE MAPS TRÊN TRANG CHỦ
                </h3>
                <p class="text-[11px] text-slate-600 mt-0.5">
                  Địa chỉ: <strong>78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng</strong>
                </p>
              </div>
              <a href="https://www.google.com/maps/search/?api=1&query=78+Nguyen+Dinh+An+Hai+Da+Nang" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-brandBlue hover:bg-brandGold text-white text-xs font-bold transition">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường
              </a>
            </div>

            <!-- Bản đồ Google Maps trực quan ngay ngoài trang chủ -->
            <div class="w-full h-56 sm:h-64 rounded-lg overflow-hidden border border-slate-200 relative bg-slate-100">
              <iframe
                title="Bản đồ Google Map 78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng"
                src="https://maps.google.com/maps?q=78%20Nguy%E1%BB%85n%20%C4%90%C3%ACnh,%20An%20H%E1%BA%A3i,%20S%C6%A1n%20Tr%C3%A0,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ (THEO MẪU TINTRUONGTHINH.COM) ================= -->
  <section id="tin-tuc" class="py-7 bg-white border-t border-slate-200">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">TIN TỨC &amp; KINH NGHIỆM XÂY DỰNG – CƠ KHÍ</h2>
        <div class="section-title-line"></div>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw&sz=w800';"
                 alt="Hướng dẫn bảo dưỡng bê tông móng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Hướng dẫn bảo dưỡng bê tông móng và kết cấu thép đúng kỹ thuật
              </h3>
              <p class="text-slate-600 text-[11px] mt-1.5 leading-relaxed">
                Quy trình kiểm tra độ ẩm, bảo dưỡng bê tông móng và sơn chống gỉ kết cấu thép giúp tăng tuổi thọ công trình tại vùng biển Đà Nẵng.
              </p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-3 text-[11px] font-bold text-brandGold hover:underline">Đọc chi tiết →</a>
          </div>
        </article>

        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK&sz=w800';"
                 alt="Kinh nghiệm xây nhà trọn gói Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư cần biết để tránh phát sinh
              </h3>
              <p class="text-slate-600 text-[11px] mt-1.5 leading-relaxed">
                Cách lập bảng dự toán vật tư xây dựng, lựa chọn chủng loại sắt thép và giám sát tiến độ thi công minh bạch ngay từ đầu.
              </p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-3 text-[11px] font-bold text-brandGold hover:underline">Đọc chi tiết →</a>
          </div>
        </article>

        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1&sz=w800';"
                 alt="Ưu điểm nhà thép tiền chế"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Ưu điểm vượt trội khi thi công Nhà xưởng &amp; Quán Cafe bằng khung thép tiền chế
              </h3>
              <p class="text-slate-600 text-[11px] mt-1.5 leading-relaxed">
                Rút ngắn 50% thời gian thi công, dễ dàng tháo lắp mở rộng và tối ưu không gian vượt nhịp lớn cho nhà xưởng, showroom.
              </p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-3 text-[11px] font-bold text-brandGold hover:underline">Đọc chi tiết →</a>
          </div>
        </article>

        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 flex flex-col">
          <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
            <img src="https://lh3.googleusercontent.com/d/1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ=w800"
                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ&sz=w800';"
                 alt="Xu hướng cổng cửa sắt CNC Đà Nẵng"
                 class="w-full h-full object-cover">
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full">
                Xu hướng thiết kế Cổng sắt mỹ thuật CNC &amp; Mái kính cường lực cho Biệt thự, Nhà phố
              </h3>
              <p class="text-slate-600 text-[11px] mt-1.5 leading-relaxed">
                Tổng hợp các mẫu cửa cổng sắt cắt CNC sơn tĩnh điện chống ăn mòn biển, vừa sang trọng vừa đảm bảo an ninh tuyệt đối.
              </p>
            </div>
            <a href="#lien-he-bao-gia" class="mt-3 text-[11px] font-bold text-brandGold hover:underline">Đọc chi tiết →</a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC ================= -->
  <section id="doi-tac" class="py-6 bg-slate-50 border-t border-slate-200">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <div class="section-title-line"></div>
        <h2 class="section-title-text text-base sm:text-xl">ĐỐI TÁC &amp; THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH</h2>
        <div class="section-title-line"></div>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-sm flex flex-col items-center justify-center">
          <span class="font-heading font-extrabold text-brandBlue text-xs sm:text-sm">THÉP HÒA PHÁT</span>
          <span class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng &amp; ống thép</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-sm flex flex-col items-center justify-center">
          <span class="font-heading font-extrabold text-brandGold text-xs sm:text-sm">TÔN HOA SEN</span>
          <span class="text-[11px] text-slate-500 mt-0.5">Tôn lợp &amp; xà gồ mạ kẽm</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-sm flex flex-col items-center justify-center">
          <span class="font-heading font-extrabold text-brandBlue text-xs sm:text-sm">SƠN JOTUN / DULUX</span>
          <span class="text-[11px] text-slate-500 mt-0.5">Sơn công trình &amp; kết cấu</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-sm flex flex-col items-center justify-center">
          <span class="font-heading font-extrabold text-brandGold text-xs sm:text-sm">NHÔM XINGFA</span>
          <span class="text-[11px] text-slate-500 mt-0.5">Hệ nhôm kính cao cấp</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-sm flex flex-col items-center justify-center">
          <span class="font-heading font-extrabold text-brandBlue text-xs sm:text-sm">SIKA VIỆT NAM</span>
          <span class="text-[11px] text-slate-500 mt-0.5">Phụ gia &amp; chống thấm</span>
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3.5 text-center shadow-sm flex flex-col items-center justify-center">
          <span class="font-heading font-extrabold text-brandGold text-xs sm:text-sm">VIGLACERA</span>
          <span class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát &amp; thiết bị</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
  <footer class="bg-brandBlueDark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brandGold">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
        
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded-lg bg-brandGold text-white flex items-center justify-center font-heading font-extrabold text-sm">
              NP
            </div>
            <div>
              <h3 class="font-heading font-extrabold text-white text-sm sm:text-base">
                CÔNG TY TNHH TM XÂY DỰNG &amp; CƠ KHÍ NAM PHÁT
              </h3>
              <p class="text-[11px] text-brandGold font-semibold">Website chính thức: namphat.com</p>
            </div>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed">
            Đơn vị uy tín hàng đầu tại Đà Nẵng trong lĩnh vực Thiết kế Kiến trúc – Thi công Xây dựng trọn gói – Gia công lắp dựng Cơ khí &amp; Kết cấu thép.
          </p>
          <ul class="text-xs space-y-1.5 pt-1">
            <li><i class="fa-solid fa-location-dot text-brandGold mr-2"></i><strong>Trụ sở:</strong> 78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-brandGold mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0916193575" class="text-brandGold font-bold hover:underline">0916.193.575</a></li>
            <li><i class="fa-solid fa-id-card text-brandGold mr-2"></i><strong>Mã số thuế:</strong> 0402260375</li>
            <li><i class="fa-brands fa-facebook text-brandGold mr-2"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/matcam.gjak/" target="_blank" rel="noopener noreferrer" class="hover:underline">facebook.com/matcam.gjak</a></li>
          </ul>
        </div>

        <div class="lg:col-span-3 space-y-2">
          <h4 class="font-heading font-bold text-white text-xs sm:text-sm uppercase border-b border-white/15 pb-2">
            LĨNH VỰC HOẠT ĐỘNG
          </h4>
          <ul class="text-xs space-y-2 text-slate-300">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brandGold">• Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brandGold">• Thi công xây dựng phần thô</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brandGold">• Thi công nhà trọn gói Đà Nẵng</a></li>
            <li><a href="#san-pham-co-khi" class="hover:text-brandGold">• Gia công Cơ khí &amp; Kết cấu thép</a></li>
            <li><a href="#san-pham-co-khi" class="hover:text-brandGold">• Nhà thép tiền chế – Mái tôn – CNC</a></li>
          </ul>
        </div>

        <div class="lg:col-span-4 space-y-2">
          <h4 class="font-heading font-bold text-white text-xs sm:text-sm uppercase border-b border-white/15 pb-2">
            DANH MỤC CÔNG TRÌNH
          </h4>
          <div class="grid grid-cols-2 gap-2 text-xs text-slate-300">
            <a href="#cong-trinh-thuc-te" class="hover:text-brandGold">• Khách sạn – Căn hộ</a>
            <a href="#cong-trinh-thuc-te" class="hover:text-brandGold">• Biệt thự nghỉ dưỡng</a>
            <a href="#cong-trinh-thuc-te" class="hover:text-brandGold">• Nhà phố hiện đại</a>
            <a href="#cong-trinh-thuc-te" class="hover:text-brandGold">• Văn phòng công ty</a>
            <a href="#du-an-da-nang" class="hover:text-brandGold">• Dự án tại Đà Nẵng</a>
            <a href="#bang-bao-gia" class="hover:text-brandGold">• Báo giá thi công</a>
          </div>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-[11px] text-slate-400 gap-2">
        <p>© Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI XÂY DỰNG VÀ CƠ KHÍ NAM PHÁT (namphat.com)</strong>.</p>
        <p>Địa chỉ: 78 Nguyễn Đình, Phường An Hải, TP Đà Nẵng • SĐT: 0916.193.575</p>
      </div>
    </div>
  </footer>

  <!-- ================= NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
  <div class="fixed bottom-4 right-3 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/matcam.gjak/" target="_blank" rel="noopener noreferrer"
       class="flex items-center gap-2 px-3 py-2 rounded-full bg-blue-600 hover:bg-blue-700 text-white shadow-lg border border-white/20 transition">
      <i class="fa-brands fa-facebook-messenger text-base"></i>
      <span class="text-xs font-bold">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0916193575" target="_blank" rel="noopener noreferrer"
       class="flex items-center gap-2 px-3 py-2 rounded-full bg-sky-500 hover:bg-sky-600 text-white shadow-lg border border-white/20 transition">
      <span class="font-heading font-extrabold text-xs bg-white text-sky-600 px-1.5 py-0.5 rounded-full">Zalo</span>
      <span class="text-xs font-bold">Chat Zalo</span>
    </a>

    <!-- Nút Hotline Nổi Bật -->
    <a href="tel:0916193575"
       class="floating-pulse flex items-center gap-2 px-3.5 py-2.5 rounded-full bg-brandGold hover:bg-brandGoldHover text-white shadow-xl border border-white/30 transition">
      <i class="fa-solid fa-phone-volume text-sm"></i>
      <span class="text-xs sm:text-sm font-extrabold tracking-tight">0916.193.575</span>
    </a>
  </div>

  <!-- ================= MODAL XEM CHI TIẾT ẢNH & YÊU CẦU BÁO GIÁ NHANH ================= -->
  <div id="itemModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-4 py-3 bg-brandBlue text-white">
        <h4 id="modalTitle" class="font-bold text-xs sm:text-sm pr-2 product-title-full">Chi tiết hạng mục</h4>
        <button id="closeModalBtn" type="button" class="text-white/80 hover:text-white text-lg leading-none">&times;</button>
      </div>
      <div class="p-4 space-y-3">
        <div class="aspect-[16/10] w-full rounded-lg overflow-hidden bg-slate-100 border border-slate-200">
          <img id="modalImg" src="" alt="Ảnh thực tế công trình Nam Phát" class="w-full h-full object-cover">
        </div>
        <p id="modalDesc" class="text-xs text-slate-600 leading-relaxed"></p>
        <div class="flex flex-wrap items-center justify-between gap-2 pt-2 border-t border-slate-100">
          <a href="tel:0916193575" class="px-3.5 py-2 rounded-lg bg-brandGold text-white text-xs font-bold">
            <i class="fa-solid fa-phone mr-1"></i>Gọi 0916.193.575
          </a>
          <a id="modalQuoteBtn" href="#lien-he-bao-gia" class="px-3.5 py-2 rounded-lg bg-brandBlue text-white text-xs font-bold">
            Đăng ký nhận báo giá hạng mục này
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU 16 ẢNH THỰC TẾ, SLIDER, LỌC DANH MỤC ================= -->
  <script>
    // Danh sách 16 ảnh thực tế từ Google Drive của khách hàng, phân loại đúng vào các danh mục chuẩn của web mẫu & Cơ khí Nam Phát
    const realItemsData = [
      {
        id: '1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk',
        category: 'biet-thu-nha-pho',
        title: 'Thi Công Trọn Gói Nhà Phố Hiện Đại & Hệ Lam Cơ Khí Mặt Tiền Tại Đà Nẵng',
        desc: 'Công trình nhà phố kết hợp hệ khung lam sắt hộp mạ kẽm sơn tĩnh điện và lan can ban công hiện đại.'
      },
      {
        id: '1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW',
        category: 'co-khi-ket-cau',
        title: 'Gia Công Lắp Dựng Kết Cấu Khung Thép & Hệ Mái Che Công Trình Thực Tế',
        desc: 'Hạng mục gia công cơ khí kết cấu thép chịu lực, mối hàn đạt chuẩn kỹ thuật và độ bền cao.'
      },
      {
        id: '1PjtEF4hlMU_42b438GmEQhYZTba75kRJ',
        category: 'biet-thu-nha-pho',
        title: 'Xây Dựng Hoàn Thiện Nhà Phố Gia Đình & Lắp Đặt Cửa Cổng Đồng Bộ',
        desc: 'Thi công phần thô và hoàn thiện kiến trúc mặt tiền nhà phố tại TP Đà Nẵng.'
      },
      {
        id: '1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA',
        category: 'khach-san-can-ho',
        title: 'Thi Công Căn Hộ Dịch Vụ Cho Thuê & Hệ Thống Lan Can Sắt Mỹ Thuật',
        desc: 'Giải pháp xây dựng tối ưu không gian và chi phí cho chủ đầu tư căn hộ, khách sạn tại Đà Nẵng.'
      },
      {
        id: '1ng7_50Be4LsQqNa28KBn8rSCicz40ir9',
        category: 'van-phong-nha-xuong',
        title: 'Thi Công Nhà Xưởng Khung Thép Tiền Chế & Hệ Thống Mái Tôn Công Nghiệp',
        desc: 'Chế tạo và lắp dựng khung kèo thép tiền chế vượt nhịp lớn cho nhà xưởng, kho bãi.'
      },
      {
        id: '1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS',
        category: 'co-khi-ket-cau',
        title: 'Sản Xuất Cửa Cổng Sắt Mỹ Thuật Cắt CNC & Khung Bảo Vệ An Toàn',
        desc: 'Gia công trực tiếp tại xưởng Cơ Khí Nam Phát với lớp sơn chống gỉ 2 thành phần bền bỉ.'
      },
      {
        id: '1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF',
        category: 'biet-thu-nha-pho',
        title: 'Công Trình Nhà Phố Phường An Hải – Thi Công Phần Thô & Cơ Khí Hoàn Thiện',
        desc: 'Đảm bảo đúng tiến độ, vật tư chính hãng và giám sát kỹ thuật chặt chẽ tại Phường An Hải, Đà Nẵng.'
      },
      {
        id: '1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi',
        category: 'khach-san-can-ho',
        title: 'Thi Công Tòa Nhà Căn Hộ – Phòng Trọ Cao Cấp Kết Hợp Cầu Thang Thép',
        desc: 'Thiết kế và thi công trọn gói mô hình căn hộ cho thuê hiệu suất cao tại Đà Nẵng.'
      },
      {
        id: '1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq',
        category: 'van-phong-nha-xuong',
        title: 'Lắp Dựng Kết Cấu Thép Nhà Kho & Hạng Mục Cơ Khí Công Trình Lớn',
        desc: 'Đội ngũ thợ cơ khí và kỹ sư Nam Phát thi công lắp đặt an toàn, chuẩn bản vẽ kết cấu.'
      },
      {
        id: '1fqJikC677z_7x28XQaAx3VQD7zqWtiUy',
        category: 'biet-thu-nha-pho',
        title: 'Thi Công Biệt Thự Hiện Đại & Hệ Mái Kính Khung Thép Cường Lực Cao Cấp',
        desc: 'Kết hợp hài hòa giữa kiến trúc sang trọng và chi tiết cơ khí ngoại thất tinh tế.'
      },
      {
        id: '1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x',
        category: 'van-phong-nha-xuong',
        title: 'Thiết Kế & Thi Công Cải Tạo Văn Phòng Công Ty Kết Hợp Khung Thép',
        desc: 'Giải pháp nâng tầng, mở rộng không gian văn phòng nhanh chóng bằng hệ sàn deck khung thép.'
      },
      {
        id: '11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ',
        category: 'co-khi-ket-cau',
        title: 'Gia Công Hệ Vì Kèo Thép Mạ Kẽm, Xà Gồ & Lợp Mái Tôn Chống Nóng',
        desc: 'Thi công mái tôn chống thấm dột, chống bão kiên cố cho công trình dân dụng và công nghiệp.'
      },
      {
        id: '1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw',
        category: 'co-khi-ket-cau',
        title: 'Thi Công Cầu Thang Xương Cá Bằng Thép & Lan Can Kính Nội Thất',
        desc: 'Điểm nhấn hiện đại, chắc chắn và tiết kiệm diện tích cho nhà phố, biệt thự, văn phòng.'
      },
      {
        id: '1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK',
        category: 'khach-san-can-ho',
        title: 'Hoàn Thiện Công Trình Khách Sạn & Hạng Mục Cơ Khí Phụ Trợ Đồng Bộ',
        desc: 'Đáp ứng tiêu chuẩn thẩm mỹ và an toàn phòng cháy chữa cháy cho công trình lưu trú.'
      },
      {
        id: '1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1',
        category: 'van-phong-nha-xuong',
        title: 'Thi Công Khung Thép Tiền Chế Quán Cafe, Showroom & Nhà Hàng Đà Nẵng',
        desc: 'Thiết kế không gian mở thoáng đãng, tối ưu chi phí đầu tư ban đầu cho khách hàng.'
      },
      {
        id: '1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ',
        category: 'co-khi-ket-cau',
        title: 'Gia Công Lắp Đặt Hàng Rào, Cửa Cổng Sắt & Kết Cấu Bảo Vệ Công Trình',
        desc: 'Sản phẩm cơ khí hoàn thiện sắc nét, bền đẹp theo thời gian tại Nam Phát (namphat.com).'
      }
    ];

    const productGridEl = document.getElementById('productGrid');
    const itemModal = document.getElementById('itemModal');
    const modalTitle = document.getElementById('modalTitle');
    const modalImg = document.getElementById('modalImg');
    const modalDesc = document.getElementById('modalDesc');
    const closeModalBtn = document.getElementById('closeModalBtn');
    const modalQuoteBtn = document.getElementById('modalQuoteBtn');

    function renderProducts(filterKey) {
      const filtered = filterKey === 'all'
        ? realItemsData
        : realItemsData.filter(item => item.category === filterKey);

      productGridEl.innerHTML = filtered.map((item, idx) => {
        const primaryUrl = `https://lh3.googleusercontent.com/d/${item.id}=w800`;
        const backupUrl = `https://drive.google.com/thumbnail?id=${item.id}&sz=w800`;
        const fallbackPlaceholder = `https://placehold.co/600x450/0d3b66/ffffff?text=Nam+Phat+${idx + 1}`;

        return `
          <div class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col justify-between">
            <div>
              <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden cursor-pointer" onclick="openItemDetail('${item.id}')">
                <img src="${primaryUrl}"
                     onerror="if(this.src!=='${backupUrl}'){this.src='${backupUrl}';}else{this.onerror=null;this.src='${fallbackPlaceholder}';}"
                     alt="${item.title}"
                     loading="lazy"
                     class="w-full h-full object-cover hover:scale-105 transition duration-300">
              </div>
              <div class="p-2.5 sm:p-3.5">
                <h3 class="font-bold text-brandBlue text-xs sm:text-sm product-title-full cursor-pointer hover:text-brandGold transition" onclick="openItemDetail('${item.id}')">
                  ${item.title}
                </h3>
                <p class="text-slate-600 text-[11px] mt-1 leading-relaxed">
                  ${item.desc}
                </p>
              </div>
            </div>
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex items-center justify-between gap-1 border-t border-slate-100">
              <button type="button" onclick="openItemDetail('${item.id}')" class="text-[11px] font-semibold text-brandBlue hover:text-brandGold">
                Xem ảnh lớn
              </button>
              <a href="#lien-he-bao-gia" class="px-2.5 py-1 rounded bg-brandGold/15 text-brandGold hover:bg-brandGold hover:text-white text-[11px] font-bold transition">
                Báo giá
              </a>
            </div>
          </div>
        `;
      }).join('');
    }

    window.openItemDetail = function(fileId) {
      const found = realItemsData.find(x => x.id === fileId);
      if (!found) return;
      modalTitle.textContent = found.title;
      modalImg.src = `https://lh3.googleusercontent.com/d/${found.id}=w1000`;
      modalImg.onerror = function() {
        this.onerror = null;
        this.src = `https://drive.google.com/thumbnail?id=${found.id}&sz=w1000`;
      };
      modalDesc.textContent = found.desc;
      itemModal.classList.remove('hidden');
      itemModal.classList.add('flex');
    };

    closeModalBtn.addEventListener('click', () => {
      itemModal.classList.add('hidden');
      itemModal.classList.remove('flex');
    });
    modalQuoteBtn.addEventListener('click', () => {
      itemModal.classList.add('hidden');
      itemModal.classList.remove('flex');
    });
    itemModal.addEventListener('click', (e) => {
      if (e.target === itemModal) {
        itemModal.classList.add('hidden');
        itemModal.classList.remove('flex');
      }
    });

    // Khởi tạo danh sách 16 sản phẩm/công trình
    renderProducts('all');

    // Sự kiện lọc danh mục
    document.querySelectorAll('.category-pill').forEach(btn => {
      btn.addEventListener('click', () => {
        document.querySelectorAll('.category-pill').forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        renderProducts(btn.getAttribute('data-filter'));
      });
    });

    // Xử lý 2 Banner tự trượt kích thước bằng nhau
    let currentSlide = 0;
    const slides = document.querySelectorAll('.banner-slide');
    const dots = document.querySelectorAll('.banner-dot');

    function showSlide(index) {
      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((s, i) => {
        s.classList.toggle('active', i === currentSlide);
      });
      dots.forEach((d, i) => {
        if (i === currentSlide) {
          d.className = 'banner-dot w-6 h-2 rounded-full bg-brandGold transition-all';
        } else {
          d.className = 'banner-dot w-2 h-2 rounded-full bg-white/60 transition-all';
        }
      });
    }

    document.getElementById('prevBannerBtn').addEventListener('click', () => showSlide(currentSlide - 1));
    document.getElementById('nextBannerBtn').addEventListener('click', () => showSlide(currentSlide + 1));
    dots.forEach(dot => {
      dot.addEventListener('click', () => showSlide( parseInt(dot.getAttribute('data-dot'), 10) ));
    });

    // Tự động trượt mỗi 5 giây
    setInterval(() => {
      showSlide(currentSlide + 1);
    }, 5000);

    // Menu trên điện thoại
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenuDropdown = document.getElementById('mobileMenuDropdown');
    mobileMenuBtn.addEventListener('click', () => {
      mobileMenuDropdown.classList.toggle('hidden');
    });
    document.querySelectorAll('.mobile-nav-link').forEach(link => {
      link.addEventListener('click', () => mobileMenuDropdown.classList.add('hidden'));
    });

    // Xử lý gửi Form Yêu Cầu Báo Giá Trang Chủ
    const quoteRequestForm = document.getElementById('quoteRequestForm');
    const formSuccessMessage = document.getElementById('formSuccessMessage');
    quoteRequestForm.addEventListener('submit', (e) => {
      e.preventDefault();
      const name = document.getElementById('custName').value.trim();
      const phone = document.getElementById('custPhone').value.trim();
      const type = document.getElementById('projectType').value;
      const budget = document.getElementById('budgetLevel').value;

      formSuccessMessage.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${type}</strong> (Mức đầu tư: ${budget}) đã được ghi nhận. Bộ phận kỹ thuật <strong>NAM PHÁT (0916.193.575)</strong> sẽ liên hệ tư vấn ngay!`;
      formSuccessMessage.classList.remove('hidden');
      quoteRequestForm.reset();
    });
  </script>
</body>
</html>
