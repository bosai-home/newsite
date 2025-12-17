---
title: 关于我们
permalink: /about.html
layout: none   <!-- 关键：不使用默认布局，避免出现主题页脚 -->
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
        .container {
            max-width: 1200px;
        }
        .rounded.shadow-lg {
            transition: transform 0.3s ease;
        }
        .rounded.shadow-lg:hover {
            transform: scale(1.03);
        }
        .text-primary {
            color: #0d6efd !important;
        }

        /* 导航栏手机端优化（与产品页一致） */
        .navbar {
            padding: 0.8rem 1rem;
        }
        .navbar-brand {
            font-size: 1.4rem !important;
        }
    </style>
</head>
<body>

    <!-- 导航栏（与产品详情页完全一致） -->
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
        <div class="row align-items-center">
            <!-- 图片部分（左侧或上方，根据屏幕自适应） -->
            <div class="col-lg-6 text-center mb-4 mb-lg-0">
                <img src="https://img.freepik.com/free-photo/group-businesspeople-with-thumbs-up-gesture-modern-office-multi-ethnic-people-working-together-teamwork-concept_1139-964.jpg?w=740" 
                     alt="我们的团队" 
                     class="img-fluid rounded shadow-lg" 
                     style="max-height: 500px; object-fit: cover;">
            </div>

            <!-- 文字内容部分 -->
            <div class="col-lg-6">
                <h1 class="display-5 fw-bold text-primary mb-4">关于我们</h1>
                <p class="lead fs-5 text-muted mb-4">
                    我们是一家专注于高端家居五金配件的设计与制造企业，致力于为全球客户提供优质、创新且可靠的产品解决方案。
                </
