<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة الرفاه للحوالات المالية - تحويل أموال آمن وسريع</title>
    <meta name="description" content="شركة الرفاه تقدم خدمات الحوالات المالية بين تركيا وسوريا بأسعار تنافسية وخدمة مميزة">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #0E1831;
            --secondary-color: #1a2a57;
            --gold: #D4AF37;
            --light-gold: #f5d062;
            --dark-gold: #b8860b;
            --white: #ffffff;
            --light-gray: #f5f7fa;
            --dark-gray: #4a5568;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }
        
        body {
            background-color: var(--light-gray);
            color: var(--primary-color);
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(rgba(14, 24, 49, 0.9), rgba(14, 24, 49, 0.9)), url('https://images.unsplash.com/photo-1566378246598-5b11a0ed4868?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
            color: var(--white);
            padding: 2rem 1rem;
            text-align: center;
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            position: relative;
        }
        
        .header-content {
            max-width: 800px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }
        
        .logo {
            width: 150px;
            margin-bottom: 1.5rem;
        }
        
        nav {
            background-color: var(--primary-color);
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        nav .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .nav-logo {
            color: var(--gold);
            font-weight: bold;
            font-size: 1.5rem;
            text-decoration: none;
        }
        
        .nav-logo span {
            color: var(--white);
        }
        
        .nav-links {
            display: flex;
            list-style: none;
        }
        
        .nav-links li {
            margin: 0 0.5rem;
        }
        
        .nav-links a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: all 0.3s;
            display: flex;
            align-items: center;
        }
        
        .nav-links a:hover {
            background-color: var(--gold);
            color: var(--primary-color);
        }
        
        .nav-links a i {
            margin-left: 5px;
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: var(--white);
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            position: relative;
        }
        
        .section-title h2 {
            font-size: 2rem;
            color: var(--primary-color);
            display: inline-block;
            padding-bottom: 0.5rem;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            width: 50px;
            height: 3px;
            background-color: var(--gold);
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .hero {
            text-align: center;
        }
        
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--white);
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            color: rgba(255, 255, 255, 0.9);
        }
        
        .btn {
            display: inline-block;
            background-color: var(--gold);
            color: var(--primary-color);
            padding: 0.8rem 2rem;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
            border: 2px solid var(--gold);
            margin: 0.5rem;
        }
        
        .btn:hover {
            background-color: transparent;
            color: var(--gold);
        }
        
        .btn-outline {
            background-color: transparent;
            color: var(--gold);
            border: 2px solid var(--gold);
        }
        
        .btn-outline:hover {
            background-color: var(--gold);
            color: var(--primary-color);
        }
        
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 4rem;
        }
        
        .service-card {
            background-color: var(--white);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
            border-top: 4px solid var(--gold);
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
        }
        
        .service-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .service-content {
            padding: 1.5rem;
        }
        
        .service-card h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }
        
        .service-card p {
            color: var(--dark-gray);
            margin-bottom: 1.5rem;
        }
        
        .exchange-rate {
            background-color: var(--white);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 4rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1.5rem;
        }
        
        th, td {
            padding: 1rem;
            text-align: right;
            border-bottom: 1px solid #eee;
        }
        
        th {
            background-color: var(--primary-color);
            color: var(--white);
            font-weight: 500;
        }
        
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        
        tr:hover {
            background-color: #f1f1f1;
        }
        
        .rate-highlight {
            color: var(--gold);
            font-weight: bold;
        }
        
        .branches {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 4rem;
        }
        
        .branch-card {
            background-color: var(--white);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .branch-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .branch-content {
            padding: 1.5rem;
        }
        
        .branch-card h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            font-size: 1.3rem;
        }
        
        .branch-info {
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
        }
        
        .branch-info i {
            color: var(--gold);
            margin-left: 0.5rem;
            width: 20px;
            text-align: center;
        }
        
        .contact {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 4rem;
        }
        
        .contact-info {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 2rem;
            border-radius: 10px;
        }
        
        .contact-info h3 {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            color: var(--gold);
        }
        
        .contact-item {
            margin-bottom: 1.5rem;
            display: flex;
            align-items: flex-start;
        }
        
        .contact-item i {
            color: var(--gold);
            font-size: 1.2rem;
            margin-left: 0.8rem;
            margin-top: 3px;
        }
        
        .contact-form {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
            color: var(--primary-color);
        }
        
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
            transition: border-color 0.3s;
        }
        
        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            border-color: var(--gold);
            outline: none;
        }
        
        textarea {
            resize: vertical;
            min-height: 120px;
        }
        
        .form-btn {
            width: 100%;
            padding: 0.8rem;
            background-color: var(--gold);
            color: var(--primary-color);
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .form-btn:hover {
            background-color: var(--dark-gold);
        }
        
        footer {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 3rem 0 1.5rem;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1.5rem;
        }
        
        .footer-column h3 {
            color: var(--gold);
            margin-bottom: 1.5rem;
            font-size: 1.3rem;
            position: relative;
            padding-bottom: 0.5rem;
        }
        
        .footer-column h3::after {
            content: '';
            position: absolute;
            width: 40px;
            height: 2px;
            background-color: var(--gold);
            bottom: 0;
            right: 0;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 0.8rem;
        }
        
        .footer-links a {
            color: var(--white);
            text-decoration: none;
            transition: color 0.3s;
            display: flex;
            align-items: center;
        }
        
        .footer-links a:hover {
            color: var(--gold);
        }
        
        .footer-links a i {
            margin-left: 0.5rem;
            font-size: 0.8rem;
        }
        
        .social-links {
            display: flex;
            margin-top: 1.5rem;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            color: var(--white);
            border-radius: 50%;
            margin-left: 0.5rem;
            transition: all 0.3s;
        }
        
        .social-links a:hover {
            background-color: var(--gold);
            color: var(--primary-color);
            transform: translateY(-3px);
        }
        
        .copyright {
            text-align: center;
            padding-top: 2rem;
            margin-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.7);
            font-size: 0.9rem;
        }
        
        /* Transfer Form Styles */
        .transfer-form {
            background-color: var(--white);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 4rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .transfer-form h3 {
            color: var(--primary-color);
            margin-bottom: 1.5rem;
            text-align: center;
            font-size: 1.5rem;
        }
        
        .form-row {
            display: flex;
            flex-wrap: wrap;
            margin: 0 -1rem;
        }
        
        .form-col {
            flex: 1;
            min-width: 250px;
            padding: 0 1rem;
        }
        
        .transfer-summary {
            background-color: #f8f9fa;
            border-radius: 8px;
            padding: 1.5rem;
            margin-top: 1.5rem;
            border: 1px solid #eee;
        }
        
        .transfer-summary h4 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            border-bottom: 1px solid #ddd;
            padding-bottom: 0.5rem;
        }
        
        .summary-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.5rem;
        }
        
        .summary-item.total {
            font-weight: bold;
            margin-top: 1rem;
            padding-top: 1rem;
            border-top: 1px solid #ddd;
        }
        
        /* Animation Classes */
        .fade-in {
            animation: fadeIn 1s ease-in;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        .slide-up {
            animation: slideUp 1s ease-out;
        }
        
        @keyframes slideUp {
            from { 
                opacity: 0;
                transform: translateY(50px);
            }
            to { 
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .nav-links {
                display: none;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            header {
                min-height: 70vh;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
        }
        
        @media (max-width: 768px) {
            .section-title h2 {
                font-size: 1.8rem;
            }
            
            .service-card, .branch-card {
                margin-bottom: 1.5rem;
            }
            
            .form-col {
                flex: 100%;
                margin-bottom: 1rem;
            }
        }
        
        @media (max-width: 576px) {
            .btn {
                display: block;
                width: 100%;
                margin: 0.5rem 0;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="fade-in">
        <div class="header-content">
            <img src="https://via.placeholder.com/150x80.png?text=الرفاه+للحوالات" alt="شعار الرفاه للحوالات المالية" class="logo">
            <div class="hero">
                <h1 class="slide-up">حوالات مالية سريعة وآمنة بين تركيا وسوريا</h1>
                <p class="slide-up">نقدم حلول تحويل الأموال بسرعة فائقة وأعلى معايير الأمان وبأسعار تنافسية</p>
                <div class="slide-up">
                    <a href="#transfer" class="btn">إبدأ التحويل الآن</a>
                    <a href="#branches" class="btn btn-outline">فروعنا</a>
                </div>
            </div>
        </div>
    </header>
    
    <!-- Navigation -->
    <nav>
        <div class="container">
            <a href="#" class="nav-logo">الرفاه<span>للحوالات</span></a>
            <button class="mobile-menu-btn">
                <i class="fas fa-bars"></i>
            </button>
            <ul class="nav-links">
                <li><a href="#home"><i class="fas fa-home"></i> الرئيسية</a></li>
                <li><a href="#services"><i class="fas fa-hand-holding-usd"></i> خدماتنا</a></li>
                <li><a href="#exchange"><i class="fas fa-exchange-alt"></i> أسعار الصرف</a></li>
                <li><a href="#transfer"><i class="fas fa-money-bill-transfer"></i> تحويل أموال</a></li>
                <li><a href="#branches"><i class="fas fa-map-marker-alt"></i> فروعنا</a></li>
                <li><a href="#contact"><i class="fas fa-envelope"></i> اتصل بنا</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Main Content -->
    <div class="container">
        <!-- Services Section -->
        <section id="services" class="section">
            <div class="section-title">
                <h2>خدماتنا المميزة</h2>
            </div>
            <div class="services">
                <div class="service-card slide-up">
                    <img src="https://images.unsplash.com/photo-1579621970563-ebec7560ff3e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1471&q=80" alt="حوالات محلية" class="service-img">
                    <div class="service-content">
                        <h3>حوالات من تركيا إلى سوريا</h3>
                        <p>تحويل الأموال من تركيا إلى سوريا بسرعة وأمان مع أفضل الأسعار وأقل العمولات</p>
                        <a href="#transfer" class="btn">إبدأ التحويل</a>
                    </div>
                </div>
                <div class="service-card slide-up">
                    <img src="https://images.unsplash.com/photo-1553729459-efe14ef6055d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="حوالات دولية" class="service-img">
                    <div class="service-content">
                        <h3>حوالات من سوريا إلى تركيا</h3>
                        <p>إرسال الأموال من سوريا إلى تركيا بشبكة واسعة من الشركاء الموثوقين وأسعار تنافسية</p>
                        <a href="#transfer" class="btn">إبدأ التحويل</a>
                    </div>
                </div>
                <div class="service-card slide-up">
                    <img src="https://images.unsplash.com/photo-1604594849809-dfedbc827105?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="دفع الفواتير" class="service-img">
                    <div class="service-content">
                        <h3>دفع الفواتير والخدمات</h3>
                        <p>خدمة دفع الفواتير والخدمات في تركيا وسوريا بكل سهولة ويسر من خلال فروعنا</p>
                        <a href="#" class="btn">المزيد</a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Exchange Rates Section -->
        <section id="exchange" class="section">
            <div class="section-title">
                <h2>أسعار الصرف اليومية</h2>
            </div>
            <div class="exchange-rate slide-up">
                <p>تاريخ التحديث: <span class="rate-highlight" id="update-date">١ يونيو ٢٠٢٣</span></p>
                <table>
                    <thead>
                        <tr>
                            <th>العملة</th>
                            <th>شراء</th>
                            <th>بيع</th>
                            <th>التغيير</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><i class="fas fa-dollar-sign"></i> الدولار الأمريكي (USD)</td>
                            <td class="rate-highlight">9000</td>
                            <td class="rate-highlight">9100</td>
                            <td><span style="color: green;">+0.5% <i class="fas fa-arrow-up"></i></span></td>
                        </tr>
                        <tr>
                            <td><i class="fas fa-lira-sign"></i> الليرة التركية (TRY)</td>
                            <td class="rate-highlight">220</td>
                            <td class="rate-highlight">230</td>
                            <td><span style="color: red;">-0.3% <i class="fas fa-arrow-down"></i></span></td>
                        </tr>
                        <tr>
                            <td><i class="fas fa-coins"></i> القص (Gold)</td>
                            <td class="rate-highlight">39.7</td>
                            <td class="rate-highlight">39.1</td>
                            <td><span style="color: green;">+1.2% <i class="fas fa-arrow-up"></i></span></td>
                        </tr>
                    </tbody>
                </table>
                <p style="margin-top: 1rem; font-size: 0.9rem; color: #666;">* الأسعار قابلة للتغيير حسب السوق</p>
            </div>
        </section>
        
        <!-- Money Transfer Section -->
        <section id="transfer" class="section">
            <div class="section-title">
                <h2>نظام التحويل المالي</h2>
            </div>
            <div class="transfer-form slide-up">
                <h3>نموذج تحويل الأموال</h3>
                <form id="moneyTransferForm">
                    <div class="form-row">
                        <div class="form-col">
                            <div class="form-group">
                                <label for="sender-name">اسم المرسل</label>
                                <input type="text" id="sender-name" name="sender-name" required>
                            </div>
                            <div class="form-group">
                                <label for="sender-phone">هاتف المرسل</label>
                                <input type="tel" id="sender-phone" name="sender-phone" required>
                            </div>
                            <div class="form-group">
                                <label for="sender-currency">العملة المرسلة</label>
                                <select id="sender-currency" name="sender-currency" required>
                                    <option value="">اختر العملة</option>
                                    <option value="USD">دولار أمريكي (USD)</option>
                                    <option value="TRY">ليرة تركية (TRY)</option>
                                </select>
                            </div>
                        </div>
                        <div class="form-col">
                            <div class="form-group">
                                <label for="receiver-name">اسم المستلم</label>
                                <input type="text" id="receiver-name" name="receiver-name" required>
                            </div>
                            <div class="form-group">
                                <label for="receiver-phone">هاتف المستلم</label>
                                <input type="tel" id="receiver-phone" name="receiver-phone" required>
                            </div>
                            <div class="form-group">
                                <label for="receiver-currency">العملة المستلمة</label>
                                <select id="receiver-currency" name="receiver-currency" required>
                                    <option value="">اختر العملة</option>
                                    <option value="TRY">ليرة تركية (TRY)</option>
                                    <option value="SYP">ليرة سورية (SYP)</option>
                                    <option value="USD">دولار أمريكي (USD)</option>
                                </select>
                            </div>
                        </div>
                    </div>
                    <div class="form-group">
                        <label for="amount">المبلغ المراد تحويله</label>
                        <input type="number" id="amount" name="amount" min="1" required>
                    </div>
                    
                    <div class="transfer-summary">
                        <h4>ملخص التحويل</h4>
                        <div class="summary-item">
                            <span>المبلغ المرسل:</span>
                            <span id="sent-amount">0</span>
                        </div>
                        <div class="summary-item">
                            <span>العمولة:</span>
                            <span id="commission">0</span>
                        </div>
                        <div class="summary-item total">
                            <span>المبلغ الإجمالي:</span>
                            <span id="total-amount">0</span>
                        </div>
                        <div class="summary-item">
                            <span>المبلغ المستلم:</span>
                            <span id="received-amount">0</span>
                        </div>
                        <div class="summary-item">
                            <span>سعر الصرف:</span>
                            <span id="exchange-rate">1 USD = 9000 SYP</span>
                        </div>
                    </div>
                    
                    <button type="submit" class="form-btn">إرسال التحويل</button>
                </form>
            </div>
        </section>
        
        <!-- Branches Section -->
        <section id="branches" class="section">
            <div class="section-title">
                <h2>فروعنا</h2>
            </div>
            <div class="branches">
                <div class="branch-card slide-up">
                    <img src="https://images.unsplash.com/photo-1582268611958-ebfd161ef9cf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="الفرع الرئيسي - إسطنبول" class="branch-img">
                    <div class="branch-content">
                        <h3>الفرع الرئيسي - إسطنبول</h3>
                        <div class="branch-info">
                            <i class="fas fa-map-marker-alt"></i>
                            <p>حي الفاتح، شارع تقسيم</p>
                        </div>
                        <div class="branch-info">
                            <i class="fas fa-phone"></i>
                            <p>+905394600275</p>
                        </div>
                        <div class="branch-info">
                            <i class="fas fa-clock"></i>
                            <p>مواعيد العمل: 8 صباحاً - 10 مساءً</p>
                        </div>
                        <a href="#" class="btn btn-outline" style="display: inline-block; width: auto; margin-top: 1rem;">عرض الخريطة</a>
                    </div>
                </div>
                <div class="branch-card slide-up">
                    <img src="https://images.unsplash.com/photo-1516156008625-3a9d6067fab5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="فرع غازي عنتاب" class="branch-img">
                    <div class="branch-content">
                        <h3>فرع غازي عنتاب</h3>
                        <div class="branch-info">
                            <i class="fas fa-map-marker-alt"></i>
                            <p>حي شاهين بيه، شارع الجامعة</p>
                        </div>
                        <div class="branch-info">
                            <i class="fas fa-phone"></i>
                            <p>+905394600275</p>
                        </div>
                        <div class="branch-info">
                            <i class="fas fa-clock"></i>
                            <p>مواعيد العمل: 9 صباحاً - 11 مساءً</p>
                        </div>
                        <a href="#" class="btn btn-outline" style="display: inline-block; width: auto; margin-top: 1rem;">عرض الخريطة</a>
                    </div>
                </div>
                <div class="branch-card slide-up">
                    <img src="https://images.unsplash.com/photo-1566378246598-5b11a0ed4868?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="فرع حلب" class="branch-img">
                    <div class="branch-content">
                        <h3>فرع حلب</h3>
                        <div class="branch-info">
                            <i class="fas fa-map-marker-alt"></i>
                            <p>حي الصاخور، شارع الخندق</p>
                        </div>
                        <div class="branch-info">
                            <i class="fas fa-phone"></i>
                            <p>+963944567890</p>
                        </div>
                        <div class="branch-info">
                            <i class="fas fa-clock"></i>
                            <p>مواعيد العمل: 8 صباحاً - 10 مساءً</p>
                        </div>
                        <a href="#" class="btn btn-outline" style="display: inline-block; width: auto; margin-top: 1rem;">عرض الخريطة</a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Contact Section -->
        <section id="contact" class="section">
            <div class="section-title">
                <h2>تواصل معنا</h2>
            </div>
            <div class="contact">
                <div class="contact-info slide-up">
                    <h3>معلومات التواصل</h3>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h4>العنوان</h4>
                            <p>إسطنبول، تركيا</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div>
                            <h4>الهاتف</h4>
                            <p>+905394600275</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h4>البريد الإلكتروني</h4>
                            <p>info@alrafah.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-clock"></i>
                        <div>
                            <h4>ساعات العمل</h4>
                            <p>الأحد - الخميس: 8 ص - 10 م</p>
                            <p>الجمعة - السبت: 10 ص - 12 م</p>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="https://wa.me/905394600275"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                <div class="contact-form slide-up">
                    <h3>أرسل رسالتك</h3>
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="name">الاسم الكامل</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">البريد الإلكتروني</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">رقم الهاتف</label>
                            <input type="tel" id="phone" name="phone" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">الموضوع</label>
                            <select id="subject" name="subject" required>
                                <option value="">اختر الموضوع</option>
                                <option value="transfer">استفسار عن حوالة</option>
                                <option value="complaint">شكوى</option>
                                <option value="suggestion">مقترح</option>
                                <option value="other">أخرى</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="message">الرسالة</label>
                            <textarea id="message" name="message" required></textarea>
                        </div>
                        <button type="submit" class="form-btn">إرسال الرسالة</button>
                    </form>
                </div>
            </div>
        </section>
    </div>
    
    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-column">
                <h3>عن الشركة</h3>
                <p>شركة الرفاه للحوالات المالية تقدم خدمات تحويل الأموال بين تركيا وسوريا منذ عام 2010 بموثوقية وأمان عاليين.</p>
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
            <div class="footer-column">
                <h3>روابط سريعة</h3>
                <ul class="footer-links">
                    <li><a href="#home"><i class="fas fa-chevron-left"></i> الرئيسية</a></li>
                    <li><a href="#services"><i class="fas fa-chevron-left"></i> خدماتنا</a></li>
                    <li><a href="#exchange"><i class="fas fa-chevron-left"></i> أسعار الصرف</a></li>
                    <li><a href="#transfer"><i class="fas fa-chevron-left"></i> تحويل أموال</a></li>
                    <li><a href="#contact"><i class="fas fa-chevron-left"></i> اتصل بنا</a></li>
                </ul>
            </div>
            <div class="footer-column">
                <h3>خدماتنا</h3>
                <ul class="footer-links">
                    <li><a href="#"><i class="fas fa-chevron-left"></i> حوالات تركيا-سوريا</a></li>
                    <li><a href="#"><i class="fas fa-chevron-left"></i> حوالات سوريا-تركيا</a></li>
                    <li><a href="#"><i class="fas fa-chevron-left"></i> دفع الفواتير</a></li>
                    <li><a href="#"><i class="fas fa-chevron-left"></i> خدمات الشركات</a></li>
                </ul>
            </div>
            <div class="footer-column">
                <h3>التطبيقات</h3>
                <p>حمل تطبيقنا الآن لتحويل الأموال بسهولة وأمان</p>
                <div style="margin-top: 1rem;">
                    <a href="#" style="display: inline-block; margin-bottom: 0.5rem;">
                        <img src="https://via.placeholder.com/120x40.png?text=Google+Play" alt="جوجل بلاي" style="height: 40px;">
                    </a>
                    <a href="#" style="display: inline-block;">
                        <img src="https://via.placeholder.com/120x40.png?text=App+Store" alt="آب ستور" style="height: 40px;">
                    </a>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>&copy; 2023 شركة الرفاه للحوالات المالية. جميع الحقوق محفوظة.</p>
            <p>مرخصة من قبل البنك المركزي التركي</p>
        </div>
    </footer>
    
    <!-- JavaScript -->
    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
        const navLinks = document.querySelector('.nav-links');
        
        mobileMenuBtn.addEventListener('click', () => {
            navLinks.style.display = navLinks.style.display === 'flex' ? 'none' : 'flex';
        });
        
        // Smooth Scrolling for Anchor Links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (window.innerWidth <= 992) {
                        navLinks.style.display = 'none';
                    }
                }
            });
        });
        
        // Form Submission
        const contactForm = document.getElementById('contactForm');
        
        if (contactForm) {
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                
                // Here you would typically send the form data to a server
                // For demonstration, we'll just show an alert
                alert('تم إرسال رسالتك بنجاح! سنتواصل معك قريباً.');
                this.reset();
            });
        }
        
        // Animation on Scroll
        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.slide-up');
            
            elements.forEach(element => {
                const elementPosition = element.getBoundingClientRect().top;
                const screenPosition = window.innerHeight / 1.2;
                
                if (elementPosition < screenPosition) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        };
        
        // Set initial state for animated elements
        document.querySelectorAll('.slide-up').forEach(element => {
            element.style.opacity = '0';
            element.style.transform = 'translateY(50px)';
            element.style.transition = 'opacity 0.5s ease-out, transform 0.5s ease-out';
        });
        
        // Run animation check on load and scroll
        window.addEventListener('load', animateOnScroll);
        window.addEventListener('scroll', animateOnScroll);
        
        // Update current date
        function updateCurrentDate() {
            const now = new Date();
            const options = { day: 'numeric', month: 'long', year: 'numeric' };
            document.getElementById('update-date').textContent = now.toLocaleDateString('ar-SA', options);
        }
        
        // Money Transfer Calculation
        const moneyTransferForm = document.getElementById('moneyTransferForm');
        const sentAmountEl = document.getElementById('sent-amount');
        const commissionEl = document.getElementById('commission');
        const totalAmountEl = document.getElementById('total-amount');
        const receivedAmountEl = document.getElementById('received-amount');
        const exchangeRateEl = document.getElementById('exchange-rate');
        
        // Exchange rates
        const exchangeRates = {
            'USD-SYP': 9000,
            'USD-TRY': 1,
            'TRY-SYP': 220,
            'TRY-USD': 0.05,
            'SYP-TRY': 0.0045,
            'SYP-USD': 0.00011
        };
        
        // Commission calculation
        function calculateCommission(amount, currency) {
            if (currency === 'TRY') {
                // 25 ليرة لكل 1000 ليرة
                return Math.max(25, Math.floor(amount / 1000) * 25);
            } else if (currency === 'USD') {
                // 15 دولار لكل 1000 دولار
                return Math.max(15, Math.floor(amount / 1000) * 15);
            }
            return 0;
        }
        
        // Update transfer summary
        function updateTransferSummary() {
            const senderCurrency = document.getElementById('sender-currency').value;
            const receiverCurrency = document.getElementById('receiver-currency').value;
            const amount = parseFloat(document.getElementById('amount').value) || 0;
            
            if (!senderCurrency || !receiverCurrency) return;
            
            const commission = calculateCommission(amount, senderCurrency);
            const totalAmount = amount + commission;
            
            // Calculate received amount based on exchange rate
            const exchangeRateKey = `${senderCurrency}-${receiverCurrency}`;
            const exchangeRate = exchangeRates[exchangeRateKey] || 1;
            const receivedAmount = amount * exchangeRate;
            
            // Update UI
            sentAmountEl.textContent = `${amount.toFixed(2)} ${senderCurrency}`;
            commissionEl.textContent = `${commission.toFixed(2)} ${senderCurrency}`;
            totalAmountEl.textContent = `${totalAmount.toFixed(2)} ${senderCurrency}`;
            receivedAmountEl.textContent = `${receivedAmount.toFixed(2)} ${receiverCurrency}`;
            
            // Update exchange rate display
            if (senderCurrency === 'USD' && receiverCurrency === 'SYP') {
                exchangeRateEl.textContent = `1 USD = 9000 SYP`;
            } else if (senderCurrency === 'TRY' && receiverCurrency === 'SYP') {
                exchangeRateEl.textContent = `1 TRY = 220 SYP`;
            } else if (senderCurrency === 'USD' && receiverCurrency === 'TRY') {
                exchangeRateEl.textContent = `1 USD = 1 TRY`;
            } else if (senderCurrency === 'TRY' && receiverCurrency === 'USD') {
                exchangeRateEl.textContent = `1 TRY = 0.05 USD`;
            } else {
                exchangeRateEl.textContent = `1 ${senderCurrency} = ${exchangeRate} ${receiverCurrency}`;
            }
        }
        
        // Event listeners for transfer form
        document.getElementById('sender-currency').addEventListener('change', updateTransferSummary);
        document.getElementById('receiver-currency').addEventListener('change', updateTransferSummary);
        document.getElementById('amount').addEventListener('input', updateTransferSummary);
        
        // Submit transfer form
        moneyTransferForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            const senderName = document.getElementById('sender-name').value;
            const senderPhone = document.getElementById('sender-phone').value;
            const senderCurrency = document.getElementById('sender-currency').value;
            const receiverName = document.getElementById('receiver-name').value;
            const receiverPhone = document.getElementById('receiver-phone').value;
            const receiverCurrency = document.getElementById('receiver-currency').value;
            const amount = document.getElementById('amount').value;
            const receivedAmount = receivedAmountEl.textContent;
            
            // Prepare WhatsApp message
            const whatsappMessage = `طلب تحويل جديد:
            
المرسل: ${senderName}
هاتف المرسل: ${senderPhone}
العملة المرسلة: ${senderCurrency}
المبلغ: ${amount} ${senderCurrency}

المستلم: ${receiverName}
هاتف المستلم: ${receiverPhone}
العملة المستلمة: ${receiverCurrency}
المبلغ المستلم: ${receivedAmount}

شكراً لاستخدامكم خدمة الرفاه للحوالات المالية`;

            // Encode message for URL
            const encodedMessage = encodeURIComponent(whatsappMessage);
            
            // Open WhatsApp with the message
            window.open(`https://wa.me/905394600275?text=${encodedMessage}`, '_blank');
            
            // Reset form
            this.reset();
            updateTransferSummary();
            
            // Show success message
            alert('تم إعداد طلب التحويل بنجاح! سيتم التواصل معك عبر واتساب لتأكيد العملية.');
        });
        
        // Initialize
        updateCurrentDate();
        updateTransferSummary();
    </script>
</body>
</html>
