<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VORTEX ARENA</title>
    <style>
        /* TÜM TASARIM BURADA - DIŞ BAĞLANTI YOK */
        * { box-sizing: border-box; }
        body { background-color: #080808 !important; color: white !important; font-family: sans-serif; margin: 0; padding: 20px; display: flex; justify-content: center; }
        .wrapper { width: 100%; max-width: 400px; text-align: center; }
        
        .logo { font-size: 32px; font-weight: 900; font-style: italic; text-transform: uppercase; margin-bottom: 5px; letter-spacing: -1px; }
        .neon { color: #39FF14; text-shadow: 0 0 10px #39FF14; }
        .sub { font-size: 10px; color: #555; letter-spacing: 4px; margin-bottom: 40px; }

        .card { background: #111; border: 1px solid #222; border-radius: 15px; padding: 20px; margin-bottom: 20px; text-align: left; }
        .label { color: #39FF14; font-size: 9px; font-weight: bold; text-transform: uppercase; margin-bottom: 10px; display: block; }
        
        .match { display: flex; justify-content: space-between; align-items: center; padding: 10px 0; }
        .vs { font-weight: 900; color: #333; font-style: italic; }

        .player { background: #181818; padding: 12px; border-radius: 10px; margin-bottom: 10px; border-left: 4px solid #39FF14; display: flex; align-items: center; }
        .p-name { font-weight: bold; font-size: 14px; margin-left: 10px; }

        .btn { background: #39FF14; color: black; border: none; width: 100%; padding: 15px; border-radius: 10px; font-weight: bold; font-size: 14px; margin-top: 20px; text-transform: uppercase; }
    </style>
</head>
<body>

    <div class="wrapper">
        <div class="logo">VORTEX <span class="neon">ARENA</span></div>
        <div class="sub">AGRESİF • FÜTÜRİSTİK • ELİT</div>

        <div class="card">
            <span class="label">Sıradaki Maç</span>
            <div class="match">
                <span>🐺 VORTEX</span>
                <span class="vs">VS</span>
                <span style="color:#444">TBD ?</span>
            </div>
            <div style="text-align: center; font-size: 11px; color: #444; margin-top: 15px;">15 MART | 21:00</div>
        </div>

        <div style="text-align: left; margin-bottom: 10px;">
            <span class="label" style="color:white">Kadro</span>
        </div>

        <div class="player">
            <span>🥷</span>
            <span class="p-name">GHOST_WALKER</span>
        </div>

        <div class="player" style="border-left-color: #333;">
            <span>🎯</span>
            <span class="p-name">REAPER_AWP</span>
        </div>

        <button class="btn">KADROYA BAŞVUR</button>
    </div>

</body>
</html>
