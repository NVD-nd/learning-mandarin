<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luyện Thi TOCFL - Học Tiếng Trung Cho Người Việt</title>
  <meta name="description" content="Hệ thống luyện thi TOCFL hiệu quả nhất cho người Việt, kết hợp công nghệ AI và phương pháp học thông minh">
  <meta name="keywords" content="TOCFL, học tiếng Trung, luyện thi TOCFL, tiếng Trung cho người Việt, HSK, tiếng Hoa">
  
  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tocfl.vn/">
  <meta property="og:title" content="Luyện Thi TOCFL - Học Tiếng Trung Cho Người Việt">
  <meta property="og:description" content="Hệ thống luyện thi TOCFL hiệu quả nhất cho người Việt, kết hợp công nghệ AI và phương pháp học thông minh">
  <meta property="og:image" content="https://tocfl.vn/images/og-image.jpg">

  <!-- Favicon -->
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary-color: #2e7d32;
      --primary-light: #4caf50;
      --primary-dark: #1b5e20;
      --secondary-color: #f57c00;
      --secondary-light: #ff9800;
      --secondary-dark: #e65100;
      --accent-color: #8bc34a;
      --text-color: #212121;
      --text-light: #757575;
      --text-lighter: #9e9e9e;
      --border-color: #e0e0e0;
      --light-bg: #f5f5f5;
      --white: #ffffff;
      --success-color: #689f38;
      --info-color: #0288d1;
      --warning-color: #ffa000;
      --danger-color: #d32f2f;
      --radius-sm: 4px;
      --radius-md: 8px;
      --radius-lg: 12px;
      --shadow-sm: 0 1px 3px rgba(0,0,0,0.12);
      --shadow-md: 0 4px 6px rgba(0,0,0,0.1);
      --shadow-lg: 0 10px 20px rgba(0,0,0,0.1);
      --transition: all 0.3s ease;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Be Vietnam Pro', sans-serif;
      line-height: 1.6;
      color: var(--text-color);
      background-color: var(--light-bg);
      overflow-x: hidden;
    }

    h1, h2, h3, h4, h5, h6 {
      font-weight: 700;
      line-height: 1.3;
      margin-bottom: 1rem;
    }

    h1 { font-size: 2.5rem; }
    h2 { font-size: 2rem; }
    h3 { font-size: 1.75rem; }
    h4 { font-size: 1.5rem; }
    h5 { font-size: 1.25rem; }
    h6 { font-size: 1rem; }

    p {
      margin-bottom: 1rem;
      color: var(--text-light);
    }

    a {
      color: var(--primary-color);
      text-decoration: none;
      transition: var(--transition);
    }

    a:hover {
      color: var(--primary-dark);
    }

    img {
      max-width: 100%;
      height: auto;
    }

    ul, ol {
      margin-bottom: 1rem;
      padding-left: 1.5rem;
    }

    .container {
      width: 100%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 15px;
    }

    .section {
      padding: 80px 0;
    }

    .section-sm {
      padding: 50px 0;
    }

    .section-lg {
      padding: 100px 0;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
    }

    .section-title h2 {
      position: relative;
      display: inline-block;
      padding-bottom: 15px;
    }

    .section-title h2::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 80px;
      height: 4px;
      background: var(--primary-color);
      border-radius: 2px;
    }

    .text-center { text-align: center; }
    .text-left { text-align: left; }
    .text-right { text-align: right; }
    .text-primary { color: var(--primary-color); }
    .text-secondary { color: var(--secondary-color); }
    .text-light { color: var(--text-light); }
    .text-white { color: var(--white); }

    .bg-primary { background-color: var(--primary-color); }
    .bg-secondary { background-color: var(--secondary-color); }
    .bg-light { background-color: var(--light-bg); }
    .bg-white { background-color: var(--white); }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 600;
      text-align: center;
      white-space: nowrap;
      vertical-align: middle;
      user-select: none;
      border: 1px solid transparent;
      padding: 10px 20px;
      font-size: 1rem;
      line-height: 1.5;
      border-radius: var(--radius-md);
      transition: var(--transition);
      cursor: pointer;
    }

    .btn-sm {
      padding: 8px 16px;
      font-size: 0.875rem;
    }

    .btn-lg {
      padding: 12px 24px;
      font-size: 1.125rem;
    }

    .btn-block {
      display: block;
      width: 100%;
    }

    .btn-primary {
      color: var(--white);
      background-color: var(--primary-color);
    }

    .btn-primary:hover {
      background-color: var(--primary-dark);
      color: var(--white);
    }

    .btn-secondary {
      color: var(--white);
      background-color: var(--secondary-color);
    }

    .btn-secondary:hover {
      background-color: var(--secondary-dark);
      color: var(--white);
    }

    .btn-outline {
      color: var(--primary-color);
      background-color: transparent;
      border-color: var(--primary-color);
    }

    .btn-outline:hover {
      color: var(--white);
      background-color: var(--primary-color);
    }

    .card {
      position: relative;
      display: flex;
      flex-direction: column;
      min-width: 0;
      word-wrap: break-word;
      background-color: var(--white);
      background-clip: border-box;
      border: 1px solid var(--border-color);
      border-radius: var(--radius-md);
      box-shadow: var(--shadow-sm);
      transition: var(--transition);
    }

    .card:hover {
      box-shadow: var(--shadow-md);
      transform: translateY(-5px);
    }

    .card-body {
      flex: 1 1 auto;
      padding: 20px;
    }

    .card-title {
      margin-bottom: 15px;
    }

    .progress-bar {
      height: 8px;
      background-color: #e0e0e0;
      border-radius: 4px;
      overflow: hidden;
    }

    .progress {
      height: 100%;
      background-color: var(--primary-color);
      transition: width 0.6s ease;
    }

    /* Navigation */
    .navbar {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 1000;
      background-color: rgba(46, 125, 50, 0.95);
      box-shadow: var(--shadow-sm);
      transition: var(--transition);
    }

    .navbar.scrolled {
      background-color: rgba(46, 125, 50, 0.98);
      box-shadow: var(--shadow-md);
    }

    .navbar-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 0;
    }

    .logo {
      display: flex;
      align-items: center;
      font-size: 1.5rem;
      font-weight: 700;
      color: var(--white);
    }

    .logo i {
      margin-right: 10px;
      font-size: 1.75rem;
    }

    .mobile-menu-btn {
      display: none;
      background: none;
      border: none;
      color: var(--white);
      font-size: 1.5rem;
      cursor: pointer;
    }

    .nav-menu {
      display: flex;
      list-style: none;
    }

    .nav-item {
      margin-left: 20px;
      position: relative;
    }

    .nav-link {
      color: var(--white);
      font-weight: 500;
      display: flex;
      align-items: center;
      padding: 10px 0;
    }

    .nav-link i {
      margin-right: 8px;
    }

    .nav-link::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 0;
      height: 2px;
      background: var(--white);
      transition: var(--transition);
    }

    .nav-link:hover::after,
    .nav-link.active::after {
      width: 100%;
    }

    /* Hero Section */
    .hero {
      position: relative;
      min-height: 100vh;
      display: flex;
      align-items: center;
      background: linear-gradient(135deg, #f5f5f5 0%, #e8f5e9 100%);
      padding-top: 80px;
    }

    .hero-content {
      position: relative;
      z-index: 2;
      max-width: 600px;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
      line-height: 1.2;
    }

    .hero p {
      font-size: 1.25rem;
      margin-bottom: 30px;
      color: var(--text-light);
    }

    .hero-buttons {
      display: flex;
      gap: 15px;
      margin-bottom: 40px;
    }

    .hero-stats {
      display: flex;
      gap: 15px;
    }

    .stat-card {
      display: flex;
      align-items: center;
      background: rgba(255, 255, 255, 0.9);
      padding: 15px;
      border-radius: var(--radius-md);
      box-shadow: var(--shadow-sm);
    }

    .stat-card i {
      font-size: 1.5rem;
      margin-right: 15px;
      color: var(--primary-color);
    }

    .stat-card span {
      font-size: 1.25rem;
      font-weight: 700;
      display: block;
    }

    .stat-card small {
      font-size: 0.875rem;
      color: var(--text-light);
    }

    /* Features Section */
    .feature-card {
      height: 100%;
      text-align: center;
      padding: 30px 20px;
      border-radius: var(--radius-md);
      transition: var(--transition);
    }

    .feature-icon {
      width: 80px;
      height: 80px;
      margin: 0 auto 20px;
      background-color: rgba(76, 175, 80, 0.1);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 2rem;
      color: var(--primary-color);
    }

    /* TOCFL Levels */
    .level-card {
      height: 100%;
      text-align: center;
      padding: 30px;
      border-radius: var(--radius-md);
      transition: var(--transition);
    }

    .level-badge {
      display: inline-block;
      padding: 5px 15px;
      background-color: var(--primary-color);
      color: var(--white);
      border-radius: 20px;
      font-weight: 600;
      margin-bottom: 15px;
    }

    .level-progress {
      width: 120px;
      height: 120px;
      margin: 0 auto 20px;
      position: relative;
    }

    .level-progress svg {
      width: 100%;
      height: 100%;
    }

    .level-progress circle {
      fill: none;
      stroke-width: 8;
      stroke-linecap: round;
      transform: rotate(-90deg);
      transform-origin: 50% 50%;
    }

    .progress-bg {
      stroke: #e0e0e0;
    }

    .progress-fill {
      stroke: var(--primary-color);
      stroke-dasharray: 283;
      stroke-dashoffset: 283;
    }

    .progress-text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 1.5rem;
      font-weight: 700;
    }

    /* Practice Section */
    .practice-card {
      height: 100%;
      padding: 0;
      overflow: hidden;
    }

    .practice-image {
      height: 180px;
      background-size: cover;
      background-position: center;
      position: relative;
    }

    .practice-content {
      padding: 20px;
    }

    .practice-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin: 15px 0;
      font-size: 0.875rem;
      color: var(--text-light);
    }

    .practice-meta span {
      display: flex;
      align-items: center;
    }

    .practice-meta i {
      margin-right: 5px;
    }

    /* Testimonial Section */
    .testimonial-card {
      padding: 30px;
      border-radius: var(--radius-md);
    }

    .testimonial-author {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }

    .testimonial-author img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 15px;
    }

    .testimonial-rating {
      color: var(--secondary-color);
    }

    /* Pricing Section */
    .pricing-card {
      height: 100%;
      padding: 30px;
      text-align: center;
      border-radius: var(--radius-md);
    }

    .pricing-card.popular {
      border-top: 4px solid var(--primary-color);
    }

    .pricing-card.premium {
      border-top: 4px solid var(--secondary-color);
    }

    .popular-badge {
      position: absolute;
      top: 0;
      right: 30px;
      transform: translateY(-50%);
      background-color: var(--primary-color);
      color: var(--white);
      padding: 5px 15px;
      border-radius: 20px;
      font-size: 0.75rem;
      font-weight: 700;
    }

    .price {
      margin: 20px 0;
    }

    .price span {
      font-size: 2.5rem;
      font-weight: 700;
      color: var(--primary-color);
    }

    .price small {
      font-size: 1rem;
      color: var(--text-light);
    }

    .pricing-features {
      margin: 30px 0;
      text-align: left;
    }

    .pricing-features li {
      margin-bottom: 10px;
      display: flex;
      align-items: center;
    }

    .pricing-features i {
      margin-right: 10px;
      width: 20px;
      text-align: center;
    }

    .pricing-features .fa-check {
      color: var(--success-color);
    }

    .pricing-features .fa-times {
      color: var(--danger-color);
    }

    /* Footer */
    .footer {
      background-color: #263238;
      color: var(--white);
      padding: 80px 0 0;
    }

    .footer-logo {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
      font-size: 1.5rem;
      font-weight: 700;
    }

    .footer-logo i {
      margin-right: 10px;
      font-size: 1.75rem;
    }

    .footer-about p {
      color: rgba(255, 255, 255, 0.7);
      margin-bottom: 20px;
    }

    .footer-social {
      display: flex;
      gap: 10px;
    }

    .social-icon {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.1);
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--white);
      transition: var(--transition);
    }

    .social-icon:hover {
      background: var(--primary-color);
      color: var(--white);
      transform: translateY(-3px);
    }

    .footer-links h4 {
      color: var(--white);
      margin-bottom: 20px;
      font-size: 1.125rem;
    }

    .footer-links ul {
      list-style: none;
    }

    .footer-links li {
      margin-bottom: 10px;
    }

    .footer-links a {
      color: rgba(255, 255, 255, 0.7);
      transition: var(--transition);
    }

    .footer-links a:hover {
      color: var(--white);
    }

    .footer-bottom {
      padding: 20px 0;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      margin-top: 50px;
    }

    .footer-copyright {
      color: rgba(255, 255, 255, 0.5);
      font-size: 0.875rem;
    }

    /* Back to Top */
    .back-to-top {
      position: fixed;
      bottom: 30px;
      right: 30px;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background: var(--primary-color);
      color: var(--white);
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      opacity: 0;
      visibility: hidden;
      transition: var(--transition);
      z-index: 999;
      box-shadow: var(--shadow-md);
    }

    .back-to-top.show {
      opacity: 1;
      visibility: visible;
    }

    .back-to-top:hover {
      background: var(--primary-dark);
      transform: translateY(-3px);
    }

    /* Responsive Styles */
    @media (max-width: 992px) {
      .hero h1 {
        font-size: 2.5rem;
      }
      
      .hero-content {
        text-align: center;
        max-width: 100%;
      }
      
      .hero-buttons {
        justify-content: center;
      }
      
      .hero-stats {
        justify-content: center;
      }
    }

    @media (max-width: 768px) {
      .section {
        padding: 60px 0;
      }
      
      .section-lg {
        padding: 80px 0;
      }
      
      .mobile-menu-btn {
        display: block;
      }
      
      .nav-menu {
        position: fixed;
        top: 80px;
        left: 0;
        right: 0;
        background: var(--white);
        box-shadow: var(--shadow-lg);
        padding: 20px;
        flex-direction: column;
        align-items: flex-start;
        opacity: 0;
        visibility: hidden;
        transform: translateY(-20px);
        transition: var(--transition);
      }
      
      .nav-menu.active {
        opacity: 1;
        visibility: visible;
        transform: translateY(0);
      }
      
      .nav-item {
        margin-left: 0;
        margin-bottom: 15px;
        width: 100%;
      }
      
      .nav-link {
        color: var(--text-color);
        padding: 10px 0;
      }
      
      .nav-link::after {
        background: var(--primary-color);
      }
    }

    @media (max-width: 576px) {
      .hero h1 {
        font-size: 2rem;
      }
      
      .hero p {
        font-size: 1rem;
      }
      
      .hero-buttons {
        flex-direction: column;
        gap: 10px;
      }
      
      .hero-stats {
        flex-direction: column;
        gap: 10px;
      }
      
      .stat-card {
        justify-content: center;
      }
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <header class="navbar">
    <div class="container navbar-container">
      <a href="#" class="logo">
        <i class="fas fa-language"></i>
        <span>TOCFL Việt Nam</span>
      </a>

      <button class="mobile-menu-btn">
        <i class="fas fa-bars"></i>
      </button>

      <ul class="nav-menu">
        <li class="nav-item"><a href="#" class="nav-link active"><i class="fas fa-home"></i> Trang Chủ</a></li>
        <li class="nav-item"><a href="#features" class="nav-link"><i class="fas fa-star"></i> Tính Năng</a></li>
        <li class="nav-item"><a href="#tocfl" class="nav-link"><i class="fas fa-graduation-cap"></i> Luyện Thi TOCFL</a></li>
        <li class="nav-item"><a href="#practice" class="nav-link"><i class="fas fa-book-open"></i> Bài Tập</a></li>
        <li class="nav-item"><a href="#pricing" class="nav-link"><i class="fas fa-crown"></i> Gói Học</a></li>
        <li class="nav-item"><a href="#contact" class="nav-link"><i class="fas fa-envelope"></i> Liên Hệ</a></li>
        <li class="nav-item"><a href="#" class="nav-link btn btn-outline btn-sm"><i class="fas fa-sign-in-alt"></i> Đăng Nhập</a></li>
      </ul>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <h1>Luyện Thi TOCFL Hiệu Quả Cho Người Việt</h1>
        <p>Hệ thống học tiếng Trung thông minh kết hợp công nghệ AI, giúp bạn đạt điểm cao trong kỳ thi TOCFL một cách dễ dàng.</p>
        
        <div class="hero-buttons">
          <a href="#pricing" class="btn btn-primary btn-lg">
            <i class="fas fa-rocket"></i> Bắt Đầu Ngay
          </a>
          <a href="#features" class="btn btn-outline btn-lg">
            <i class="fas fa-play-circle"></i> Xem Tính Năng
          </a>
        </div>
        
        <div class="hero-stats">
          <div class="stat-card">
            <i class="fas fa-users"></i>
            <div>
              <span>+10,000</span>
              <small>Học Viên</small>
            </div>
          </div>
          <div class="stat-card">
            <i class="fas fa-chart-line"></i>
            <div>
              <span>95%</span>
              <small>Đỗ TOCFL</small>
            </div>
          </div>
          <div class="stat-card">
            <i class="fas fa-clock"></i>
            <div>
              <span>2x</span>
              <small>Tiết Kiệm Thời Gian</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="section bg-light">
    <div class="container">
      <div class="section-title">
        <h2>Tính Năng Nổi Bật</h2>
        <p>Công nghệ học tập tiên tiến dành riêng cho người Việt học TOCFL</p>
      </div>
      
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="feature-card card">
            <div class="feature-icon">
              <i class="fas fa-robot"></i>
            </div>
            <h3>Trợ Lý AI</h3>
            <p>Hệ thống AI thông minh giúp bạn luyện tập mọi lúc, sửa lỗi phát âm và ngữ pháp ngay lập tức.</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="feature-card card">
            <div class="feature-icon">
              <i class="fas fa-headphones"></i>
            </div>
            <h3>Luyện Nghe Chuẩn</h3>
            <p>Hàng trăm bài luyện nghe với giọng đọc chuẩn Đài Loan, có phụ đề và giải thích chi tiết.</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="feature-card card">
            <div class="feature-icon">
              <i class="fas fa-book"></i>
            </div>
            <h3>Từ Vựng Thông Minh</h3>
            <p>Học từ vựng theo chủ đề TOCFL với hình ảnh, ví dụ và hệ thống ôn tập khoa học.</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="feature-card card">
            <div class="feature-icon">
              <i class="fas fa-clipboard-check"></i>
            </div>
            <h3>Đề Thi Thử</h3>
            <p>Ngân hàng đề thi thử TOCFL đầy đủ các cấp độ, mô phỏng kỳ thi thực tế.</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="feature-card card">
            <div class="feature-icon">
              <i class="fas fa-chart-line"></i>
            </div>
            <h3>Theo Dõi Tiến Độ</h3>
            <p>Hệ thống phân tích điểm mạnh, yếu và đề xuất lộ trình học tập cá nhân hóa.</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="feature-card card">
            <div class="feature-icon">
              <i class="fas fa-mobile-alt"></i>
            </div>
            <h3>Học Mọi Lúc</h3>
            <p>Ứng dụng di động cho phép bạn học mọi lúc mọi nơi, đồng bộ trên mọi thiết bị.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- TOCFL Levels Section -->
  <section id="tocfl" class="section">
    <div class="container">
      <div class="section-title">
        <h2>Các Cấp Độ TOCFL</h2>
        <p>Hệ thống luyện thi toàn diện cho mọi trình độ</p>
      </div>
      
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="level-card card">
            <div class="level-badge">Band A</div>
            <h3>TOCFL Cấp 1-2</h3>
            <p>Dành cho người mới bắt đầu học tiếng Trung</p>
            
            <div class="level-progress">
              <svg>
                <circle class="progress-bg" cx="60" cy="60" r="54"></circle>
                <circle class="progress-fill" cx="60" cy="60" r="54"></circle>
              </svg>
              <div class="progress-text">85%</div>
            </div>
            
            <div class="d-flex justify-content-between mb-3">
              <div>
                <h5>300</h5>
                <small>Từ Vựng</small>
              </div>
              <div>
                <h5>40</h5>
                <small>Bài Học</small>
              </div>
              <div>
                <h5>5</h5>
                <small>Đề Thi</small>
              </div>
            </div>
            
            <a href="#" class="btn btn-primary btn-block">Bắt Đầu Học</a>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="level-card card">
            <div class="level-badge">Band B</div>
            <h3>TOCFL Cấp 3-4</h3>
            <p>Dành cho người có trình độ trung cấp</p>
            
            <div class="level-progress">
              <svg>
                <circle class="progress-bg" cx="60" cy="60" r="54"></circle>
                <circle class="progress-fill" cx="60" cy="60" r="54"></circle>
              </svg>
              <div class="progress-text">72%</div>
            </div>
            
            <div class="d-flex justify-content-between mb-3">
              <div>
                <h5>1200</h5>
                <small>Từ Vựng</small>
              </div>
              <div>
                <h5>60</h5>
                <small>Bài Học</small>
              </div>
              <div>
                <h5>8</h5>
                <small>Đề Thi</small>
              </div>
            </div>
            
            <a href="#" class="btn btn-primary btn-block">Bắt Đầu Học</a>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="level-card card">
            <div class="level-badge">Band C</div>
            <h3>TOCFL Cấp 5-6</h3>
            <p>Dành cho người có trình độ cao cấp</p>
            
            <div class="level-progress">
              <svg>
                <circle class="progress-bg" cx="60" cy="60" r="54"></circle>
                <circle class="progress-fill" cx="60" cy="60" r="54"></circle>
              </svg>
              <div class="progress-text">65%</div>
            </div>
            
            <div class="d-flex justify-content-between mb-3">
              <div>
                <h5>2500</h5>
                <small>Từ Vựng</small>
              </div>
              <div>
                <h5>80</h5>
                <small>Bài Học</small>
              </div>
              <div>
                <h5>10</h5>
                <small>Đề Thi</small>
              </div>
            </div>
            
            <a href="#" class="btn btn-primary btn-block">Bắt Đầu Học</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Practice Section -->
  <section id="practice" class="section bg-light">
    <div class="container">
      <div class="section-title">
        <h2>Bài Tập Mẫu</h2>
        <p>Luyện tập với các dạng bài thi TOCFL thực tế</p>
      </div>
      
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="practice-card card">
            <div class="practice-image" style="background-image: url('https://images.unsplash.com/photo-1547981609-4b6bfe67ca0b?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80')"></div>
            <div class="practice-content">
              <h3>Luyện Nghe Cấp 3</h3>
              <p>Luyện nghe với các đoạn hội thoại hàng ngày trong đề thi TOCFL Band B.</p>
              
              <div class="practice-meta">
                <span><i class="fas fa-question-circle"></i> 20 Câu Hỏi</span>
                <span><i class="fas fa-clock"></i> 30 Phút</span>
              </div>
              
              <a href="#" class="btn btn-primary btn-block">Làm Bài Ngay</a>
            </div>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="practice-card card">
            <div class="practice-image" style="background-image: url('https://images.unsplash.com/photo-1501504905252-473c47e087f8?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80')"></div>
            <div class="practice-content">
              <h3>Đọc Hiểu Cấp 4</h3>
              <p>Luyện đọc hiểu với các bài báo, thông báo trong đề thi TOCFL Band B.</p>
              
              <div class="practice-meta">
                <span><i class="fas fa-question-circle"></i> 25 Câu Hỏi</span>
                <span><i class="fas fa-clock"></i> 40 Phút</span>
              </div>
              
              <a href="#" class="btn btn-primary btn-block">Làm Bài Ngay</a>
            </div>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="practice-card card">
            <div class="practice-image" style="background-image: url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80')"></div>
            <div class="practice-content">
              <h3>Từ Vựng Cấp 2</h3>
              <p>Ôn tập từ vựng thường xuất hiện trong đề thi TOCFL Band A.</p>
              
              <div class="practice-meta">
                <span><i class="fas fa-question-circle"></i> 50 Câu Hỏi</span>
                <span><i class="fas fa-clock"></i> 25 Phút</span>
              </div>
              
              <a href="#" class="btn btn-primary btn-block">Làm Bài Ngay</a>
            </div>
          </div>
        </div>
      </div>
      
      <div class="text-center mt-4">
        <a href="#" class="btn btn-outline btn-lg">
          <i class="fas fa-book-open"></i> Xem Thêm Bài Tập
        </a>
      </div>
    </div>
  </section>

  <!-- Testimonial Section -->
  <section class="section">
    <div class="container">
      <div class="section-title">
        <h2>Học Viên Nói Gì Về Chúng Tôi</h2>
        <p>Những câu chuyện thành công từ học viên của TOCFL Việt Nam</p>
      </div>
      
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="testimonial-card card">
            <div class="testimonial-author">
              <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="Nguyễn Thị Hồng">
              <div>
                <h5>Nguyễn Thị Hồng</h5>
                <div class="testimonial-rating">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
              </div>
            </div>
            <p>"Nhờ luyện tập với hệ thống này, mình đã đạt TOCFL cấp 4 chỉ sau 3 tháng. Các bài luyện nghe rất sát với đề thi thực tế."</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="testimonial-card card">
            <div class="testimonial-author">
              <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Trần Văn Nam">
              <div>
                <h5>Trần Văn Nam</h5>
                <div class="testimonial-rating">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                </div>
              </div>
            </div>
            <p>"Trợ lý AI giúp mình luyện phát âm rất hiệu quả. Mình đã cải thiện được điểm số phần thi nói từ 50 lên 85 điểm."</p>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="testimonial-card card">
            <div class="testimonial-author">
              <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Lê Thị Mai">
              <div>
                <h5>Lê Thị Mai</h5>
                <div class="testimonial-rating">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star-half-alt"></i>
                </div>
              </div>
            </div>
            <p>"Hệ thống từ vựng thông minh giúp mình nhớ từ rất lâu. Mình đã học được hơn 1000 từ trong 2 tháng mà không cảm thấy áp lực."</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Section -->
  <section id="pricing" class="section bg-light">
    <div class="container">
      <div class="section-title">
        <h2>Chọn Gói Học Phù Hợp</h2>
        <p>Đầu tư cho tương lai của bạn với chi phí hợp lý nhất</p>
      </div>
      
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="pricing-card card">
            <div class="pricing-header">
              <h3>Cơ Bản</h3>
              <div class="price">
                <span>0đ</span>
                <small>/tháng</small>
              </div>
              <p>Dành cho người mới bắt đầu</p>
            </div>
            
            <ul class="pricing-features">
              <li><i class="fas fa-check"></i> 10 bài học mỗi ngày</li>
              <li><i class="fas fa-check"></i> TOCFL Band A</li>
              <li><i class="fas fa-check"></i> 2 đề thi thử</li>
              <li><i class="fas fa-times"></i> Trợ lý AI</li>
              <li><i class="fas fa-times"></i> Lộ trình cá nhân</li>
              <li><i class="fas fa-times"></i> Hỗ trợ giáo viên</li>
            </ul>
            
            <a href="#" class="btn btn-outline btn-block">Đăng Ký Ngay</a>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="pricing-card card popular">
            <div class="popular-badge">Phổ Biến</div>
            <div class="pricing-header">
              <h3>Nâng Cao</h3>
              <div class="price">
                <span>499.000đ</span>
                <small>/tháng</small>
              </div>
              <p>Dành cho người nghiêm túc</p>
            </div>
            
            <ul class="pricing-features">
              <li><i class="fas fa-check"></i> Không giới hạn bài học</li>
              <li><i class="fas fa-check"></i> TOCFL Band A-B</li>
              <li><i class="fas fa-check"></i> 10 đề thi thử</li>
              <li><i class="fas fa-check"></i> Trợ lý AI cơ bản</li>
              <li><i class="fas fa-check"></i> Lộ trình cá nhân</li>
              <li><i class="fas fa-times"></i> Hỗ trợ giáo viên</li>
            </ul>
            
            <a href="#" class="btn btn-primary btn-block">Đăng Ký Ngay</a>
          </div>
        </div>
        
        <div class="col-md-4 mb-4">
          <div class="pricing-card card premium">
            <div class="pricing-header">
              <h3>Chuyên Sâu</h3>
              <div class="price">
                <span>899.000đ</span>
                <small>/tháng</small>
              </div>
              <p>Dành cho người học chuyên nghiệp</p>
            </div>
            
            <ul class="pricing-features">
              <li><i class="fas fa-check"></i> Không giới hạn bài học</li>
              <li><i class="fas fa-check"></i> TOCFL Band A-C</li>
              <li><i class="fas fa-check"></i> 20 đề thi thử</li>
              <li><i class="fas fa-check"></i> Trợ lý AI nâng cao</li>
              <li><i class="fas fa-check"></i> Lộ trình cá nhân</li>
              <li><i class="fas fa-check"></i> Hỗ trợ giáo viên</li>
            </ul>
            
            <a href="#" class="btn btn-primary btn-block">Đăng Ký Ngay</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section">
    <div class="container">
      <div class="section-title">
        <h2>Liên Hệ Với Chúng Tôi</h2>
        <p>Chúng tôi luôn sẵn sàng hỗ trợ bạn</p>
      </div>
      
      <div class="row">
        <div class="col-md-6 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h4 class="mb-4">Thông Tin Liên Hệ</h4>
              
              <div class="d-flex align-items-start mb-4">
                <i class="fas fa-map-marker-alt text-primary mt-1 me-3"></i>
                <div>
                  <h5>Địa Chỉ</h5>
                  <p class="mb-0">123 Đường ABC, Quận 1, TP.HCM</p>
                </div>
              </div>
              
              <div class="d-flex align-items-start mb-4">
                <i class="fas fa-phone-alt text-primary mt-1 me-3"></i>
                <div>
                  <h5>Điện Thoại</h5>
                  <p class="mb-0">+84 123 456 789</p>
                </div>
              </div>
              
              <div class="d-flex align-items-start mb-4">
                <i class="fas fa-envelope text-primary mt-1 me-3"></i>
                <div>
                  <h5>Email</h5>
                  <p class="mb-0">support@tocfl.vn</p>
                </div>
              </div>
              
              <div class="d-flex align-items-start">
                <i class="fas fa-clock text-primary mt-1 me-3"></i>
                <div>
                  <h5>Giờ Làm Việc</h5>
                  <p class="mb-0">Thứ 2 - Thứ 6: 8:00 - 17:00</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="col-md-6 mb-4">
          <div class="card h-100">
            <div class="card-body">
              <h4 class="mb-4">Gửi Tin Nhắn</h4>
              
              <form>
                <div class="mb-3">
                  <label for="name" class="form-label">Họ Tên</label>
                  <input type="text" class="form-control" id="name" placeholder="Nhập họ tên của bạn">
                </div>
                
                <div class="mb-3">
                  <label for="email" class="form-label">Email</label>
                  <input type="email" class="form-control" id="email" placeholder="Nhập email của bạn">
                </div>
                
                <div class="mb-3">
                  <label for="subject" class="form-label">Chủ Đề</label>
                  <input type="text" class="form-control" id="subject" placeholder="Nhập chủ đề">
                </div>
                
                <div class="mb-3">
                  <label for="message" class="form-label">Nội Dung</label>
                  <textarea class="form-control" id="message" rows="4" placeholder="Nhập nội dung tin nhắn"></textarea>
                </div>
                
                <button type="submit" class="btn btn-primary">Gửi Tin Nhắn</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="footer-logo">
            <i class="fas fa-language"></i>
            <span>TOCFL Việt Nam</span>
          </div>
          <p>Hệ thống luyện thi TOCFL hiệu quả nhất cho người Việt, kết hợp công nghệ AI và phương pháp học thông minh.</p>
          
          <div class="footer-social">
            <a href="#" class="social-icon"><i class="fab fa-facebook-f"></i></a>
            <a href="#" class="social-icon"><i class="fab fa-youtube"></i></a>
            <a href="#" class="social-icon"><i class="fab fa-tiktok"></i></a>
            <a href="#" class="social-icon"><i class="fab fa-zalo"></i></a>
          </div>
        </div>
        
        <div class="col-md-2 mb-4">
          <h4>Liên Kết</h4>
          <ul>
            <li><a href="#">Trang Chủ</a></li>
            <li><a href="#features">Tính Năng</a></li>
            <li><a href="#tocfl">TOCFL</a></li>
            <li><a href="#practice">Bài Tập</a></li>
            <li><a href="#pricing">Gói Học</a></li>
          </ul>
        </div>
        
        <div class="col-md-2 mb-4">
          <h4>Tài Nguyên</h4>
          <ul>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Tài Liệu</a></li>
            <li><a href="#">Đề Thi Mẫu</a></li>
            <li><a href="#">Từ Điển</a></li>
            <li><a href="#">Hỏi Đáp</a></li>
          </ul>
        </div>
        
        <div class="col-md-4 mb-4">
          <h4>Đăng Ký Nhận Tin</h4>
          <p>Nhận thông tin khóa học mới và tài liệu miễn phí.</p>
          
          <form class="d-flex">
            <input type="email" class="form-control me-2" placeholder="Nhập email của bạn">
            <button type="submit" class="btn btn-primary">
              <i class="fas fa-paper-plane"></i>
            </button>
          </form>
          
          <div class="mt-3">
            <h5>Tải Ứng Dụng</h5>
            <div class="d-flex">
              <a href="#" class="btn btn-outline btn-sm me-2">
                <i class="fab fa-apple"></i> App Store
              </a>
              <a href="#" class="btn btn-outline btn-sm">
                <i class="fab fa-google-play"></i> Google Play
              </a>
            </div>
          </div>
        </div>
      </div>
      
      <div class="footer-bottom">
        <div class="footer-copyright">
          <p>&copy; 2023 TOCFL Việt Nam. Bảo lưu mọi quyền.</p>
        </div>
        
        <div class="d-flex">
          <a href="#" class="me-3">Điều Khoản</a>
          <a href="#">Chính Sách Bảo Mật</a>
        </div>
      </div>
    </div>
  </footer>

  <!-- Back to Top -->
  <div class="back-to-top">
    <i class="fas fa-arrow-up"></i>
  </div>

  <!-- Scripts -->
  <script>
    // Mobile Menu Toggle
    document.querySelector('.mobile-menu-btn').addEventListener('click', function() {
      document.querySelector('.nav-menu').classList.toggle('active');
      this.classList.toggle('active');
    });

    // Navbar Scroll Effect
    window.addEventListener('scroll', function() {
      const navbar = document.querySelector('.navbar');
      if (window.scrollY > 50) {
        navbar.classList.add('scrolled');
      } else {
        navbar.classList.remove('scrolled');
      }
    });

    // Back to Top Button
    window.addEventListener('scroll', function() {
      const backToTop = document.querySelector('.back-to-top');
      if (window.pageYOffset > 300) {
        backToTop.classList.add('show');
      } else {
        backToTop.classList.remove('show');
      }
    });

    document.querySelector('.back-to-top').addEventListener('click', function(e) {
      e.preventDefault();
      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });
    });

    // Smooth Scrolling for Anchor Links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        if (targetId === '#') return;
        
        const targetElement = document.querySelector(targetId);
        if (targetElement) {
          window.scrollTo({
            top: targetElement.offsetTop - 80,
            behavior: 'smooth'
          });
        }
      });
    });

    // Animate Progress Circles
    document.addEventListener('DOMContentLoaded', function() {
      const progressCircles = document.querySelectorAll('.progress-fill');
      
      progressCircles.forEach(circle => {
        const progress = parseInt(circle.parentElement.parentElement.querySelector('.progress-text').textContent);
        const radius = circle.r.baseVal.value;
        const circumference = 2 * Math.PI * radius;
        const offset = circumference - (progress / 100) * circumference;
        
        circle.style.strokeDasharray = `${circumference} ${circumference}`;
        circle.style.strokeDashoffset = circumference;
        
        setTimeout(() => {
          circle.style.transition = 'stroke-dashoffset 1.5s ease-in-out';
          circle.style.strokeDashoffset = offset;
        }, 100);
      });
    });

    // Form Validation
    document.querySelectorAll('form').forEach(form => {
      form.addEventListener('submit', function(e) {
        e.preventDefault();
        
        const inputs = this.querySelectorAll('input[required], textarea[required]');
        let isValid = true;
        
        inputs.forEach(input => {
          if (!input.value.trim()) {
            isValid = false;
            input.classList.add('is-invalid');
          } else {
            input.classList.remove('is-invalid');
          }
        });
        
        if (isValid) {
          // Form is valid, submit it
          alert('Cảm ơn bạn! Chúng tôi sẽ liên hệ với bạn sớm nhất.');
          this.reset();
        }
      });
    });
  </script>
</body>
</html>
