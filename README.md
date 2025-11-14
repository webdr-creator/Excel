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
      --card-width:700px;
    }
    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:flex-start;
      justify-content:center;
      background:#f4f4f9;
      font-family: "Segoe UI", Tahoma, sans-serif;
      padding:40px 16px;
      color:#222;
    }

    /* البطاقة التي تجمع العنوان والمحتوى — بحيث يكونان ملتصقين */
    .card{
      width:90%;
      max-width:var(--card-width);
      border-radius:12px;
      overflow:hidden; /* هذا يلتصق العنوان مع الصندوق لأن الحواف مقطوعة على البطاقة */
      box-shadow:0 8px 24px rgba(0,0,0,0.12);
      background:#fff;
    }

    /* العنوان — ممتلئ باللون */
    .card .title{
      background:var(--green);
      color:#fff;
      text-align:center;
      padding:24px 18px;
      font-size:1.9rem;
      font-weight:700;
      letter-spacing:2px;
    }

    /* الصندوق الذي يحتوي الخانات — ملتصق مباشرة بالعنوان لأنهما داخل البطاقة نفسها */
    .card .container{
      padding:22px;
      background:#ffffff;
      display:grid;
      grid-template-columns: repeat(2, minmax(0, 1fr)); /* اثنتان في كل صف */
      gap:18px;
      align-items:stretch;
    }

    /* كل خانة */
    .box{
      background:var(--green);
      color:#fff;
      padding:18px 14px;
      border-radius:10px;
      text-align:center;
      font-size:1.05rem;
      cursor:pointer;
      box-shadow:0 6px 16px rgba(0,0,0,0.08);
      transition: transform .18s ease, background .18s ease;
      display:flex;
      align-items:center;
      justify-content:center;
      line-height:1.3;
      white-space:normal;
    }
    .box:hover{ background:var(--green-hover); transform:translateY(-4px); }

    /* لضمان أن نصوص العربية الطويلة تظهر في صفين داخل الخانة بشكل جميل */
    .box br{ display:none; }

    /* -- ملاحظة responsiveness --
       على شاشات ضيقة جداً قد تتكدس الخانات رأسياً لأن المساحة لا تكفي؛
       إن أردت إجبارها لتبقى ثنائيات حتى على الموبايل يمكن تقليل حجم النص أو السماح للتمرير، أخبرني. */
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
