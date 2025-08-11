# Samurai.egyptlinks
Qrcode
<!doctype html>
<html lang="ar">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Samurai Egypt — روابط</title>
  <meta name="description" content="روابط Samurai Egypt" />
  <style>
    :root{
      --bg: #000000; /* خلفية سوداء بالكامل */
      --card: #0f0f0f;
      --text: #ffffff;
      --muted: #aaaaaa;
      --accent-1: #ff1a1a; /* أحمر من اللوجو */
      --btn-radius: 14px;
      --max-width: 520px;
      --gap: 14px;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing: border-box}
    html,body{height:100%}
    body{
      margin:0;min-height:100%;
      display:flex;align-items:center;justify-content:center;
      background: var(--bg);
      color:var(--text);
      padding:24px;
    }
    .card{
      width:100%;max-width:var(--max-width);
      background:rgba(255,255,255,0.02);
      border-radius:18px;padding:28px;text-align:center;
    }
    .avatar{
      width:140px;height:140px;margin:0 auto;border-radius:50%;
      overflow:hidden;border:4px solid var(--accent-1);
    }
    .avatar img{width:100%;height:100%;object-fit:contain;display:block;background:black}
    h1{margin:14px 0 6px;font-size:22px;color:var(--accent-1)}
    p.lead{margin:0 0 18px;color:var(--muted);font-size:13px}

    .links{display:flex;flex-direction:column;gap:var(--gap);margin-top:10px}
    .btn{
      display:flex;align-items:center;gap:12px;justify-content:center;
      padding:14px 16px;border-radius:var(--btn-radius);
      text-decoration:none;color:var(--text);font-weight:600;font-size:15px;
      background:rgba(255,0,0,0.1);
      border:1px solid var(--accent-1);
      transition:transform .12s ease, box-shadow .12s ease;
    }
    .btn:hover{transform:translateY(-4px);box-shadow:0 8px 24px rgba(255,0,0,0.4)}
    .btn .icon{width:20px;height:20px;display:inline-block;opacity:0.95}

    footer{margin-top:18px;color:var(--muted);font-size:12px}
    .modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;padding:20px}
    .modal .panel{background:var(--card);padding:18px;border-radius:12px;max-width:360px;width:100%;text-align:center}
    .modal.open{display:flex}
    .qr-img{width:230px;height:230px;margin:8px auto 12px;display:block}
  </style>
</head>
<body>
  <main class="card">
    <div class="avatar">
      <img src="لوجو ساموراي.png" alt="Samurai Egypt Logo">
    </div>
    <h1>Samurai Egypt</h1>
    <p class="lead">كل لينكاتي — تابع واتسوق وتابع المحتوى</p>
    <div class="links">
      <a class="btn" href="https://www.instagram.com/samurai.egypt/" target="_blank">إنستاجرام</a>
      <a class="btn" href="https://www.tiktok.com/@samurai.egypt" target="_blank">تيك توك</a>
      <a class="btn" href="https://sllr.co/samurai/shop" target="_blank">متجر Samurai</a>
    </div>
    <footer>© Samurai Egypt</footer>
  </main>
</body>
</html>
