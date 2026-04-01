<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة المنتج</title>
    <style>
        /* ===== CSS داخلي ===== */
        body {
            font-family: Arial, sans-serif;
            background: #f9f9f9;
            margin: 0;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
        }

        .header h1 {
            color: #e60023;
        }

        .products-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .product-card {
            width: 260px;
            background: #fff;
            padding: 15px;
            border-radius: 12px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            text-align: center;
            transition: 0.2s;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 3px 12px rgba(0,0,0,0.15);
        }

        .product-card img {
            width: 100%;
            border-radius: 8px;
            object-fit: cover;
        }

        .product-name {
            margin: 12px 0 6px;
            font-size: 18px;
            color: #333;
        }

        .product-price {
            color: #e60023;
            font-size: 20px;
            font-weight: bold;
        }

        .btn-add {
            background: #e60023;
            color: #fff;
            border: none;
            padding: 10px 0;
            width: 100%;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 10px;
            transition: 0.2s;
        }

        .btn-add:hover {
            background: #c3001f;
        }

        .contact {
            text-align: center;
            margin-top: 40px;
            font-size: 18px;
        }

        .contact a {
            color: #e60023;
            text-decoration: none;
            font-weight: bold;
        }

        .contact a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>

    <div class="header">
        <h1>منتجاتنا</h1>
        <p>أفضل جودة وأسعار ممتازة</p>
    </div>

    <div class="products-container">

        <div class="product-card">
            <img src="https://via.placeholder.com/300x300" alt="منتج 1">
            <h3 class="product-name">اسم المنتج 1</h3>
            <p class="product-price">299 د.م</p>
            <button class="btn-add">أضف إلى السلة</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/300x300" alt="منتج 2">
            <h3 class="product-name">اسم المنتج 2</h3>
            <p class="product-price">349 د.م</p>
            <button class="btn-add">أضف إلى السلة</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/300x300" alt="منتج 3">
            <h3 class="product-name">اسم المنتج 3</h3>
            <p class="product-price">399 د.م</p>
            <button class="btn-add">أضف إلى السلة</button>
        </div>

    </div>

    <div class="contact">
        تواصل معنا عبر الواتساب: <a href="tel:+212691444558">+212 691444558</a>
    </div>

</body>
</html>
