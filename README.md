<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WAY</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            padding-top: 40px;
        }

        /* مربع العنوان */
        .app-title-wrapper {
            width: 80%;
            max-width: 700px;
            background-color: #4CAF50;
            padding: 25px;
            border-radius: 12px;
            text-align: center;
            margin-bottom: 25px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }

        .app-title {
            font-size: 2.5em;
            color: white;
            font-weight: bold;
            letter-spacing: 3px;
        }

        /* صندوق الخانات */
        .container {
            width: 80%;
            max-width: 700px;
            background-color: #fff;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);

            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px; /* المسافة بين الخانات */
        }

        /* تصميم الخانات */
        .box {
            padding: 20px;
            background-color: #4CAF50;
            color: white;
            border-radius: 10px;
            text-align: center;
            font-size: 1.2em;
            cursor: pointer;
            transition: 0.3s;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .box:hover {
            background-color: #45a049;
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

    <!-- العنوان -->
    <div class="app-title-wrapper">
        <div class="app-title">WAY</div>
    </div>

    <!-- الخانات الثنائية -->
    <div class="container">

        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثانية الفصل الأول</div>
        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثانية الفصل الثاني</div>

        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثالثة الفصل الأول</div>
        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثالثة الفصل الثاني</div>

        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الرابعة الفصل الأول</div>
        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الرابعة الفصل الثاني</div>

        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الخامسة الفصل الأول</div>
        <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الخامسة الفصل الثاني</div>

    </div>

</body>
</html>
