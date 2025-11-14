<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WAY</title>

<style>
    body {
        margin: 0;
        font-family: "Cairo", sans-serif;
        background: #e8e8e8;
    }

    /* العنوان الأخضر */
    .header {
        background: #4CAF50;
        padding: 35px;
        text-align: center;
        font-size: 2.3rem;
        font-weight: bold;
        color: white;
        border-radius: 0 0 20px 20px;
    }

    /* المربع الأبيض */
    .content-box {
        background: #fff;
        width: 90%;
        max-width: 900px;
        margin: 20px auto;
        padding: 35px 10px;
        border-radius: 15px;
        box-shadow: 0 0 15px rgba(0,0,0,0.1);
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }

    /* الخانات */
    .box {
        display: inline-block;     /* مهم: يحول الخانات لحجم النص */
        background: #4CAF50;
        color: #fff;
        padding: 10px 25px;
        border-radius: 10px;
        font-size: 1.2rem;
        text-align: center;
        white-space: nowrap;       /* يمنع انقسام النص */
        cursor: pointer;
        box-shadow: 0 6px 14px rgba(0,0,0,0.1);
        transition: .2s;
    }

    .box:hover {
        background: #45a049;
        transform: translateY(-3px);
    }

</style>
</head>

<body>

    <div class="header">WAY</div>

    <div class="content-box">

        <div class="box">السنة الثانية – الفصل الأول</div>
        <div class="box">السنة الثانية – الفصل الثاني</div>
        <div class="box">السنة الثالثة – الفصل الأول</div>
        <div class="box">السنة الثالثة – الفصل الثاني</div>
        <div class="box">السنة الرابعة – الفصل الأول</div>
        <div class="box">السنة الرابعة – الفصل الثاني</div>

    </div>

</body>
</html>
