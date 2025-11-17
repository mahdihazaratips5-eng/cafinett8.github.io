<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحه قرمز - بیمه خودرو</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: #ff0000 !important;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Tahoma, Arial, sans-serif;
        }
        
        .red-page {
            text-align: center;
            color: white;
            padding: 50px;
        }
        
        .red-page h1 {
            font-size: 4em;
            margin-bottom: 30px;
            text-shadow: 3px 3px 0px rgba(0,0,0,0.3);
        }
        
        .red-page p {
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        
        .btn {
            background: white;
            color: #ff0000;
            padding: 15px 40px;
            border: none;
            border-radius: 25px;
            font-size: 1.2em;
            font-weight: bold;
            cursor: pointer;
            margin: 10px;
            text-decoration: none;
            display: inline-block;
        }
        
        .btn:hover {
            background: #ffcccc;
        }
    </style>
</head>
<body>
    <div class="red-page">
        <h1>🚨 صفحه قرمز 🚨</h1>
        <p>این صفحه کاملاً قرمز طراحی شده است</p>
        <p>برای بازگشت به صفحه اصلی کلیک کنید</p>
        <a href="index.html" class="btn">بازگشت به صفحه اصلی</a>
        <br>
        <a href="#" class="btn" onclick="changeColor()">تغییر رنگ زمینه</a>
    </div>

    <script>
        function changeColor() {
            const colors = ['#ff0000', '#ff4444', '#cc0000', '#ff6666'];
            const randomColor = colors[Math.floor(Math.random() * colors.length)];
            document.body.style.background = randomColor;
        }
    </script>
</body>
</html>
