<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WAY</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            color: #333;
        }
        .app-title {
            font-size: 3em;
            margin-bottom: 40px;
            color: #4CAF50;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            letter-spacing: 3px;
            text-align: center;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 30px;
            width: 90%;
            max-width: 1200px;
            padding: 20px;
        }
        .box {
            padding: 25px;
            text-align: center;
            background-color: #4CAF50;
            color: white;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            font-size: 1.2em;
            transition: transform 0.3s ease, background-color 0.3s ease;
            cursor: pointer;
        }
        .box:hover {
            background-color: #45a049;
            transform: translateY(-5px);
        }
        .row {
            display: flex;
            justify-content: space-between;
            gap: 20px;
        }
    </style>
</head>
<body>
    <div class="app-title">WAY</div>
    <div class="container">
        <div class="row">
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثانية الفصل الأول</div>
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثانية الفصل الثاني</div>
        </div>
        <div class="row">
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثالثة الفصل الأول</div>
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثالثة الفصل الثاني</div>
        </div>
        <div class="row">
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الرابعة الفصل الأول</div>
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الرابعة الفصل الثاني</div>
        </div>
        <div class="row">
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الخامسة الفصل الأول</div>
            <div class="box" onclick="window.location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الخامسة الفصل الثاني</div>
        </div>
    </div>
</body>
</html>
