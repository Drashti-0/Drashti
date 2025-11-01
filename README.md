 <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Drashti Bhanderi — README Preview</title>
  <style>
    body{
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: #0f172a;
      color: #e6eef8;
      display:flex;
      align-items:center;
      justify-content:center;
      min-height:100vh;
      margin:0;
      padding:20px;
    }
    .card{
      max-width:760px;
      width:100%;
      background: linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.01));
      border-radius:16px;
      padding:28px;
      box-shadow: 0 8px 30px rgba(2,6,23,0.6);
      text-align:center;
    }

    h1{ margin:0 0 6px 0; font-size:28px; letter-spacing:0.2px; }
    p.lead{ margin:4px 0 18px 0; color:#9fb0d6; }

    /* Animated line container */
    .animated-line{
      display:inline-block;
      font-weight:700;
      font-size:20px;
      padding:8px 14px;
      border-radius:999px;
      position:relative;
      overflow:hidden;
      --glow: 0 0 30px rgba(99,102,241,0.25);
    }

    /* moving gradient text */
    .animated-line .text{
      background: linear-gradient(90deg, #60a5fa, #7c3aed, #06b6d4, #60a5fa);
      background-size: 300% 100%;
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      animation: slideGradient 3s linear infinite;
      display:inline-block;
    }

    /* subtle pop animation on the CSE word */
    .animated-line .cse{
      display:inline-block;
      margin-left:8px;
      padding:4px 10px;
      border-radius:999px;
      background:rgba(255,255,255,0.04);
      box-shadow: var(--glow);
      transform-origin:center;
      animation: pop 1.8s ease-in-out infinite;
    }

    @keyframes slideGradient{
      0%{ background-position: 0% 50%; }
      50%{ background-position: 100% 50%; }
      100%{ background-position: 0% 50%; }
    }

    @keyframes pop{
      0%   { transform: scale(1); filter: drop-shadow(0 0 0 rgba(0,0,0,0)); }
      30%  { transform: scale(1.06); }
      60%  { transform: scale(0.98); }
      100% { transform: scale(1); }
    }

    /* small responsive tweaks */
    @media (max-width:520px){
      .card{ padding:18px; }
      h1{ font-size:22px; }
      .animated-line{ font-size:16px; }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Hi 👋, I'm Drashti Bhanderi</h1>
    <p class="lead">🎓 First-Year Computer Science & Engineering student</p>

    <div style="margin-top:14px;">
      <span class="animated-line" aria-hidden="true">
        <span class="text">Learning</span>
        <span class="cse">CSE</span>
      </span>
    </div>

    <p style="margin-top:18px; color:#a9c0e8;">
      👩‍💻 Passionate about coding • 📚 Curious to learn • 🌱 Growing every day
    </p>
  </div>
</body>
</html>
