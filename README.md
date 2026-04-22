<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LuckyBot - Discord Giveaway Bot</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: linear-gradient(135deg, #0a0e27 0%, #1a0a3d 100%);
            color: #e0e0e0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            min-height: 100vh;
            overflow-x: hidden;
        }
        
        header {
            background: rgba(0, 0, 0, 0.8);
            padding: 30px 20px;
            text-align: center;
            border-bottom: 3px solid #7c3aed;
        }
        
        h1 {
            color: #a855f7;
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: 0 0 20px rgba(168, 85, 247, 0.5);
        }
        
        .subtitle {
            color: #60a5fa;
            font-size: 1.2em;
        }
        
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
        }
        
        .commands-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }
        
        .command-card {
            background: rgba(20, 20, 40, 0.9);
            border: 2px solid #3b82f6;
            border-radius: 10px;
            padding: 25px;
            transition: all 0.3s ease;
            cursor: pointer;
        }
        
        .command-card:hover {
            background: rgba(30, 30, 60, 0.9);
            border-color: #a855f7;
            box-shadow: 0 0 20px rgba(168, 85, 247, 0.4);
            transform: translateY(-5px);
        }
        
        .command-name {
            color: #a855f7;
            font-size: 1.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .command-desc {
            color: #60a5fa;
            font-size: 1.1em;
        }
        
        .button-group {
            text-align: center;
            margin: 40px 0;
        }
        
        .invite-btn {
            background: linear-gradient(135deg, #7c3aed 0%, #3b82f6 100%);
            color: white;
            padding: 15px 40px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
            margin: 10px;
        }
        
        .invite-btn:hover {
            box-shadow: 0 0 30px rgba(168, 85, 247, 0.6);
            transform: scale(1.05);
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #60a5fa;
            border-top: 2px solid #7c3aed;
            margin-top: 40px;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .commands-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🎉 LuckyBot</h1>
        <p class="subtitle">Der beste Discord Giveaway Bot</p>
    </header>
    
    <div class="container">
        <h2 style="text-align: center; color: #a855f7; margin-bottom: 30px;">Commands</h2>
        
        <div class="commands-grid">
            <div class="command-card">
                <div class="command-name">/giveaway</div>
                <div class="command-desc">Giveaway starten</div>
            </div>
            
            <div class="command-card">
                <div class="command-name">/help</div>
                <div class="command-desc">Hilfe</div>
            </div>
            
            <div class="command-card">
                <div class="command-name">/history</div>
                <div class="command-desc">Giveaway historie</div>
            </div>
            
            <div class="command-card">
                <div class="command-name">/quickgiveaway</div>
                <div class="command-desc">Schnelles giveaway</div>
            </div>
            
            <div class="command-card">
                <div class="command-name">/reroll</div>
                <div class="command-desc">Giveaway wiederholen</div>
            </div>
            
            <div class="command-card">
                <div class="command-name">/stats</div>
                <div class="command-desc">Alle gewinner</div>
            </div>
        </div>
        
        <div class="button-group">
            <a href="https://discord.com/api/oauth2/authorize?client_id=YOUR_BOT_ID&permissions=8&scope=bot%20applications.commands" class="invite-btn">🤖 Bot einladen</a>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2026 LuckyBot - Made with 💜</p>
    </footer>
</body>
</html>
