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

    /* حاوية تشمل العنوان والمحتوى ليصبح العرض موحد */
    .container {
        width: 90%;
        max-width: 900px;
        margin: 20px auto;
        border-radius: 20px;
        overflow: hidden; /* يجعل الزوايا منحنية ومتصلة */
        box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    /* العنوان الأخضر */
    .header {
        background: #4CAF50;
        padding: 35px;
        text-align: center;
        font-size: 2.3rem;
        font-weight: bold;
        color: white;
    }

    /* المربع الأبيض */
    .content-box {
        background: #fff;
        padding: 35px 10px;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }

    /* الخانات */
    .box {
        display: inline-block;
        background: #4CAF50;
        color: #fff;
        padding: 12px 28px;
        border-radius: 10px;
        font-size: 1.2rem;
        white-space: nowrap;
        box-shadow: 0 6px 14px rgba(0,0,0,0.1);
        transition: .2s;
        cursor: pointer;
    }

    .box:hover {
        background: #45a049;
        transform: translateY(-3px);
    }
</style>
</head>

<body>

    <div class="container">

        <div class="header">WAY</div>

        <div class="content-box">

            <div class="box">السنة الثانية – الفصل الأول</div>
            <div class="box">السنة الثانية – الفصل الثاني</div>

            <div class="box">السنة الثالثة – الفصل الأول</div>
            <div class="box">السنة الثالثة – الفصل الثاني</div>

            <div class="box">السنة الرابعة – الفصل الأول</div>
            <div class="box">السنة الرابعة – الفصل الثاني</div>

            <div class="box">السنة الخامسة – الفصل الأول</div>
            <div class="box">السنة الخامسة – الفصل الثاني</div>

        </div>

    </div>

</body>
</html>
