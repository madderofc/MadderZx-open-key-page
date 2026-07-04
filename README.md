<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MadderZx — Get Key</title>
  <style>
    :root{
      --bg-url: url('REPLACE_WITH_ANIME_IMAGE_URL'); /* Replace with your anime girl image URL */
      --overlay: linear-gradient(rgba(0,0,0,0.46), rgba(0,0,0,0.46));
      --accent: #1e90ff;
      --text: #eaf4ff;
      --muted: #c8d8f0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{ height:100%; margin:0; }
    body{
      background: var(--overlay), var(--bg-url) center/cover fixed no-repeat;
      color:var(--text);
      display:flex;
      align-items:center;
      justify-content:center;
      padding:24px;
      box-sizing:border-box;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    .container{
      width:100%;
      max-width:820px;
      text-align:center;
      position:relative;
      padding:40px 20px;
    }

    .logo{
      position:absolute;
      left:18px;
      top:18px;
      width:56px;
      height:56px;
      border-radius:50%;
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:800;
      font-size:20px;
      color:var(--accent);
      background:rgba(255,255,255,0.03);
      border:1px solid rgba(255,255,255,0.06);
    }

    .creator{
      position:absolute;
      right:18px;
      top:18px;
      color:var(--muted);
      font-size:13px;
    }

    h1{
      margin:0 0 10px 0;
      font-size:44px;
      color:var(--accent);
      letter-spacing:0.6px;
    }
    p{ margin:0 0 26px 0; color:var(--muted); }

    .get-btn{
      background:linear-gradient(90deg,#00c3ff,#0072ff);
      color:white;
      border:none;
      padding:16px 28px;
      border-radius:14px;
      font-size:20px;
      font-weight:800;
      cursor:pointer;
      box-shadow:0 16px 40px rgba(0,110,255,0.22);
    }
    .get-btn:active{ transform:translateY(1px); }

    @media (max-width:520px){
      h1{ font-size:28px; }
      .logo{ left:12px; top:12px; width:48px; height:48px; font-size:18px; }
      .creator{ right:12px; top:12px; font-size:12px; }
    }
  </style>
</head>
<body>
  <div class="container" role="main" aria-labelledby="main-title">
    <div class="logo" aria-hidden="true">1</div>
    <div class="creator">creator by @OpMmadhav</div>

    <h1 id="main-title">MadderZx Key</h1>
    <p>Click "Get Key" — naya page khul jayega</p>
    <button id="getBtn" class="get-btn" aria-label="Get Key">Get Key</button>
  </div>

  <script>
    (function(){
      const TARGET = 'https://earnlinks.in/ys8Sk';
      const btn = document.getElementById('getBtn');
      btn.addEventListener('click', function(){
        try{
          window.open(TARGET, '_blank', 'noopener,noreferrer');
        }catch(e){
          location.href = TARGET;
        }
      });
    })();
  </script>
</body>
</html># MadderZx-open-key-page
