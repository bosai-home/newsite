---
title: 联系我们
permalink: /contact.html
layout: none   <!-- 关键：不使用任何布局，直接输出以下 HTML -->
---

<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }} - TechShop</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { 
            font-family: 'Segoe UI', system-ui, sans-serif; 
            background-color: #f8f9fa; 
            padding-bottom: 50px;
        }
        .container { max-width: 1200px; }
        .rounded.shadow-lg:hover { 
            transform: scale(1.03); 
            transition: transform 0.3s ease; 
        }
        .d-flex h5 { margin-bottom: 0.5rem; }

        /* 导航栏（与产品页保持一致） */
        .navbar {
            padding: 0.8rem 1rem;
        }
        .navbar-brand {
            font-size: 1.4rem !important;
        }
    </style>
</head>
<body>

    <!-- 导航栏（复制你产品页的导航，保持一致性） -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm">
        <div class="container">
            <a class="navbar-brand logo" href="/index.html">🔥 TechShop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="/index.html">首页</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">所有产品</a></li>
                    <li class="nav-item"><a class="nav-link" href="/about.html">关于我们</a></li>
                    <li class="nav-item"><a class="nav-link" href="/contact.html">联系</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container my-5 py-5">
        <h1 class="display-4 text-center fw-bold text-primary mb-5">联系我们</h1>

        <div class="row align-items-center g-5">
            <!-- 左侧图片 -->
            <div class="col-lg-6 text-center">
                <img src="https://jaidigitalmarketing.com/wp-content/uploads/2025/02/DALL%C2%B7E-2025-02-18-00.32.20-A-modern-and-professional-contact-us-webpage-banner.-The-image-features-a-sleek-office-environment-with-a-friendly-customer-support-team-assisting-cli.webp" 
                     alt="我们的客户支持团队" 
                     class="img-fluid rounded shadow-lg" 
                     style="max-height: 500px; object-fit: cover;">
            </div>

            <!-- 右侧联系信息 -->
            <div class="col-lg-6">
                <p class="lead fs-5 text-muted mb-5">
                    我们随时为您提供支持！无论您有产品咨询、定制需求还是合作意向，都欢迎随时联系我们。
                </p>

                <div class="row g-4">
                    <div class="col-12 d-flex align-items-center">
                        <div class="me-4">
                            <img src="https://thumbs.dreamstime.com/b/pin-map-location-icons-location-map-icon-illustration-map-pin-flat-icon-vector-design-map-pin-place-marker-d-map-pins-map-location-358949321.jpg" 
                                 alt="地址图标" width="50" class="img-fluid">
                        </div>
                        <div>
                            <h5 class="fw-bold">公司地址</h5>
                            <p class="mb-0">中国广东省广州市天河区某某工业园88号</p>
                        </div>
                    </div>

                    <div class="col-12 d-flex align-items-center">
                        <div class="me-4">
                            <img src="https://static.vecteezy.com/system/resources/previews/018/865/447/non_2x/email-simple-flat-icon-illustration-vector.jpg" 
                                 alt="邮箱图标" width="50" class="img-fluid">
                        </div>
                        <div>
                            <h5 class="fw-bold">电子邮箱</h5>
                            <p class="mb-0"><a href="mailto:info@yourcompany.com">info@yourcompany.com</a></p>
                        </div>
                    </div>

                    <div class="col-12 d-flex align-items-center">
                        <div class="me-4">
                            <img src="https://www.shutterstock.com/image-vector/simple-phone-call-icon-vector-260nw-2629030447.jpg" 
                                 alt="电话图标" width="50" class="img-fluid">
                        </div>
                        <div>
                            <h5 class="fw-bold">联系电话</h5>
                            <p class="mb-0">+86 123-4567-8899（工作日 9:00-18:00）</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- 询盘表单 -->
        <div class="mt-5">
            <h3 class="text-center mb-4 text-primary">💬 直接留言给我们</h3>
            <p class="text-center lead mb-5">填写以下表单，我们将在 24 小时内回复您！</p>

            <div class="ratio ratio-16x9 border rounded shadow-sm" style="max-height: 900px;">
                <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf5DJMqO3bixxs3I-sL9ef5MOGNNif35vbmxYc7ZmSb4XfGzg/viewform?embedded=true" 
                        style="border: none; width: 100%; height: 100%;"
                        frameborder="0" 
                        marginheight="0" 
                        marginwidth="0">
                    正在加载…
                </iframe>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
