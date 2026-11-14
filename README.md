<html lang="vi">
<head>
  <!-- Cấu hình Meta chuẩn SEO & Chia sẻ mạng xã hội (Thumbnail là Logo Tân An Thành) -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>CÔNG TY TNHH TÂN AN THÀNH - Đồng Phục Thời Trang, Áo Quần Bảo Hộ, In Thêu, Xưởng May</title>
  <meta name="description" content="Công ty TNHH Tân An Thành (tananthanh.com) - Chuyên Đồng Phục Thời Trang, Áo Quần Bảo Hộ Lao Động, In Thêu Vi Tính, Xưởng Sản Xuất Ngành May tại 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng. Hotline: 0983.579.544 - 0983.524.996">
  
  <!-- Open Graph Thumbnail dùng ảnh Logo khi gửi link trang web -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tananthanh.com/">
  <meta property="og:title" content="CÔNG TY TNHH TÂN AN THÀNH | Đồng Phục Thời Trang & Bảo Hộ Lao Động">
  <meta property="og:description" content="Chuyên Đồng Phục Thời Trang, Áo Quần Bảo Hộ, In Thêu, Xưởng Sản Xuất Ngành May. Địa chỉ: 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng.">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y">
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y">

  <!-- Tailwind CSS & Font Inter + Font Awesome -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              DEFAULT: '#0d3b72', // Xanh navy đậm chuẩn màu thương hiệu & aobaoho.vn
              dark: '#082850',
              light: '#19549c',
              accent: '#d9251d', // Đỏ cam nổi bật cho giảm giá & điểm nhấn
              bg: '#f5f7fa'
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
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
      background-color: #f5f7fa;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng từng từ bên trong tên danh mục */
    .desktop-cat-link {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      line-height: 1.2;
    }

    /* Flatsome Badge % Giảm giá góc trên bên trái */
    .badge-sale-flatsome {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d9251d;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 6px 7px;
      border-radius: 9999px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.35;
    }

    /* Hiệu ứng pulse nhẹ cho nút liên hệ nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 37, 29, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0); }
    }
    .pulse-contact {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="w-full overflow-x-hidden">

  <!-- ==================== 1. TOP BAR (FLATSOME TOP BAR) ==================== -->
  <div class="bg-brand-dark text-white text-[11px] sm:text-xs py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate max-w-full">
        <span class="font-semibold text-amber-300"><i class="fa-solid fa-industry mr-1"></i>tananthanh.com</span>
        <span class="hidden sm:inline text-white/40">|</span>
        <span class="truncate">Chuyên Đồng Phục Thời Trang, Áo Quần Bảo Hộ, In Thêu, Xưởng Sản Xuất Ngành May</span>
      </div>
      <div class="hidden md:flex items-center gap-4 whitespace-nowrap">
        <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng</span>
        <span><i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>0983.579.544 - 0983.524.996</span>
      </div>
    </div>
  </div>

  <!-- ==================== 2. HEADER CHÍNH (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40 w-full">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-2 sm:gap-4">
      
      <!-- Nút mở menu danh mục trên điện thoại -->
      <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-md text-brand border border-slate-200 hover:bg-slate-100 shrink-0" aria-label="Menu">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>

      <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
      <a href="#" class="flex items-center gap-2 sm:gap-3 min-w-0 shrink">
        <img 
          src="https://lh3.googleusercontent.com/d/17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y" 
          onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='https://drive.google.com/thumbnail?id=17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y&sz=w400';}else{this.src='https://placehold.co/120x120/0d3b72/ffffff?text=TAT';}"
          alt="Logo Công Ty TNHH Tân An Thành" 
          class="h-9 w-9 sm:h-11 sm:w-11 object-contain rounded border border-slate-100 p-0.5 bg-white shrink-0"
        >
        <div class="min-w-0">
          <div class="text-xs sm:text-base md:text-lg font-extrabold text-brand tracking-tight leading-tight truncate">
            CÔNG TY TNHH TÂN AN THÀNH
          </div>
          <div class="text-[10px] sm:text-xs text-slate-600 font-medium truncate">
            Đồng Phục Thời Trang • Bảo Hộ Lao Động • In Thêu
          </div>
        </div>
      </a>

      <!-- Ô tìm kiếm sản phẩm kiểu Flatsome (Desktop) -->
      <div class="hidden md:flex flex-1 max-w-md mx-2">
        <div class="relative w-full flex">
          <input 
            id="searchInputDesktop" 
            type="text" 
            oninput="handleSearch(this.value)"
            placeholder="Tìm đồng phục, quần áo bảo hộ, áo phản quang, in thêu..." 
            class="w-full text-xs sm:text-sm border border-slate-300 rounded-l-md px-3 py-2 focus:outline-none focus:border-brand"
          >
          <button onclick="handleSearch(document.getElementById('searchInputDesktop').value)" class="bg-brand hover:bg-brand-light text-white px-4 rounded-r-md text-xs font-semibold shrink-0 transition">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>

      <!-- Cam kết nhanh trên Desktop (Không để nút gọi ngay tránh tràn viền) -->
      <div class="hidden xl:flex items-center gap-4 text-xs text-slate-700 shrink-0">
        <div class="flex items-center gap-1.5">
          <i class="fa-solid fa-medal text-brand text-base"></i>
          <div>
            <div class="font-bold text-slate-800 leading-tight">Giá Gốc Tại Xưởng</div>
            <div class="text-[11px] text-slate-500">Không qua trung gian</div>
          </div>
        </div>
        <div class="flex items-center gap-1.5">
          <i class="fa-solid fa-truck-fast text-brand text-base"></i>
          <div>
            <div class="font-bold text-slate-800 leading-tight">Giao Hàng Toàn Quốc</div>
            <div class="text-[11px] text-slate-500">Đúng tiến độ cam kết</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Thanh tìm kiếm gọn trên Điện thoại -->
    <div class="md:hidden px-2.5 pb-2">
      <div class="relative w-full flex">
        <input 
          id="searchInputMobile" 
          type="text" 
          oninput="handleSearch(this.value)"
          placeholder="Tìm sản phẩm đồng phục, bảo hộ..." 
          class="w-full text-xs border border-slate-300 rounded-l-md px-3 py-1.5 focus:outline-none focus:border-brand"
        >
        <button onclick="handleSearch(document.getElementById('searchInputMobile').value)" class="bg-brand text-white px-3 rounded-r-md text-xs">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </div>
    </div>

    <!-- ==================== 3. THANH DANH MỤC TRÊN MÁY TÍNH ==================== -->
    <!-- Tên danh mục viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2, không xuống dòng tên danh mục -->
    <nav class="hidden lg:block bg-brand text-white border-t border-brand-light">
      <div class="flatsome-container py-1.5">
        <ul class="flex flex-wrap items-center justify-center xl:justify-between gap-x-2 gap-y-1 text-[12px] font-semibold">
          <li>
            <a href="#trang-chu" onclick="filterCategory('all')" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              <i class="fa-solid fa-house mr-1 text-amber-300"></i>TRANG CHỦ
            </a>
          </li>
          <li>
            <a href="#sec-dong-phuc" onclick="filterCategory('dong-phuc')" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              ĐỒNG PHỤC THỜI TRANG
            </a>
          </li>
          <li>
            <a href="#sec-bao-ho" onclick="filterCategory('bao-ho')" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              QUẦN ÁO BẢO HỘ LAO ĐỘNG
            </a>
          </li>
          <li>
            <a href="#sec-gile-nganh" onclick="filterCategory('gile-nganh')" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              ÁO PHẢN QUANG & ĐỒNG PHỤC NGÀNH
            </a>
          </li>
          <li>
            <a href="#sec-in-theu" onclick="filterCategory('in-theu')" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              IN THÊU & THIẾT BỊ BẢO HỘ
            </a>
          </li>
          <li>
            <a href="#sec-xuong-may" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              XƯỞNG SẢN XUẤT NGÀNH MAY
            </a>
          </li>
          <li>
            <a href="#sec-bao-gia" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              YÊU CẦU BÁO GIÁ
            </a>
          </li>
          <li>
            <a href="#sec-doi-tac" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              ĐỐI TÁC
            </a>
          </li>
          <li>
            <a href="#sec-bai-viet" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              BÀI VIẾT
            </a>
          </li>
          <li>
            <a href="#sec-lien-he" class="desktop-cat-link px-2 py-1 rounded hover:bg-white/15 transition">
              BẢN ĐỒ & FANPAGE
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ==================== MENU DRAWER DANH MỤC TRÊN ĐIỆN THOẠI ==================== -->
  <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/50 z-50 hidden"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[270px] max-w-[82vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="p-3 bg-brand text-white flex items-center justify-between">
      <span class="font-bold text-xs uppercase tracking-wider"><i class="fa-solid fa-list mr-1.5"></i>Danh Mục Tân An Thành</span>
      <button onclick="toggleMobileMenu()" class="w-7 h-7 flex items-center justify-center rounded bg-white/10 text-white">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <div class="p-3 overflow-y-auto flex-1 divide-y divide-slate-100 text-xs font-medium text-slate-700">
      <a href="#trang-chu" onclick="filterCategory('all'); toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-border-all text-brand w-4 text-center"></i> Tất Cả Sản Phẩm (23)
      </a>
      <a href="#sec-dong-phuc" onclick="filterCategory('dong-phuc'); toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-shirt text-brand w-4 text-center"></i> Đồng Phục Thời Trang & Áo Thun
      </a>
      <a href="#sec-bao-ho" onclick="filterCategory('bao-ho'); toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-user-shield text-brand w-4 text-center"></i> Quần Áo Bảo Hộ Lao Động
      </a>
      <a href="#sec-gile-nganh" onclick="filterCategory('gile-nganh'); toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-vest text-brand w-4 text-center"></i> Áo Phản Quang & Đồng Phục Ngành
      </a>
      <a href="#sec-in-theu" onclick="filterCategory('in-theu'); toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-helmet-safety text-brand w-4 text-center"></i> In Thêu & Thiết Bị Bảo Hộ
      </a>
      <a href="#sec-bao-gia" onclick="toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-file-signature text-brand w-4 text-center"></i> Form Yêu Cầu & Báo Giá
      </a>
      <a href="#sec-doi-tac" onclick="toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-handshake text-brand w-4 text-center"></i> Danh Mục Các Đối Tác
      </a>
      <a href="#sec-bai-viet" onclick="toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-newspaper text-brand w-4 text-center"></i> Bài Viết & Tin Tức
      </a>
      <a href="#sec-lien-he" onclick="toggleMobileMenu();" class="flex items-center gap-2.5 py-2.5 hover:text-brand">
        <i class="fa-solid fa-map-location-dot text-brand w-4 text-center"></i> Bản Đồ & Fanpage
      </a>
    </div>
    <div class="p-3 bg-slate-50 border-t border-slate-200 text-[11px] text-slate-600">
      <div class="font-bold text-brand mb-1">CÔNG TY TNHH TÂN AN THÀNH</div>
      <div>Đ/c: 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng</div>
      <div class="mt-0.5 font-semibold text-red-600">SĐT: 0983.579.544 - 0983.524.996</div>
    </div>
  </aside>

  <!-- ==================== 4. HERO BANNER TỰ TRƯỢT (2 SLIDES BẰNG NHAU) ==================== -->
  <!-- Thiết kế riêng ảnh banner Điện Thoại khác với ảnh banner Máy Tính để chữ nhỏ gọn, nằm hết bên trong ảnh, không tràn viền -->
  <section id="trang-chu" class="mt-3">
    <div class="flatsome-container">
      <div class="relative w-full rounded-lg overflow-hidden shadow-sm border border-slate-200 bg-brand-dark">

        <!-- SLIDE 1 -->
        <div id="banner-slide-0" class="banner-slide transition-opacity duration-500 opacity-100 block">
          
          <!-- Bản Máy Tính (Desktop Banner 1 - Chiều cao cố định 340px bằng Slide 2) -->
          <div class="hidden md:grid md:grid-cols-12 items-center h-[340px] lg:h-[360px] bg-gradient-to-r from-[#072549] via-[#0d3b72] to-[#155299] px-8 lg:px-12 relative overflow-hidden">
            <div class="col-span-7 text-white z-10 pr-4">
              <div class="inline-block bg-amber-400 text-slate-900 font-bold text-[11px] px-2.5 py-0.5 rounded mb-2">
                XƯỞNG SẢN XUẤT NGÀNH MAY TRỰC TIẾP - TANANTHANH.COM
              </div>
              <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                CÔNG TY TNHH TÂN AN THÀNH
              </h1>
              <p class="text-amber-300 font-bold text-xs lg:text-sm mt-1">
                Chuyên Đồng Phục Thời Trang • Áo Quần Bảo Hộ • In Thêu Vi Tính
              </p>
              <ul class="mt-2.5 space-y-1 text-xs lg:text-[13px] text-slate-100">
                <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>May đo thiết kế theo yêu cầu doanh nghiệp, trường học, nhà máy, công trình</li>
                <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>Chất liệu vải Kaki, Pangrim, Cá sấu cao cấp - Đường may bền chắc chuẩn xuất khẩu</li>
                <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>Địa chỉ: 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng | ĐT: 0983.579.544 - 0983.524.996</li>
              </ul>
              <div class="mt-4 flex items-center gap-3">
                <a href="#sec-bao-gia" class="bg-brand-accent hover:bg-red-700 text-white font-bold text-xs px-4 py-2 rounded shadow transition">
                  NHẬN BÁO GIÁ SỈ TẠI XƯỞNG
                </a>
                <a href="#tat-ca-san-pham" class="bg-white/15 hover:bg-white/25 text-white font-semibold text-xs px-4 py-2 rounded border border-white/30 transition">
                  XEM 23 MẪU THỰC TẾ
                </a>
              </div>
            </div>
            <!-- Khung ảnh thực tế bên phải trên máy tính -->
            <div class="col-span-5 grid grid-cols-2 gap-2.5 z-10">
              <div class="bg-white p-1.5 rounded-lg shadow-lg">
                <img src="https://lh3.googleusercontent.com/d/1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd" onerror="this.src='https://drive.google.com/thumbnail?id=1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd&sz=w600'" alt="Đồng phục Tân An Thành" class="w-full h-32 lg:h-36 object-cover rounded">
                <div class="text-[11px] font-bold text-center text-brand mt-1 truncate">Đồng Phục Thời Trang</div>
              </div>
              <div class="bg-white p-1.5 rounded-lg shadow-lg">
                <img src="https://lh3.googleusercontent.com/d/1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR" onerror="this.src='https://drive.google.com/thumbnail?id=1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR&sz=w600'" alt="Bảo hộ Tân An Thành" class="w-full h-32 lg:h-36 object-cover rounded">
                <div class="text-[11px] font-bold text-center text-brand mt-1 truncate">Quần Áo Bảo Hộ</div>
              </div>
            </div>
          </div>

          <!-- Bản Điện Thoại (Mobile Banner 1 Thiết kế riêng - Kích thước cố định 230px bằng Slide 2, chữ nhỏ gọn nằm hết trong khung) -->
          <div class="flex md:hidden flex-col justify-between h-[230px] bg-gradient-to-br from-[#072549] via-[#0d3b72] to-[#155299] p-3 text-white relative overflow-hidden">
            <div>
              <span class="inline-block bg-amber-400 text-slate-900 font-bold text-[9px] px-2 py-0.5 rounded">
                XƯỞNG MAY TRỰC TIẾP • TANANTHANH.COM
              </span>
              <h2 class="text-sm font-extrabold mt-1 leading-tight text-white">
                CÔNG TY TNHH TÂN AN THÀNH
              </h2>
              <p class="text-[11px] text-amber-300 font-semibold mt-0.5 leading-tight">
                Đồng Phục Thời Trang • Áo Quần Bảo Hộ • In Thêu
              </p>
            </div>
            <div class="grid grid-cols-12 gap-2 items-center my-1">
              <div class="col-span-7 space-y-0.5 text-[10px] text-slate-100 leading-tight">
                <div>• May đồng phục công ty, bảo hộ kỹ sư</div>
                <div>• In thêu logo vi tính sắc nét, bền màu</div>
                <div>• Đ/c: 14A Nguyễn Tất Thành, Tam Kỳ</div>
                <div class="text-amber-300 font-bold">• ĐT: 0983.579.544 - 0983.524.996</div>
              </div>
              <div class="col-span-5 flex gap-1">
                <img src="https://lh3.googleusercontent.com/d/1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd" onerror="this.src='https://drive.google.com/thumbnail?id=1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd&sz=w400'" alt="Sản phẩm" class="w-1/2 h-20 object-cover rounded bg-white p-0.5">
                <img src="https://lh3.googleusercontent.com/d/1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR" onerror="this.src='https://drive.google.com/thumbnail?id=1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR&sz=w400'" alt="Sản phẩm" class="w-1/2 h-20 object-cover rounded bg-white p-0.5">
              </div>
            </div>
            <div class="flex items-center justify-between pt-1 border-t border-white/15">
              <span class="text-[10px] text-slate-200">Cam kết giá gốc tận xưởng</span>
              <a href="#sec-bao-gia" class="bg-brand-accent text-white text-[10px] font-bold px-2.5 py-1 rounded">
                Báo Giá Ngay
              </a>
            </div>
          </div>
        </div>

        <!-- SLIDE 2 -->
        <div id="banner-slide-1" class="banner-slide transition-opacity duration-500 opacity-0 hidden">
          
          <!-- Bản Máy Tính (Desktop Banner 2 - Chiều cao cố định 340px bằng Slide 1) -->
          <div class="hidden md:grid md:grid-cols-12 items-center h-[340px] lg:h-[360px] bg-gradient-to-r from-[#0f2942] via-[#134e6f] to-[#0d3b72] px-8 lg:px-12 relative overflow-hidden">
            <div class="col-span-7 text-white z-10 pr-4">
              <div class="inline-block bg-brand-accent text-white font-bold text-[11px] px-2.5 py-0.5 rounded mb-2">
                CÔNG NGHỆ IN THÊU HIỆN ĐẠI & BẢO HỘ ĐỒNG BỘ
              </div>
              <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                GIẢI PHÁP ĐỒNG PHỤC & AN TOÀN LAO ĐỘNG TOÀN DIỆN
              </h2>
              <p class="text-amber-300 font-bold text-xs lg:text-sm mt-1">
                Xưởng Sản Xuất Ngành May Quy Mô Lớn - Đáp Ứng Đơn Hàng Gấp
              </p>
              <ul class="mt-2.5 space-y-1 text-xs lg:text-[13px] text-slate-100">
                <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>Miễn phí tư vấn mẫu vải, thiết kế demo logo đồng phục theo nhận diện thương hiệu</li>
                <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>Đầy đủ trang thiết bị bảo hộ: Quần áo kỹ sư, áo gile phản quang, giày, mũ bảo hộ</li>
                <li><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>Chiết khấu cao cho đơn hàng doanh nghiệp - Giao hàng tận nơi trên toàn quốc</li>
              </ul>
              <div class="mt-4 flex items-center gap-3">
                <a href="#sec-in-theu" class="bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold text-xs px-4 py-2 rounded shadow transition">
                  DỊCH VỤ IN THÊU & BẢO HỘ
                </a>
                <a href="#sec-lien-he" class="bg-white/15 hover:bg-white/25 text-white font-semibold text-xs px-4 py-2 rounded border border-white/30 transition">
                  XEM BẢN ĐỒ & FANPAGE
                </a>
              </div>
            </div>
            <!-- Khung ảnh thực tế bên phải trên máy tính -->
            <div class="col-span-5 grid grid-cols-2 gap-2.5 z-10">
              <div class="bg-white p-1.5 rounded-lg shadow-lg">
                <img src="https://lh3.googleusercontent.com/d/1ElybLEds6I_dpsLei0wjJIPezZpViAgp" onerror="this.src='https://drive.google.com/thumbnail?id=1ElybLEds6I_dpsLei0wjJIPezZpViAgp&sz=w600'" alt="Áo gile bảo hộ" class="w-full h-32 lg:h-36 object-cover rounded">
                <div class="text-[11px] font-bold text-center text-brand mt-1 truncate">Áo Gile Phản Quang</div>
              </div>
              <div class="bg-white p-1.5 rounded-lg shadow-lg">
                <img src="https://lh3.googleusercontent.com/d/1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld" onerror="this.src='https://drive.google.com/thumbnail?id=1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld&sz=w600'" alt="In thêu đồng phục" class="w-full h-32 lg:h-36 object-cover rounded">
                <div class="text-[11px] font-bold text-center text-brand mt-1 truncate">In Thêu Sắc Nét</div>
              </div>
            </div>
          </div>

          <!-- Bản Điện Thoại (Mobile Banner 2 Thiết kế riêng - Kích thước cố định 230px bằng Slide 1, chữ nhỏ gọn nằm hết trong khung) -->
          <div class="flex md:hidden flex-col justify-between h-[230px] bg-gradient-to-br from-[#0f2942] via-[#134e6f] to-[#0d3b72] p-3 text-white relative overflow-hidden">
            <div>
              <span class="inline-block bg-brand-accent text-white font-bold text-[9px] px-2 py-0.5 rounded">
                IN THÊU VI TÍNH & ĐỒ BẢO HỘ ĐỒNG BỘ
              </span>
              <h2 class="text-sm font-extrabold mt-1 leading-tight text-white">
                XƯỞNG MAY ĐỒNG PHỤC & BẢO HỘ UY TÍN
              </h2>
              <p class="text-[11px] text-amber-300 font-semibold mt-0.5 leading-tight">
                Thiết Kế Miễn Phí • Nhận Đặt May Số Lượng Lớn
              </p>
            </div>
            <div class="grid grid-cols-12 gap-2 items-center my-1">
              <div class="col-span-7 space-y-0.5 text-[10px] text-slate-100 leading-tight">
                <div>• Áo gile phản quang, mũ, giày bảo hộ</div>
                <div>• Đồng phục công sở, học sinh, bảo vệ</div>
                <div>• 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng</div>
                <div class="text-amber-300 font-bold">• Hotline: 0983.579.544 - 0983.524.996</div>
              </div>
              <div class="col-span-5 flex gap-1">
                <img src="https://lh3.googleusercontent.com/d/1ElybLEds6I_dpsLei0wjJIPezZpViAgp" onerror="this.src='https://drive.google.com/thumbnail?id=1ElybLEds6I_dpsLei0wjJIPezZpViAgp&sz=w400'" alt="Sản phẩm" class="w-1/2 h-20 object-cover rounded bg-white p-0.5">
                <img src="https://lh3.googleusercontent.com/d/1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld" onerror="this.src='https://drive.google.com/thumbnail?id=1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld&sz=w400'" alt="Sản phẩm" class="w-1/2 h-20 object-cover rounded bg-white p-0.5">
              </div>
            </div>
            <div class="flex items-center justify-between pt-1 border-t border-white/15">
              <span class="text-[10px] text-slate-200">Giao hàng toàn quốc nhanh chóng</span>
              <a href="#tat-ca-san-pham" class="bg-amber-400 text-slate-900 text-[10px] font-bold px-2.5 py-1 rounded">
                Xem Sản Phẩm
              </a>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng & chấm chỉ báo Slide -->
        <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20 transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20 transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex gap-1.5 z-20">
          <button id="banner-dot-0" onclick="goToSlide(0)" class="w-5 h-1.5 rounded-full bg-amber-400 transition-all"></button>
          <button id="banner-dot-1" onclick="goToSlide(1)" class="w-2 h-1.5 rounded-full bg-white/50 transition-all"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- ==================== 5. THANH TIỆN ÍCH CAM KẾT GIỐNG AOBAOHO.VN ==================== -->
  <section class="mt-3">
    <div class="flatsome-container">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2 sm:gap-3">
        <div class="bg-white rounded-md p-2.5 sm:p-3 border border-slate-200 flex items-center gap-2.5">
          <div class="w-9 h-9 rounded-full bg-brand/10 text-brand flex items-center justify-center shrink-0">
            <i class="fa-solid fa-industry text-sm"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-slate-800">Xưởng May Trực Tiếp</div>
            <div class="text-[11px] text-slate-500">Chủ động tiến độ & chất lượng</div>
          </div>
        </div>
        <div class="bg-white rounded-md p-2.5 sm:p-3 border border-slate-200 flex items-center gap-2.5">
          <div class="w-9 h-9 rounded-full bg-brand/10 text-brand flex items-center justify-center shrink-0">
            <i class="fa-solid fa-palette text-sm"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-slate-800">In Thêu Công Nghệ Cao</div>
            <div class="text-[11px] text-slate-500">Sắc nét, không bong tróc</div>
          </div>
        </div>
        <div class="bg-white rounded-md p-2.5 sm:p-3 border border-slate-200 flex items-center gap-2.5">
          <div class="w-9 h-9 rounded-full bg-brand/10 text-brand flex items-center justify-center shrink-0">
            <i class="fa-solid fa-shield-halved text-sm"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-slate-800">Chuẩn An Toàn Bảo Hộ</div>
            <div class="text-[11px] text-slate-500">Vải dày dặn, thoáng mát</div>
          </div>
        </div>
        <div class="bg-white rounded-md p-2.5 sm:p-3 border border-slate-200 flex items-center gap-2.5">
          <div class="w-9 h-9 rounded-full bg-brand/10 text-brand flex items-center justify-center shrink-0">
            <i class="fa-solid fa-truck-fast text-sm"></i>
          </div>
          <div class="min-w-0">
            <div class="text-xs font-bold text-slate-800">Giao Hàng Toàn Quốc</div>
            <div class="text-[11px] text-slate-500">Hỗ trợ đơn hàng doanh nghiệp</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 6. DANH MỤC SẢN PHẨM TRANG CHỦ (TỐI ƯU MÁY TÍNH & ĐIỆN THOẠI, CHỮ NHỎ GỌN) ==================== -->
  <section class="mt-5">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 shadow-sm">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3">
          <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase tracking-wide flex items-center gap-1.5">
            <i class="fa-solid fa-layer-group text-brand-accent"></i> DANH MỤC SẢN PHẨM CHÍNH
          </h2>
          <button onclick="filterCategory('all')" class="text-[11px] font-semibold text-brand hover:underline">
            Xem tất cả (23)
          </button>
        </div>

        <!-- Lưới danh mục: 2 cột trên điện thoại, 6 cột trên máy tính, chữ danh mục nhỏ gọn -->
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2 sm:gap-3">
          
          <a href="#sec-dong-phuc" onclick="filterCategory('dong-phuc')" class="group border border-slate-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center transition bg-slate-50/60 hover:bg-white">
            <div class="w-full h-24 sm:h-28 rounded overflow-hidden bg-white mb-1.5 border border-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd" onerror="this.src='https://drive.google.com/thumbnail?id=1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd&sz=w400'" alt="Đồng phục thời trang" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand leading-tight">Đồng Phục Thời Trang</div>
            <div class="text-[10px] text-slate-500 mt-0.5">6 mẫu thực tế</div>
          </a>

          <a href="#sec-bao-ho" onclick="filterCategory('bao-ho')" class="group border border-slate-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center transition bg-slate-50/60 hover:bg-white">
            <div class="w-full h-24 sm:h-28 rounded overflow-hidden bg-white mb-1.5 border border-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR" onerror="this.src='https://drive.google.com/thumbnail?id=1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR&sz=w400'" alt="Quần áo bảo hộ" class="w-full h-24 sm:h-28 object-cover group-hover:scale-105 transition duration-300">
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand leading-tight">Quần Áo Bảo Hộ</div>
            <div class="text-[10px] text-slate-500 mt-0.5">6 mẫu thực tế</div>
          </a>

          <a href="#sec-gile-nganh" onclick="filterCategory('gile-nganh')" class="group border border-slate-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center transition bg-slate-50/60 hover:bg-white">
            <div class="w-full h-24 sm:h-28 rounded overflow-hidden bg-white mb-1.5 border border-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1ElybLEds6I_dpsLei0wjJIPezZpViAgp" onerror="this.src='https://drive.google.com/thumbnail?id=1ElybLEds6I_dpsLei0wjJIPezZpViAgp&sz=w400'" alt="Áo phản quang" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand leading-tight">Áo Gile Phản Quang</div>
            <div class="text-[10px] text-slate-500 mt-0.5">4 mẫu thực tế</div>
          </a>

          <a href="#sec-gile-nganh" onclick="filterCategory('gile-nganh')" class="group border border-slate-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center transition bg-slate-50/60 hover:bg-white">
            <div class="w-full h-24 sm:h-28 rounded overflow-hidden bg-white mb-1.5 border border-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1ORmnePnaoXXai0gtmGP4AwFBb5Lz_Psr" onerror="this.src='https://drive.google.com/thumbnail?id=1ORmnePnaoXXai0gtmGP4AwFBb5Lz_Psr&sz=w400'" alt="Đồng phục công sở & trường học" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand leading-tight">Đồng Phục Ngành & Trường</div>
            <div class="text-[10px] text-slate-500 mt-0.5">4 mẫu thực tế</div>
          </a>

          <a href="#sec-in-theu" onclick="filterCategory('in-theu')" class="group border border-slate-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center transition bg-slate-50/60 hover:bg-white">
            <div class="w-full h-24 sm:h-28 rounded overflow-hidden bg-white mb-1.5 border border-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld" onerror="this.src='https://drive.google.com/thumbnail?id=1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld&sz=w400'" alt="In thêu đồng phục" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand leading-tight">In Thêu Gia Công</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Công nghệ cao</div>
          </a>

          <a href="#sec-in-theu" onclick="filterCategory('in-theu')" class="group border border-slate-200 hover:border-brand rounded-md p-2 flex flex-col items-center text-center transition bg-slate-50/60 hover:bg-white">
            <div class="w-full h-24 sm:h-28 rounded overflow-hidden bg-white mb-1.5 border border-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1eURpEJcQ8tQtgwT_od6Ca5HCM2CWpfcz" onerror="this.src='https://drive.google.com/thumbnail?id=1eURpEJcQ8tQtgwT_od6Ca5HCM2CWpfcz&sz=w400'" alt="Thiết bị bảo hộ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
            </div>
            <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand leading-tight">Phụ Kiện & Thiết Bị Bảo Hộ</div>
            <div class="text-[10px] text-slate-500 mt-0.5">Đồng bộ nhà xưởng</div>
          </a>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 7. DANH SÁCH 23 SẢN PHẨM THỰC TẾ CHIA THEO DANH MỤC (CHUẨN FLATSOME) ==================== -->
  <!--
    - Sản phẩm chia 2 cột trên điện thoại (grid-cols-2)
    - Tên sản phẩm không bị tràn ra ngoài hoặc thiếu chữ (product-title-full)
    - Giá giảm giá và % giảm giá giống Flatsome ở góc trên bên trái (.badge-sale-flatsome)
    - Không để các nhãn dán (Mới, Hot, Bán chạy) ở trang chủ
  -->
  <main id="tat-ca-san-pham" class="mt-5 space-y-6">

    <!-- Thông báo kết quả lọc/tìm kiếm (ẩn mặc định) -->
    <div id="filterStatusBox" class="flatsome-container hidden">
      <div class="bg-amber-50 border border-amber-300 text-slate-800 px-3 py-2 rounded-md flex items-center justify-between text-xs">
        <span id="filterStatusText" class="font-semibold">Đang lọc sản phẩm</span>
        <button onclick="resetFilter()" class="bg-brand text-white px-2.5 py-1 rounded text-[11px] font-bold">
          Hiển thị tất cả 23 sản phẩm
        </button>
      </div>
    </div>

    <!-- KHỐI DANH MỤC 1: ĐỒNG PHỤC THỜI TRANG & ÁO THUN ĐỒNG PHỤC (6 ảnh thực tế) -->
    <section id="sec-dong-phuc" data-cat-section="dong-phuc" class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand pb-2 mb-3">
          <h2 class="text-xs sm:text-sm md:text-base font-extrabold text-brand uppercase">
            1. ĐỒNG PHỤC THỜI TRANG & ÁO THUN DOANH NGHIỆP
          </h2>
          <a href="#sec-bao-gia" class="text-[11px] font-semibold text-brand hover:text-brand-accent">
            Nhận báo giá sỉ theo số lượng <i class="fa-solid fa-angle-right ml-0.5"></i>
          </a>
        </div>
        <div id="grid-dong-phuc" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3"></div>
      </div>
    </section>

    <!-- KHỐI DANH MỤC 2: QUẦN ÁO BẢO HỘ LAO ĐỘNG KỸ SƯ & CÔNG NHÂN (6 ảnh thực tế) -->
    <section id="sec-bao-ho" data-cat-section="bao-ho" class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand pb-2 mb-3">
          <h2 class="text-xs sm:text-sm md:text-base font-extrabold text-brand uppercase">
            2. QUẦN ÁO BẢO HỘ LAO ĐỘNG KỸ SƯ & CÔNG NHÂN
          </h2>
          <a href="#sec-bao-gia" class="text-[11px] font-semibold text-brand hover:text-brand-accent">
            Đặt may theo yêu cầu <i class="fa-solid fa-angle-right ml-0.5"></i>
          </a>
        </div>
        <div id="grid-bao-ho" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3"></div>
      </div>
    </section>

    <!-- KHỐI DANH MỤC 3: ÁO GILE PHẢN QUANG & ĐỒNG PHỤC NGÀNH NGHỀ / TRƯỜNG HỌC (6 ảnh thực tế) -->
    <section id="sec-gile-nganh" data-cat-section="gile-nganh" class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand pb-2 mb-3">
          <h2 class="text-xs sm:text-sm md:text-base font-extrabold text-brand uppercase">
            3. ÁO GILE PHẢN QUANG, ĐỒNG PHỤC CÔNG SỞ, BẢO VỆ & TRƯỜNG HỌC
          </h2>
          <a href="#sec-bao-gia" class="text-[11px] font-semibold text-brand hover:text-brand-accent">
            Tư vấn mẫu miễn phí <i class="fa-solid fa-angle-right ml-0.5"></i>
          </a>
        </div>
        <div id="grid-gile-nganh" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3"></div>
      </div>
    </section>

    <!-- KHỐI DANH MỤC 4: IN THÊU GIA CÔNG & TRANG THIẾT BỊ BẢO HỘ LAO ĐỘNG (5 ảnh thực tế) -->
    <section id="sec-in-theu" data-cat-section="in-theu" class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand pb-2 mb-3">
          <h2 class="text-xs sm:text-sm md:text-base font-extrabold text-brand uppercase">
            4. DỊCH VỤ IN THÊU LOGO & TRANG THIẾT BỊ BẢO HỘ ĐỒNG BỘ
          </h2>
          <a href="#sec-bao-gia" class="text-[11px] font-semibold text-brand hover:text-brand-accent">
            Báo giá in thêu nhanh <i class="fa-solid fa-angle-right ml-0.5"></i>
          </a>
        </div>
        <div id="grid-in-theu" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3"></div>
      </div>
    </section>

  </main>

  <!-- ==================== 8. GIỚI THIỆU XƯỞNG SẢN XUẤT NGÀNH MAY TÂN AN THÀNH ==================== -->
  <section id="sec-xuong-may" class="mt-6">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-4 sm:p-5 shadow-sm">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
          <div class="lg:col-span-7">
            <h2 class="text-sm sm:text-base md:text-lg font-extrabold text-brand uppercase">
              XƯỞNG SẢN XUẤT NGÀNH MAY - CÔNG TY TNHH TÂN AN THÀNH
            </h2>
            <p class="text-xs sm:text-sm text-slate-600 mt-2 leading-relaxed">
              <strong>Công ty TNHH Tân An Thành</strong> tự hào là đơn vị uy tín hàng đầu tại Tam Kỳ, Đà Nẵng và khu vực miền Trung chuyên thiết kế, sản xuất trực tiếp các dòng <strong>Đồng phục thời trang, Quần áo bảo hộ lao động, Đồng phục công sở, Đồng phục học sinh</strong> và dịch vụ <strong>In thêu vi tính công nghệ cao</strong>.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 mt-3 text-xs text-slate-700">
              <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                <div class="font-bold text-brand"><i class="fa-solid fa-check text-brand-accent mr-1"></i> Dây chuyền may khép kín</div>
                <div class="text-[11px] text-slate-600 mt-0.5">Từ khâu cắt, may, in lụa, in chuyển nhiệt, thêu vi tính đến đóng gói hoàn thiện.</div>
              </div>
              <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                <div class="font-bold text-brand"><i class="fa-solid fa-check text-brand-accent mr-1"></i> Nguồn vải tuyển chọn</div>
                <div class="text-[11px] text-slate-600 mt-0.5">Kaki Thành Công, Pangrim Hàn Quốc, thun cá sấu co giãn thoáng khí, thấm hút mồ hôi.</div>
              </div>
              <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                <div class="font-bold text-brand"><i class="fa-solid fa-check text-brand-accent mr-1"></i> Thiết kế mẫu miễn phí</div>
                <div class="text-[11px] text-slate-600 mt-0.5">Hỗ trợ lên maket đồng phục chuẩn màu nhận diện thương hiệu doanh nghiệp.</div>
              </div>
              <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                <div class="font-bold text-brand"><i class="fa-solid fa-check text-brand-accent mr-1"></i> Đầy đủ hóa đơn VAT & Hợp đồng</div>
                <div class="text-[11px] text-slate-600 mt-0.5">Cung ứng nhanh cho khu công nghiệp, nhà máy, công ty xây dựng, trường học.</div>
              </div>
            </div>
          </div>
          <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
            <img src="https://lh3.googleusercontent.com/d/1PxQDzHufoKX8rvtTN6U4jsKW5KCsfpXW" onerror="this.src='https://drive.google.com/thumbnail?id=1PxQDzHufoKX8rvtTN6U4jsKW5KCsfpXW&sz=w600'" alt="Xưởng may Tân An Thành 1" class="w-full h-36 sm:h-44 object-cover rounded border border-slate-200">
            <img src="https://lh3.googleusercontent.com/d/19JPCuR03qSCKVT6hWusgrI30Sgw16Syb" onerror="this.src='https://drive.google.com/thumbnail?id=19JPCuR03qSCKVT6hWusgrI30Sgw16Syb&sz=w600'" alt="Xưởng may Tân An Thành 2" class="w-full h-36 sm:h-44 object-cover rounded border border-slate-200">
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 9. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ==================== -->
  <section id="sec-bao-gia" class="mt-6">
    <div class="flatsome-container">
      <div class="bg-gradient-to-r from-brand-dark via-brand to-brand-light rounded-lg p-4 sm:p-6 text-white shadow-sm">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
          
          <div class="lg:col-span-5">
            <h2 class="text-base sm:text-lg font-extrabold uppercase text-amber-300">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH
            </h2>
            <p class="text-xs sm:text-sm text-slate-100 mt-1.5 leading-relaxed">
              Quý khách hàng, doanh nghiệp cần đặt may đồng phục thời trang, quần áo bảo hộ lao động hoặc gia công in thêu số lượng sỉ & lẻ vui lòng để lại thông tin. Bộ phận kinh doanh Tân An Thành sẽ gửi bảng báo giá gốc tại xưởng trong vòng 15 phút!
            </p>
            <div class="mt-4 space-y-2 text-xs sm:text-sm">
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-phone-volume text-amber-300 w-5"></i>
                <span>Hotline trực tiếp: <strong class="text-amber-300">0983.579.544 - 0983.524.996</strong></span>
              </div>
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-location-dot text-amber-300 w-5"></i>
                <span>Địa chỉ: <strong>14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng</strong></span>
              </div>
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-globe text-amber-300 w-5"></i>
                <span>Website: <strong>tananthanh.com</strong></span>
              </div>
            </div>
          </div>

          <div class="lg:col-span-7">
            <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-lg p-3.5 sm:p-5 shadow-md">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên / Tên đơn vị *</label>
                  <input type="text" id="qName" required placeholder="Nhập họ tên hoặc tên công ty..." class="w-full text-xs sm:text-sm border border-slate-300 rounded px-3 py-2 focus:outline-none focus:border-brand">
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input type="tel" id="qPhone" required placeholder="Nhập số điện thoại nhận báo giá..." class="w-full text-xs sm:text-sm border border-slate-300 rounded px-3 py-2 focus:outline-none focus:border-brand">
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục sản phẩm cần báo giá</label>
                  <select id="qCategory" class="w-full text-xs sm:text-sm border border-slate-300 rounded px-3 py-2 focus:outline-none focus:border-brand bg-white">
                    <option value="Đồng Phục Thời Trang / Áo Thun">Đồng Phục Thời Trang / Áo Thun</option>
                    <option value="Quần Áo Bảo Hộ Lao Động">Quần Áo Bảo Hộ Lao Động</option>
                    <option value="Áo Gile & Áo Lưới Phản Quang">Áo Gile & Áo Lưới Phản Quang</option>
                    <option value="Đồng Phục Công Sở / Trường Học / Bảo Vệ">Đồng Phục Công Sở / Trường Học / Bảo Vệ</option>
                    <option value="In Thêu Gia Công Theo Yêu Cầu">In Thêu Gia Công Theo Yêu Cầu</option>
                    <option value="Mũ, Giày, Găng Tay Bảo Hộ">Mũ, Giày, Găng Tay Bảo Hộ</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số lượng dự kiến</label>
                  <input type="text" id="qQty" placeholder="VD: 50 bộ, 200 áo..." class="w-full text-xs sm:text-sm border border-slate-300 rounded px-3 py-2 focus:outline-none focus:border-brand">
                </div>
              </div>
              <div class="mt-3">
                <label class="block text-xs font-bold text-slate-700 mb-1">Yêu cầu chi tiết (Màu sắc, chất vải, in/thêu logo...)</label>
                <textarea id="qNote" rows="2" placeholder="Nhập yêu cầu cụ thể hoặc mã sản phẩm quý khách quan tâm..." class="w-full text-xs sm:text-sm border border-slate-300 rounded px-3 py-2 focus:outline-none focus:border-brand"></textarea>
              </div>
              <div class="mt-3 flex flex-wrap items-center justify-between gap-2">
                <span class="text-[11px] text-slate-500"><i class="fa-solid fa-lock text-brand mr-1"></i>Cam kết bảo mật thông tin & phản hồi nhanh</span>
                <button type="submit" class="bg-brand-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm px-5 py-2.5 rounded shadow transition">
                  <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                </button>
              </div>
            </form>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 10. DANH MỤC CÁC ĐỐI TÁC (PARTNERS SECTION) ==================== -->
  <section id="sec-doi-tac" class="mt-6">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2 mb-3">
          <h2 class="text-xs sm:text-sm md:text-base font-extrabold text-brand uppercase">
            <i class="fa-solid fa-handshake text-brand-accent mr-1.5"></i> ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU
          </h2>
          <span class="text-[11px] text-slate-500">Hợp tác bền vững cùng doanh nghiệp</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
          <div class="border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center bg-slate-50 hover:border-brand transition">
            <i class="fa-solid fa-building-columns text-2xl text-brand mb-1.5"></i>
            <div class="text-xs font-bold text-slate-800">KCN Tam Thăng</div>
            <div class="text-[10px] text-slate-500">Nhà máy & Xí nghiệp</div>
          </div>
          <div class="border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center bg-slate-50 hover:border-brand transition">
            <i class="fa-solid fa-car-side text-2xl text-brand mb-1.5"></i>
            <div class="text-xs font-bold text-slate-800">KCN Chu Lai</div>
            <div class="text-[10px] text-slate-500">Cơ khí & Công nghiệp</div>
          </div>
          <div class="border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center bg-slate-50 hover:border-brand transition">
            <i class="fa-solid fa-bolt text-2xl text-brand mb-1.5"></i>
            <div class="text-xs font-bold text-slate-800">Đơn Vị Điện Lực</div>
            <div class="text-[10px] text-slate-500">Đồng phục bảo hộ ngành điện</div>
          </div>
          <div class="border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center bg-slate-50 hover:border-brand transition">
            <i class="fa-solid fa-helmet-safety text-2xl text-brand mb-1.5"></i>
            <div class="text-xs font-bold text-slate-800">Công Ty Xây Dựng</div>
            <div class="text-[10px] text-slate-500">Kỹ sư & Công trình</div>
          </div>
          <div class="border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center bg-slate-50 hover:border-brand transition">
            <i class="fa-solid fa-graduation-cap text-2xl text-brand mb-1.5"></i>
            <div class="text-xs font-bold text-slate-800">Hệ Thống Trường Học</div>
            <div class="text-[10px] text-slate-500">Đồng phục học sinh các cấp</div>
          </div>
          <div class="border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center bg-slate-50 hover:border-brand transition">
            <i class="fa-solid fa-utensils text-2xl text-brand mb-1.5"></i>
            <div class="text-xs font-bold text-slate-800">Nhà Hàng & Dịch Vụ</div>
            <div class="text-[10px] text-slate-500">Đồng phục thời trang & sự kiện</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 11. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ==================== -->
  <section id="sec-bai-viet" class="mt-6">
    <div class="flatsome-container">
      <div class="bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2 mb-3">
          <h2 class="text-xs sm:text-sm md:text-base font-extrabold text-brand uppercase">
            <i class="fa-solid fa-newspaper text-brand-accent mr-1.5"></i> DANH MỤC BÀI VIẾT & KINH NGHIỆM CHỌN ĐỒNG PHỤC
          </h2>
          <span class="text-[11px] text-slate-500">Cập nhật từ Tân An Thành</span>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3">
          
          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <img src="https://lh3.googleusercontent.com/d/1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR" onerror="this.src='https://drive.google.com/thumbnail?id=1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR&sz=w500'" alt="Kinh nghiệm chọn vải bảo hộ" class="w-full h-36 object-cover">
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug">
                  Cách chọn vải Kaki và Pangrim may quần áo bảo hộ lao động bền mát cho mùa hè
                </h3>
                <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                  Phân biệt chất vải Kaki liên doanh, Kaki Thành Công và Pangrim Hàn Quốc phù hợp cho kỹ sư công trình và công nhân cơ khí...
                </p>
              </div>
              <a href="#sec-bao-gia" class="text-[11px] font-bold text-brand mt-2 inline-block hover:underline">
                Tư vấn chất liệu vải →
              </a>
            </div>
          </article>

          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <img src="https://lh3.googleusercontent.com/d/1Oka23607QIUmQVDxR2DPmsaXGNwGZRYR" onerror="this.src='https://drive.google.com/thumbnail?id=1Oka23607QIUmQVDxR2DPmsaXGNwGZRYR&sz=w500'" alt="May áo thun đồng phục" class="w-full h-36 object-cover">
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug">
                  Bí quyết thiết kế áo thun đồng phục công ty chuẩn nhận diện thương hiệu
                </h3>
                <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                  Lựa chọn kiểu cổ bẻ Polo lịch sự hay cổ tròn năng động, cách phối bo cổ và tay áo giúp đội ngũ nhân sự nổi bật chuyên nghiệp...
                </p>
              </div>
              <a href="#sec-bao-gia" class="text-[11px] font-bold text-brand mt-2 inline-block hover:underline">
                Xem bảng màu vải →
              </a>
            </div>
          </article>

          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <img src="https://lh3.googleusercontent.com/d/1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld" onerror="this.src='https://drive.google.com/thumbnail?id=1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld&sz=w500'" alt="In thêu đồng phục" class="w-full h-36 object-cover">
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug">
                  Nên chọn in lụa, in PET chuyển nhiệt hay thêu vi tính cho logo đồng phục?
                </h3>
                <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                  So sánh độ bền, chi phí và tính thẩm mỹ của từng phương pháp in thêu tại xưởng sản xuất ngành may Tân An Thành...
                </p>
              </div>
              <a href="#sec-bao-gia" class="text-[11px] font-bold text-brand mt-2 inline-block hover:underline">
                Báo giá in thêu →
              </a>
            </div>
          </article>

          <article class="border border-slate-200 rounded-md overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <img src="https://lh3.googleusercontent.com/d/1ElybLEds6I_dpsLei0wjJIPezZpViAgp" onerror="this.src='https://drive.google.com/thumbnail?id=1ElybLEds6I_dpsLei0wjJIPezZpViAgp&sz=w500'" alt="Tiêu chuẩn phản quang" class="w-full h-36 object-cover">
            <div class="p-3 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug">
                  Quy chuẩn trang bị áo gile phản quang & đồ bảo hộ cho ca làm việc ban đêm
                </h3>
                <p class="text-[11px] text-slate-600 mt-1.5 leading-relaxed">
                  Đảm bảo an toàn lao động tối đa tại công trường xây dựng, giao thông và nhà máy sản xuất với dải phản quang tiêu chuẩn...
                </p>
              </div>
              <a href="#sec-bao-gia" class="text-[11px] font-bold text-brand mt-2 inline-block hover:underline">
                Đặt mua đồ bảo hộ →
              </a>
            </div>
          </article>

        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 12. ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
  <section id="sec-lien-he" class="mt-6 mb-6">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
        
        <!-- BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ (7 CỘT) -->
        <div class="lg:col-span-7 bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-200 pb-2 mb-3">
              <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase">
                <i class="fa-solid fa-map-location-dot text-brand-accent mr-1.5"></i> BẢN ĐỒ ĐỊA CHỈ: 14A NGUYỄN TẤT THÀNH, TAM KỲ, ĐÀ NẴNG
              </h2>
              <a href="https://www.google.com/maps/search/?api=1&query=14A+Nguy%E1%BB%85n+T%E1%BA%A5t+Th%C3%A0nh,+Tam+K%E1%BB%B3" target="_blank" rel="noopener" class="text-[11px] font-bold text-brand hover:underline">
                Mở Google Maps lớn <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
              </a>
            </div>
            <!-- Nhúng Google Maps trực tiếp ra trang chủ -->
            <div class="w-full h-64 sm:h-72 rounded-md overflow-hidden border border-slate-200 bg-slate-100">
              <iframe 
                title="Bản đồ Công ty TNHH Tân An Thành 14A Nguyễn Tất Thành, Tam Kỳ"
                src="https://maps.google.com/maps?q=14A%20Nguy%E1%BB%85n%20T%E1%BA%A5t%20Th%C3%A0nh,%20Tam%20K%E1%BB%B3&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                width="100%" 
                height="100%" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>
          <div class="mt-3 p-2.5 bg-slate-50 rounded border border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs">
            <div>
              <strong>Địa chỉ:</strong> 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng | <strong>SĐT:</strong> <span class="text-red-600 font-bold">0983.579.544 - 0983.524.996</span>
            </div>
            <a href="https://www.google.com/maps/search/?api=1&query=14A+Nguy%E1%BB%85n+T%E1%BA%A5t+Th%C3%A0nh,+Tam+K%E1%BB%B3" target="_blank" rel="noopener" class="bg-brand text-white px-3 py-1 rounded text-[11px] font-semibold">
              Chỉ đường ngay
            </a>
          </div>
        </div>

        <!-- FANPAGE FACEBOOK NGOÀI TRANG CHỦ (5 CỘT) -->
        <div class="lg:col-span-5 bg-white rounded-lg border border-slate-200 p-3 sm:p-4 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between border-b border-slate-200 pb-2 mb-3">
              <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase">
                <i class="fa-brands fa-facebook text-[#1877F2] mr-1.5"></i> KẾT NỐI FANPAGE TÂN AN THÀNH
              </h2>
              <a href="https://www.facebook.com/ctytananthanh?locale=vi_VN" target="_blank" rel="noopener" class="text-[11px] font-bold text-[#1877F2] hover:underline">
                Theo dõi trang
              </a>
            </div>

            <!-- Thẻ Fanpage trực quan + Plugin Facebook -->
            <div class="border border-slate-200 rounded-md overflow-hidden bg-slate-50">
              <div class="bg-gradient-to-r from-[#0d3b72] to-[#1877F2] p-3 text-white flex items-center gap-3">
                <img 
                  src="https://lh3.googleusercontent.com/d/17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y" 
                  onerror="this.src='https://drive.google.com/thumbnail?id=17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y&sz=w300'"
                  alt="Fanpage Công ty TNHH Tân An Thành" 
                  class="w-12 h-12 rounded-full bg-white p-1 object-contain shrink-0"
                >
                <div class="min-w-0">
                  <a href="https://www.facebook.com/ctytananthanh?locale=vi_VN" target="_blank" rel="noopener" class="font-bold text-sm hover:underline block truncate">
                    CÔNG TY TNHH TÂN AN THÀNH
                  </a>
                  <div class="text-[11px] text-white/90 truncate">@ctytananthanh • Đồng Phục & Bảo Hộ Lao Động</div>
                  <div class="mt-1 flex gap-2">
                    <a href="https://www.facebook.com/ctytananthanh?locale=vi_VN" target="_blank" rel="noopener" class="bg-white text-[#1877F2] text-[10px] font-bold px-2.5 py-0.5 rounded shadow-sm">
                      <i class="fa-brands fa-facebook-f mr-1"></i>Thích Trang
                    </a>
                    <a href="https://www.facebook.com/ctytananthanh?locale=vi_VN" target="_blank" rel="noopener" class="bg-amber-400 text-slate-900 text-[10px] font-bold px-2.5 py-0.5 rounded shadow-sm">
                      <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn Tin
                    </a>
                  </div>
                </div>
              </div>

              <!-- Nhúng Facebook Page Plugin kết hợp ảnh hoạt động thực tế -->
              <div class="p-2.5 bg-white">
                <div class="w-full overflow-hidden rounded border border-slate-100 flex justify-center bg-slate-50">
                  <iframe 
                    title="Fanpage Facebook Công Ty TNHH Tân An Thành"
                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fctytananthanh&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                    width="340" 
                    height="180" 
                    style="border:none;overflow:hidden;max-width:100%;" 
                    scrolling="no" 
                    frameborder="0" 
                    allowfullscreen="true" 
                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                  </iframe>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-3 p-2.5 bg-blue-50/70 rounded border border-blue-200 flex items-center justify-between gap-2 text-xs">
            <span class="text-slate-700 truncate">Xem hình ảnh đơn hàng mới mỗi ngày trên Fanpage</span>
            <a href="https://www.facebook.com/ctytananthanh?locale=vi_VN" target="_blank" rel="noopener" class="bg-[#1877F2] text-white px-3 py-1 rounded text-[11px] font-semibold shrink-0">
              Truy cập Fanpage
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ==================== 13. FOOTER CHUẨN FLATSOME ==================== -->
  <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 lg:pb-8 border-t-4 border-brand-accent">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
        
        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-3 mb-3">
            <img 
              src="https://lh3.googleusercontent.com/d/17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y" 
              onerror="this.src='https://drive.google.com/thumbnail?id=17tiWMc926lmYVpmGPhEBJcy8jUOraw6Y&sz=w300'"
              alt="Logo Tân An Thành" 
              class="w-10 h-10 object-contain bg-white rounded p-0.5 shrink-0"
            >
            <div>
              <div class="font-extrabold text-sm sm:text-base text-white">CÔNG TY TNHH TÂN AN THÀNH</div>
              <div class="text-xs text-amber-300 font-semibold">Website: tananthanh.com</div>
            </div>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed mb-3">
            Chuyên Đồng Phục Thời Trang, Áo Quần Bảo Hộ Lao Động, In Thêu Vi Tính, Xưởng Sản Xuất Ngành May trực tiếp uy tín, chất lượng, giá gốc tại xưởng.
          </p>
          <ul class="space-y-1.5 text-xs text-slate-200">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Địa chỉ:</strong> 14A Nguyễn Tất Thành, Tam Kỳ, Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i><strong>Điện thoại / Zalo:</strong> 0983.579.544 - 0983.524.996</li>
            <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i><strong>Fanpage:</strong> fb.com/ctytananthanh</li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm -->
        <div class="lg:col-span-4">
          <h3 class="text-xs sm:text-sm font-bold text-white uppercase mb-3 border-b border-white/15 pb-1.5">
            DANH MỤC SẢN PHẨM & DỊCH VỤ
          </h3>
          <ul class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 text-xs text-slate-300">
            <li><a href="#sec-dong-phuc" class="hover:text-amber-300">› Đồng phục thời trang</a></li>
            <li><a href="#sec-dong-phuc" class="hover:text-amber-300">› Áo thun đồng phục</a></li>
            <li><a href="#sec-bao-ho" class="hover:text-amber-300">› Quần áo bảo hộ kỹ sư</a></li>
            <li><a href="#sec-bao-ho" class="hover:text-amber-300">› Bảo hộ công nhân</a></li>
            <li><a href="#sec-gile-nganh" class="hover:text-amber-300">› Áo gile phản quang</a></li>
            <li><a href="#sec-gile-nganh" class="hover:text-amber-300">› Đồng phục công sở</a></li>
            <li><a href="#sec-gile-nganh" class="hover:text-amber-300">› Đồng phục học sinh</a></li>
            <li><a href="#sec-in-theu" class="hover:text-amber-300">› In thêu & Thiết bị bảo hộ</a></li>
          </ul>
        </div>

        <!-- Cột 3: Hỗ trợ khách hàng -->
        <div class="lg:col-span-3">
          <h3 class="text-xs sm:text-sm font-bold text-white uppercase mb-3 border-b border-white/15 pb-1.5">
            CHÍNH SÁCH KHÁCH HÀNG
          </h3>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li>› Tư vấn & thiết kế mẫu miễn phí</li>
            <li>› Chiết khấu cao cho đơn hàng lớn</li>
            <li>› Cam kết đúng chất liệu vải hợp đồng</li>
            <li>› Giao hàng tận nơi trên toàn quốc</li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>© Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH TÂN AN THÀNH (tananthanh.com)</strong>.</div>
        <div>Thiết kế chuẩn UX Builder Flatsome</div>
      </div>
    </div>
  </footer>

  <!-- ==================== 14. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) ==================== -->
  <!-- Tương thích trên cả máy tính và điện thoại, không gây tràn viền -->
  <div class="fixed right-2.5 bottom-4 z-40 flex flex-col items-end gap-2">
    
    <!-- Nút Zalo nổi bật -->
    <a 
      href="https://zalo.me/0983579544" 
      target="_blank" 
      rel="noopener" 
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition"
      title="Chat Zalo 0983.579.544"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo: 0983.579.544</span>
    </a>

    <!-- Nút Facebook Fanpage nổi bật -->
    <a 
      href="https://www.facebook.com/ctytananthanh?locale=vi_VN" 
      target="_blank" 
      rel="noopener" 
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition"
      title="Fanpage Công Ty TNHH Tân An Thành"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Fanpage Tân An Thành</span>
    </a>

    <!-- Nút Hotline 1 -->
    <a 
      href="tel:0983579544" 
      class="pulse-contact flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition"
      title="Gọi 0983.579.544"
    >
      <span class="w-7 h-7 rounded-full bg-white text-brand-accent flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-[11px] sm:text-xs font-extrabold pr-1.5">0983.579.544</span>
    </a>

    <!-- Nút Hotline 2 -->
    <a 
      href="tel:0983524996" 
      class="flex items-center gap-2 bg-brand hover:bg-brand-dark text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg border border-white/20 transition"
      title="Gọi 0983.524.996"
    >
      <span class="w-7 h-7 rounded-full bg-amber-400 text-slate-900 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="text-[11px] sm:text-xs font-extrabold pr-1.5">0983.524.996</span>
    </a>

  </div>

  <!-- ==================== 15. HỘP THOẠI XEM CHI TIẾT / THÔNG BÁO (KHÔNG DÙNG ALERT) ==================== -->
  <div id="customModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-md w-full p-4 shadow-2xl border border-slate-200 relative">
      <button onclick="closeModal()" class="absolute top-2.5 right-2.5 w-7 h-7 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center">
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="modalBody"></div>
    </div>
  </div>

  <!-- ==================== 16. JAVASCRIPT DỮ LIỆU 23 ẢNH SẢN PHẨM THỰC TẾ & TƯƠNG TÁC ==================== -->
  <script>
    // Danh sách đầy đủ 23 file ảnh sản phẩm thực tế từ Google Drive được phân loại đúng danh mục và tên sản phẩm
    const productsData = [
      // 1. ĐỒNG PHỤC THỜI TRANG & ÁO THUN (6 sản phẩm)
      {
        id: 1,
        driveId: '1kF5sUrTH8iR3w91_X6Dr5afPkaGDGGfd',
        name: 'Áo Thun Đồng Phục Công Ty Cổ Trụ Phối Màu Cao Cấp',
        category: 'dong-phuc',
        oldPrice: '165.000đ',
        newPrice: '135.000đ',
        discount: '-18%'
      },
      {
        id: 2,
        driveId: '1Oka23607QIUmQVDxR2DPmsaXGNwGZRYR',
        name: 'Áo Polo Đồng Phục Doanh Nghiệp Thêu Logo Sắc Nét',
        category: 'dong-phuc',
        oldPrice: '175.000đ',
        newPrice: '145.000đ',
        discount: '-17%'
      },
      {
        id: 3,
        driveId: '1hP4QXpy6qPNsNW2XqWI3gmjLjJicj003',
        name: 'Đồng Phục Áo Thun Sự Kiện Và Team Building Thoáng Mát',
        category: 'dong-phuc',
        oldPrice: '140.000đ',
        newPrice: '115.000đ',
        discount: '-18%'
      },
      {
        id: 4,
        driveId: '181JN5FsBqAqPuNNwencNMIw-q8fJ6BDw',
        name: 'Áo Thun Đồng Phục Cá Sấu Poly Co Giãn 4 Chiều',
        category: 'dong-phuc',
        oldPrice: '160.000đ',
        newPrice: '130.000đ',
        discount: '-19%'
      },
      {
        id: 5,
        driveId: '1sGGIsdw1b8QEBUBJJayOmNk3FwZMmIyp',
        name: 'Đồng Phục Thời Trang Nhà Hàng Quán Cafe Thiết Kế Riêng',
        category: 'dong-phuc',
        oldPrice: '180.000đ',
        newPrice: '150.000đ',
        discount: '-17%'
      },
      {
        id: 6,
        driveId: '1PnARvQpqTJjb18aiZ301KdT7fB8fytgj',
        name: 'Áo Khoác Gió Đồng Phục Doanh Nghiệp 2 Lớp Chống Thấm',
        category: 'dong-phuc',
        oldPrice: '260.000đ',
        newPrice: '215.000đ',
        discount: '-17%'
      },

      // 2. QUẦN ÁO BẢO HỘ LAO ĐỘNG (6 sản phẩm)
      {
        id: 7,
        driveId: '1xLjrqbxXR1Hh211nM-BXJcntu8nu_kKR',
        name: 'Bộ Quần Áo Bảo Hộ Kỹ Sư Vải Kaki Liên Doanh Phối Màu',
        category: 'bao-ho',
        oldPrice: '310.000đ',
        newPrice: '255.000đ',
        discount: '-18%'
      },
      {
        id: 8,
        driveId: '1nKuL-sT0f9F3jyvx2ZdVPEFukjcCJhaZ',
        name: 'Đồng Phục Bảo Hộ Lao Động Công Nhân Cơ Khí Dài Tay',
        category: 'bao-ho',
        oldPrice: '280.000đ',
        newPrice: '230.000đ',
        discount: '-18%'
      },
      {
        id: 9,
        driveId: '1FECUYNYTk0sowdkIWbr5URE3RR-wV_Yb',
        name: 'Bộ Quần Áo Bảo Hộ Phối Dải Phản Quang Công Trình',
        category: 'bao-ho',
        oldPrice: '340.000đ',
        newPrice: '285.000đ',
        discount: '-16%'
      },
      {
        id: 10,
        driveId: '1e4_v4DhbyPVTsuwY2EYF_aPsQKEazR8l',
        name: 'Quần Áo Bảo Hộ Ngành Điện Lực Tiêu Chuẩn Dày Dặn',
        category: 'bao-ho',
        oldPrice: '330.000đ',
        newPrice: '275.000đ',
        discount: '-17%'
      },
      {
        id: 11,
        driveId: '1PxQDzHufoKX8rvtTN6U4jsKW5KCsfpXW',
        name: 'Bộ Bảo Hộ Lao Động Vải Pangrim Hàn Quốc Cao Cấp',
        category: 'bao-ho',
        oldPrice: '390.000đ',
        newPrice: '325.000đ',
        discount: '-17%'
      },
      {
        id: 12,
        driveId: '1Zh-2BJQzwneWkrtN--lkTcLzVagC3cS3',
        name: 'Đồng Phục Bảo Hộ Xưởng Sản Xuất Và Nhà Máy Công Nghiệp',
        category: 'bao-ho',
        oldPrice: '270.000đ',
        newPrice: '220.000đ',
        discount: '-19%'
      },

      // 3. ÁO GILE PHẢN QUANG & ĐỒNG PHỤC NGÀNH / TRƯỜNG HỌC (6 sản phẩm)
      {
        id: 13,
        driveId: '1ElybLEds6I_dpsLei0wjJIPezZpViAgp',
        name: 'Áo Gile Kỹ Sư Túi Hộp Phối Lưới Phản Quang Công Trường',
        category: 'gile-nganh',
        oldPrice: '155.000đ',
        newPrice: '125.000đ',
        discount: '-19%'
      },
      {
        id: 14,
        driveId: '1mu7A93crIkH8pJXb8j-Dg7NlgfL1KFUc',
        name: 'Áo Lưới Phản Quang Bảo Hộ Lao Động Làm Việc Ca Đêm',
        category: 'gile-nganh',
        oldPrice: '95.000đ',
        newPrice: '75.000đ',
        discount: '-21%'
      },
      {
        id: 15,
        driveId: '1ORmnePnaoXXai0gtmGP4AwFBb5Lz_Psr',
        name: 'Đồng Phục Sơ Mi Văn Phòng Công Sở Nam Nữ Thanh Lịch',
        category: 'gile-nganh',
        oldPrice: '240.000đ',
        newPrice: '195.000đ',
        discount: '-19%'
      },
      {
        id: 16,
        driveId: '1mJP1_snloXo19j7_EgJI1axcrHEkaPBn',
        name: 'Đồng Phục Bảo Vệ Chuyên Nghiệp Đầy Đủ Cầu Vai Phù Hiệu',
        category: 'gile-nganh',
        oldPrice: '295.000đ',
        newPrice: '245.000đ',
        discount: '-17%'
      },
      {
        id: 17,
        driveId: '1uKxW-PdTSwYg2gA89YrTRWwEuGSoMClh',
        name: 'Đồng Phục Học Sinh Và Thể Dục Trường Học Bền Đẹp',
        category: 'gile-nganh',
        oldPrice: '170.000đ',
        newPrice: '140.000đ',
        discount: '-18%'
      },
      {
        id: 18,
        driveId: '1VZbzd_1g4QrztQ6hUAtVFz6bIujQtYV0',
        name: 'Đồng Phục Y Tế Bệnh Viện Và Phòng Khám Chuẩn Quy Định',
        category: 'gile-nganh',
        oldPrice: '250.000đ',
        newPrice: '205.000đ',
        discount: '-18%'
      },

      // 4. IN THÊU GIA CÔNG & TRANG THIẾT BỊ BẢO HỘ (5 sản phẩm)
      {
        id: 19,
        driveId: '19JPCuR03qSCKVT6hWusgrI30Sgw16Syb',
        name: 'Dịch Vụ In Lụa In Chuyển Nhiệt In PET Đồng Phục Sắc Nét',
        category: 'in-theu',
        oldPrice: '25.000đ',
        newPrice: '18.000đ',
        discount: '-28%'
      },
      {
        id: 20,
        driveId: '1C6IOxnWRXnyXAgatVLZjH8DxR-YPXIld',
        name: 'Dịch Vụ Thêu Vi Tính Logo Đồng Phục Độ Chính Xác Cao',
        category: 'in-theu',
        oldPrice: '30.000đ',
        newPrice: '22.000đ',
        discount: '-27%'
      },
      {
        id: 21,
        driveId: '1eURpEJcQ8tQtgwT_od6Ca5HCM2CWpfcz',
        name: 'Mũ Bảo Hộ Lao Động Kỹ Sư Công Nhân Có Núm Vặn Chắc Chắn',
        category: 'in-theu',
        oldPrice: '110.000đ',
        newPrice: '89.000đ',
        discount: '-19%'
      },
      {
        id: 22,
        driveId: '1MNvgD3RDrI_aD3xn3OpjTLX8I7Grcgju',
        name: 'Giày Bảo Hộ Lao Động Mũi Thép Đế Chống Đinh Chống Trượt',
        category: 'in-theu',
        oldPrice: '420.000đ',
        newPrice: '350.000đ',
        discount: '-17%'
      },
      {
        id: 23,
        driveId: '1SACYX7Hq2EN2ZDOGCQPLmVFZaK91zrWz',
        name: 'Găng Tay Và Phụ Kiện Bảo Hộ Lao Động Đồng Bộ Nhà Xưởng',
        category: 'in-theu',
        oldPrice: '65.000đ',
        newPrice: '49.000đ',
        discount: '-25%'
      }
    ];

    // Hàm tạo thẻ HTML cho từng sản phẩm chuẩn Flatsome
    function createProductCardHTML(item) {
      const primaryImg = `https://lh3.googleusercontent.com/d/${item.driveId}`;
      const backupImg = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w700`;
      const fallbackPlaceholder = `https://placehold.co/500x500/f1f5f9/0d3b72?text=Tan+An+Thanh`;

      return `
        <div class="product-card group border border-slate-200 rounded-md bg-white overflow-hidden flex flex-col justify-between hover:shadow-md hover:border-brand transition" data-name="${item.name.toLowerCase()}">
          <div>
            <!-- Khung ảnh sản phẩm + Badge % giảm giá góc trên bên trái giống Flatsome -->
            <div class="relative w-full aspect-square bg-slate-50 overflow-hidden border-b border-slate-100 cursor-pointer" onclick="openProductDetail(${item.id})">
              <span class="badge-sale-flatsome">${item.discount}</span>
              <img 
                src="${primaryImg}" 
                onerror="if(!this.dataset.fb){this.dataset.fb='1';this.src='${backupImg}';}else{this.src='${fallbackPlaceholder}';}"
                alt="${item.name}" 
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              >
            </div>

            <!-- Tên sản phẩm đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ -->
            <div class="p-2 sm:p-2.5">
              <h3 onclick="openProductDetail(${item.id})" class="product-title-full text-xs sm:text-[13px] font-semibold text-slate-800 group-hover:text-brand cursor-pointer">
                ${item.name}
              </h3>
            </div>
          </div>

          <!-- Giá gốc gạch ngang + Giá giảm giá + Nút đặt báo giá -->
          <div class="px-2 pb-2 sm:px-2.5 sm:pb-2.5 pt-1 border-t border-slate-100">
            <div class="flex flex-wrap items-baseline gap-1.5">
              <del class="text-[11px] text-slate-400">${item.oldPrice}</del>
              <span class="text-xs sm:text-sm font-extrabold text-brand-accent">${item.newPrice}</span>
            </div>
            <button 
              onclick="selectProductForQuote(${item.id})" 
              class="mt-1.5 w-full bg-brand hover:bg-brand-light text-white text-[11px] font-bold py-1.5 px-2 rounded transition"
            >
              Nhận Báo Giá Sỉ
            </button>
          </div>
        </div>
      `;
    }

    // Hiển thị toàn bộ 23 sản phẩm vào đúng 4 danh mục
    function renderAllProducts() {
      const categories = ['dong-phuc', 'bao-ho', 'gile-nganh', 'in-theu'];
      categories.forEach(cat => {
        const container = document.getElementById(`grid-${cat}`);
        if (container) {
          const items = productsData.filter(p => p.category === cat);
          container.innerHTML = items.map(createProductCardHTML).join('');
        }
      });
    }

    // Lọc theo danh mục
    function filterCategory(cat) {
      const sections = document.querySelectorAll('[data-cat-section]');
      const statusBox = document.getElementById('filterStatusBox');
      const statusText = document.getElementById('filterStatusText');

      sections.forEach(sec => {
        if (cat === 'all' || sec.getAttribute('data-cat-section') === cat) {
          sec.classList.remove('hidden');
        } else {
          sec.classList.add('hidden');
        }
      });

      if (cat === 'all') {
        statusBox.classList.add('hidden');
      } else {
        statusBox.classList.remove('hidden');
        statusText.textContent = 'Đang hiển thị danh mục đã chọn';
      }
    }

    function resetFilter() {
      filterCategory('all');
      const dInput = document.getElementById('searchInputDesktop');
      const mInput = document.getElementById('searchInputMobile');
      if (dInput) dInput.value = '';
      if (mInput) mInput.value = '';
      handleSearch('');
    }

    // Tìm kiếm sản phẩm trực tiếp
    function handleSearch(query) {
      const q = (query || '').trim().toLowerCase();
      const cards = document.querySelectorAll('.product-card');
      const statusBox = document.getElementById('filterStatusBox');
      const statusText = document.getElementById('filterStatusText');

      let count = 0;
      cards.forEach(card => {
        const name = card.getAttribute('data-name') || '';
        if (!q || name.includes(q)) {
          card.classList.remove('hidden');
          count++;
        } else {
          card.classList.add('hidden');
        }
      });

      if (q) {
        statusBox.classList.remove('hidden');
        statusText.textContent = `Tìm thấy ${count} sản phẩm với từ khóa "${query}"`;
      } else {
        statusBox.classList.add('hidden');
      }
    }

    // Chọn sản phẩm điền xuống Form Báo Giá
    function selectProductForQuote(id) {
      const item = productsData.find(p => p.id === id);
      if (!item) return;
      const noteEl = document.getElementById('qNote');
      if (noteEl) {
        noteEl.value = `Cần báo giá sản phẩm: ${item.name} (Giá tham khảo: ${item.newPrice})`;
      }
      const formSec = document.getElementById('sec-bao-gia');
      if (formSec) {
        formSec.scrollIntoView({ behavior: 'smooth' });
      }
    }

    // Xem chi tiết ảnh sản phẩm trong Modal
    function openProductDetail(id) {
      const item = productsData.find(p => p.id === id);
      if (!item) return;
      const primaryImg = `https://lh3.googleusercontent.com/d/${item.driveId}`;
      const backupImg = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w900`;
      const modal = document.getElementById('customModal');
      const body = document.getElementById('modalBody');

      body.innerHTML = `
        <div class="text-center">
          <div class="relative w-full h-64 sm:h-72 bg-slate-50 rounded overflow-hidden mb-3 border border-slate-200">
            <span class="badge-sale-flatsome">${item.discount}</span>
            <img src="${primaryImg}" onerror="this.src='${backupImg}'" alt="${item.name}" class="w-full h-full object-contain">
          </div>
          <h3 class="text-sm sm:text-base font-bold text-brand">${item.name}</h3>
          <div class="mt-1 flex items-center justify-center gap-2">
            <del class="text-xs text-slate-400">${item.oldPrice}</del>
            <span class="text-base font-extrabold text-brand-accent">${item.newPrice}</span>
          </div>
          <p class="text-xs text-slate-600 mt-2">
            Sản xuất trực tiếp tại Xưởng may Công ty TNHH Tân An Thành. Nhận may đo, phối màu và in thêu logo theo yêu cầu.
          </p>
          <div class="mt-4 flex gap-2 justify-center">
            <button onclick="closeModal(); selectProductForQuote(${item.id});" class="bg-brand-accent text-white text-xs font-bold px-4 py-2 rounded">
              Điền Vào Form Báo Giá
            </button>
            <a href="tel:0983579544" class="bg-brand text-white text-xs font-bold px-4 py-2 rounded">
              Gọi 0983.579.544
            </a>
          </div>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeModal() {
      const modal = document.getElementById('customModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // Xử lý gửi Form Báo Giá (Không dùng alert)
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value;
      const phone = document.getElementById('qPhone').value;
      const cat = document.getElementById('qCategory').value;
      const qty = document.getElementById('qQty').value || 'Chưa xác định';

      const modal = document.getElementById('customModal');
      const body = document.getElementById('modalBody');
      body.innerHTML = `
        <div class="text-center py-2">
          <div class="w-12 h-12 rounded-full bg-green-100 text-green-600 flex items-center justify-center mx-auto mb-2">
            <i class="fa-solid fa-check text-xl"></i>
          </div>
          <h3 class="text-base font-extrabold text-brand">ĐÃ GỬI YÊU CẦU BÁO GIÁ THÀNH CÔNG!</h3>
          <p class="text-xs text-slate-600 mt-2 leading-relaxed">
            Cảm ơn <strong>${name}</strong> (${phone}) đã gửi yêu cầu báo giá danh mục <strong>${cat}</strong> (Số lượng: ${qty}).<br>
            Bộ phận kinh doanh <strong>CÔNG TY TNHH TÂN AN THÀNH</strong> sẽ liên hệ tư vấn ngay!
          </p>
          <div class="mt-3 p-2 bg-slate-50 rounded text-xs text-slate-700">
            Hotline hỗ trợ nhanh: <strong class="text-brand-accent">0983.579.544 - 0983.524.996</strong>
          </div>
          <button onclick="closeModal()" class="mt-4 bg-brand text-white text-xs font-bold px-5 py-2 rounded">
            Đóng thông báo
          </button>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.getElementById('quoteForm').reset();
    }

    // Đóng/mở Menu danh mục trên điện thoại
    function toggleMobileMenu() {
      const overlay = document.getElementById('mobileMenuOverlay');
      const drawer = document.getElementById('mobileMenuDrawer');
      const isHidden = overlay.classList.contains('hidden');
      if (isHidden) {
        overlay.classList.remove('hidden');
        drawer.classList.remove('-translate-x-full');
      } else {
        overlay.classList.add('hidden');
        drawer.classList.add('-translate-x-full');
      }
    }

    // Logic tự trượt 2 ảnh Banner chuyên nghiệp kích thước bằng nhau
    let currentSlideIndex = 0;
    const totalSlides = 2;

    function goToSlide(index) {
      currentSlideIndex = (index + totalSlides) % totalSlides;
      for (let i = 0; i < totalSlides; i++) {
        const slideEl = document.getElementById(`banner-slide-${i}`);
        const dotEl = document.getElementById(`banner-dot-${i}`);
        if (i === currentSlideIndex) {
          slideEl.classList.remove('hidden', 'opacity-0');
          slideEl.classList.add('block', 'opacity-100');
          dotEl.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
        } else {
          slideEl.classList.remove('block', 'opacity-100');
          slideEl.classList.add('hidden', 'opacity-0');
          dotEl.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
        }
      }
    }

    function changeSlide(step) {
      goToSlide(currentSlideIndex + step);
    }

    window.addEventListener('DOMContentLoaded', () => {
      renderAllProducts();
      setInterval(() => {
        changeSlide(1);
      }, 5000);
    });
  </script>
</body>
</html>
