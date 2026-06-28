<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>راهنمای مسیرهای استقرار</title>

  <style>
    body {
      font-family: sans-serif;
      background: #f5f7f6;
      margin: 0;
      padding: 20px;
      direction: rtl;
    }

    .container {
      max-width: 500px;
      margin: auto;
      background: white;
      border-radius: 20px;
      padding: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    }

    h1 {
      font-size: 20px;
      color: #0a6b3d;
      text-align: center;
      margin-bottom: 10px;
    }

    p.subtitle {
      text-align: center;
      font-size: 13px;
      color: #555;
      margin-bottom: 20px;
    }

    .item {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #f7f7f7;
      padding: 12px;
      border-radius: 12px;
      margin-bottom: 10px;
      cursor: pointer;
      transition: 0.2s;
    }

    .item:hover {
      background: #e9f5ee;
    }

    .item span {
      font-size: 15px;
    }

    .arrow {
      width: 30px;
      height: 30px;
      background: #0a6b3d;
      color: white;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
    }

    .footer {
      margin-top: 20px;
      font-size: 12px;
      text-align: center;
      color: #666;
    }
  </style>
</head>

<body>

<div class="container">

  <h1>راهنمای مسیرهای استقرار</h1>
  <p class="subtitle">
    استقبال و خدمت‌رسانی به زائران و شرکت‌کنندگان در مراسم تشییع
  </p>

  <div class="item" onclick="go('nikkala')">
    <span>مجموعه نیک کالا</span>
    <div class="arrow">›</div>
  </div>

  <div class="item" onclick="go('emamzade')">
    <span>امامزاده طاهر</span>
    <div class="arrow">›</div>
  </div>

  <div class="item" onclick="go('mohammadshahr')">
    <span>متروی محمدشهر</span>
    <div class="arrow">›</div>
  </div>

  <div class="item" onclick="go('fardis')">
    <span>متروی فردیس</span>
    <div class="arrow">›</div>
  </div>

  <div class="item" onclick="go('eyvan')">
    <span>مجموعه ایوان</span>
    <div class="arrow">›</div>
  </div>

  <div class="item" onclick="go('modares')">
    <span>پادگان شهید مدرس</span>
    <div class="arrow">›</div>
  </div>

  <div class="footer">
    با انتخاب هر گزینه، می‌توانید مسیر را در اپلیکیشن نشان باز کنید
  </div>

</div>

<script>
  function go(place) {
    alert("انتخاب شد: " + place + "\nاینجا می‌تونی لینک نشان یا نقشه رو وصل کنی");
  }
</script>

</body>
</html>
