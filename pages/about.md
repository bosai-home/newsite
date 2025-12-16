---
layout: default  # 如果你有默认布局；如果没有，可以改成 layout: none 并用完整 HTML
title: 关于我们
permalink: /about.html
---

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
            </p>
            <p class="fs-5 lh-lg">
                公司成立于2015年，拥有一支经验丰富的研发团队和现代化的生产基地。我们坚持“品质至上、客户第一”的理念，从选材到工艺，每一个环节都严格把控，确保产品经久耐用、美观大方。<br><br>
                
                我们的产品远销欧美、东南亚等多个国家和地区，深受客户信赖。未来，我们将继续创新，推出更多符合现代家居审美与功能需求的产品，与您共同打造高品质的生活空间。
            </p>
            <p class="fs-5 text-primary fw-bold">
                选择我们，选择品质与信任。
            </p>
        </div>
    </div>
</div>

<style>
    /* 美观自定义样式（可选，增强视觉效果） */
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
</style>
