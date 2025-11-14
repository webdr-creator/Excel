<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>WAY</title>
  <style>
    :root{
      --green:#4CAF50;
      --green-hover:#45a049;
    }

    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:flex-start;
      justify-content:center;
      background:#f4f4f9;
      font-family: "Segoe UI", Tahoma, sans-serif;
      padding-top:30px;
    }

    .card{
      width:95%;
      max-width:700px;
      border-radius:14px;
      overflow:hidden;
      background:#fff;
      box-shadow:0 8px 24px rgba(0,0,0,0.12);
    }

    .title{
      background:var(--green);
      color:#fff;
      text-align:center;
      padding:25px 18px;
      font-size:2.3rem;
      font-weight:bold;
      letter-spacing:2px;
    }

    /* هنا نجبر الخانات أن تبقى خانتين مهما كان حجم الشاشة */
    .container{
      padding:22px;
      display:grid;
      grid-template-columns: 1fr 1fr; /* ثنائيات دائمًا */
      gap:18px;
      overflow-x: auto; /* في حال ضاقت الشاشة نسمح بالتمرير */
      scrollbar-width: thin;
    }

    .box{
      background:var(--green);
      color:#fff;
      padding:18px 12px;
      border-radius:10px;
      text-align:center;
      font-size:1.0rem;
      cursor:pointer;
      box-shadow:0 6px 16px rgba(0,0,0,0.1);
      transition:.2s;
      white-space:normal;
      line-height:1.4;
    }

    .box:hover{
      background:var(--green-hover);
      transform:translateY(-4px);
    }
  </style>
</head>

<body>

  <div class="card">
    <div class="title">WAY</div>

    <div class="container">

      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثانية<br>الفصل الأول</div>
      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثانية<br>الفصل الثاني</div>

      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثالثة<br>الفصل الأول</div>
      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الثالثة<br>الفصل الثاني</div>

      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الرابعة<br>الفصل الأول</div>
      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الرابعة<br>الفصل الثاني</div>

      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الخامسة<br>الفصل الأول</div>
      <div class="box" onclick="location.href='https://webdr-creator.github.io/Excel/tst1.html'">السنة الخامسة<br>الفصل الثاني</div>

    </div>
  </div>

</body>
</html>
