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
      justify-content:center;
      background:#f4f4f9;
      font-family:"Segoe UI", sans-serif;
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
    }

    .container{
      padding:22px;
      display:flex;
      flex-direction:column;
      gap:14px;
      align-items:center;  /* ← وضع كل الخانات في المنتصف */
    }

    .box{
      width:65%;            /* ← تصغير العرض أكثر */
      background:var(--green);
      color:#fff;
      padding:15px 10px;
      border-radius:10px;
      text-align:center;
      font-size:1.05rem;
      cursor:pointer;
      box-shadow:0 6px 16px rgba(0,0,0,0.1);
      transition:.2s;
    }

    .box:hover{
      background:var(--green-hover);
      transform:translateY(-3px);
    }
  </style>
</head>

<body>

  <div class="card">
    <div class="title">WAY</div>

    <div class="container">

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
