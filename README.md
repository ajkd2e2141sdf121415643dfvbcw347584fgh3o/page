<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ลิงก์ของฉัน</title>
  <link href="https://fonts.googleapis.com/css2?family=Prompt:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Prompt', sans-serif; background: linear-gradient(135deg, #141e30, #243b55); display: flex; justify-content: center; align-items: center; min-height: 100vh; padding: 20px; }
    .card { max-width: 500px; width: 100%; background: rgba(255,255,255,0.1); backdrop-filter: blur(10px); padding: 30px; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.5); color: white; text-align: center; border: 1px solid rgba(255,255,255,0.2); }
    .copy-text { background: rgba(255,255,255,0.15); padding: 20px; border-radius: 15px; margin-bottom: 25px; font-size: 16px; user-select: text; line-height: 1.7; }
    .btn { display: inline-block; padding: 14px 30px; margin: 10px; border-radius: 50px; text-decoration: none; font-weight: bold; font-size: 16px; transition: 0.3s; box-shadow: 0 5px 15px rgba(0,0,0,0.4); }
    .btn.yt { background: #ff0000; color: white; }
    .btn.dc { background: #5865F2; color: white; }
    .btn:hover { transform: translateY(-3px); box-shadow: 0 8px 20px rgba(0,0,0,0.5); }
    kbd { background: #333; color: #fff; padding: 3px 7px; border-radius: 4px; font-size: 13px; }
    footer { margin-top: 30px; font-size: 12px; opacity: 0.7; }
  </style>
</head>
<body>
  <div class="card">
    <div class="copy-text">
      <strong>ยินดีต้อนรับ!</strong><br>
      กดเลือกข้อความนี้แล้วกด <kbd>Ctrl+C</kbd> เพื่อก็อปได้เลย<br><br>
      ช่อง YouTube: <a href="https://youtube.com/@ชื่อช่องคุณ" style="color:#ff6b6b; text-decoration:underline;" target="_blank">@ชื่อช่องคุณ</a><br>
      Discord: <a href="https://discord.gg/XXXXXX" style="color:#7289da; text-decoration:underline;" target="_blank">discord.gg/XXXXXX</a>
    </div>
    <a href="https://youtube.com/@ชื่อช่องคุณ" target="_blank" class="btn yt">🎥 ไป YouTube</a>
    <a href="https://discord.gg/XXXXXX" target="_blank" class="btn dc">💬 เข้า Discord</a>
    <footer>สร้างด้วย ❤️ โดย [ชื่อคุณ]</footer>
  </div>
</body>
</html>
