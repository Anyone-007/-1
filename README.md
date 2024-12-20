<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجري الإلكتروني</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f9f9f9;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem;
        }
        nav a:hover {
            background-color: #4CAF50;
        }
        .container {
            padding: 2rem;
            text-align: center;
        }
        .product {
            display: inline-block;
            margin: 1rem;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: white;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            margin-bottom: 1rem;
        }
        .product h3 {
            margin: 0.5rem 0;
        }
        .product p {
            color: #666;
        }
        .product button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 3px;
        }
        .product button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبًا بكم في متجري الإلكتروني</h1>
    </header>
    <nav>
        <a href="#">الرئيسية</a>
        <a href="#">المنتجات</a>
        <a href="#">عن المتجر</a>
        <a href="#">تواصل معنا</a>
    </nav>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="صورة المنتج">
            <h3>اسم المنتج 1</h3>
            <p>وصف مختصر للمنتج.</p>
            <p>السعر: $100</p>
            <button>إضافة إلى السلة</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="صورة المنتج">
            <h3>اسم المنتج 2</h3>
            <p>وصف مختصر للمنتج.</p>
            <p>السعر: $150</p>
            <button>إضافة إلى السلة</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="صورة المنتج">
            <h3>اسم المنتج 3</h3>
            <p>وصف مختصر للمنتج.</p>
            <p>السعر: $200</p>
            <button>إضافة إلى السلة</button>
        </div>
    </div>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2024</p>
    </footer>
</body>
</html>
