<!doctype html>
<html lang="sk">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Czechoslovakia Roleplay — Coming Soon</title>
  <style>
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}

    body{
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      display:grid;
      place-items:center;
      min-height:100vh;
      color:#fff;
      overflow:hidden;
      --bg1:#0b1220;
      --bg2:#1b2a4a;
      --accent:#ffdd57;
      background: linear-gradient(270deg,var(--bg1), var(--bg2), #6a1b9a);
      background-size: 600% 600%;
      animation: backgroundShift 12s ease infinite;
    }

    @keyframes backgroundShift{
      0%{background-position:0% 50%}
      50%{background-position:100% 50%}
      100%{background-position:0% 50%}
    }

    .card{
      text-align:center;
      padding:3.2rem 2.4rem;
      border-radius:18px;
      backdrop-filter: blur(6px) saturate(120%);
      background: linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.03));
      box-shadow: 0 10px 30px rgba(2,6,23,0.6), inset 0 1px 0 rgba(255,255,255,0.05);
      max-width:960px;
      width:92%;
      animation: floatCard 4s ease-in-out infinite;
    }

    @keyframes floatCard{
      0%,100%{transform:translateY(0)}
      50%{transform:translateY(-15px)}
    }

    h1{
      font-size:clamp(28px,6vw,56px);
      margin-bottom:0.6rem;
      text-transform:uppercase;
      color: #fff;
      text-shadow: 0 6px 30px rgba(11,12,20,0.7);
      animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow{
      from{text-shadow:0 0 10px #fff,0 0 20px #ffdd57,0 0 30px #ffdd57;}
      to{text-shadow:0 0 20px #fff,0 0 40px #ffdd57,0 0 60px #ffdd57;}
    }

    .coming-soon{
      margin-top:20px;
      display:inline-block;
      font-weight:700;
      padding:0.65rem 1.1rem;
      border-radius:999px;
      background:linear-gradient(90deg, rgba(255,255,255,0.1), rgba(255,255,255,0.05));
      box-shadow: 0 6px 24px rgba(11,12,20,0.45);
      color:var(--accent);
      border:1px solid rgba(255,255,255,0.06);
      font-size:1rem;
      letter-spacing:0.12em;
      text-transform:uppercase;
      animation: pulse 1.5s ease-in-out infinite;
    }

    @keyframes pulse{
      0%{transform:scale(1)}
      50%{transform:scale(1.15)}
      100%{transform:scale(1)}
    }

    .stars{
      pointer-events:none;
      position:fixed;inset:0;z-index:0;mix-blend-mode:screen;opacity:.35;
      background-image:
        radial-gradient(circle, rgba(255,255,255,0.8) 0 1px, transparent 1px),
        radial-gradient(circle, rgba(255,255,255,0.6) 0 1px, transparent 1px),
        radial-gradient(circle, rgba(255,255,255,0.4) 0 1px, transparent 1px);
      background-size: 200px 200px, 350px 350px, 500px 500px;
      animation: twinkle 8s linear infinite;
    }

    @keyframes twinkle{
      0%,100%{opacity:.3}
      50%{opacity:.6}
    }

  </style>
</head>
<body>
  <div class="stars" aria-hidden="true"></div>

  <main class="card" role="main">
    <h1>Czechoslovakia Roleplay</h1>
    <div class="coming-soon">Coming Soon</div>
  </main>

</body>
</html>
