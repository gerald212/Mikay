<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Special Puzzle for Mikaella ✨</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Press+Start+2P&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 50%, #fbc2eb 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            padding: 15px;
        }

        /* Floating sparkles background */
        .sparkle {
            position: absolute;
            color: rgba(255, 255, 255, 0.6);
            font-size: 18px;
            animation: floatSparkle 5s infinite ease-in-out;
            user-select: none;
        }

        @keyframes floatSparkle {
            0% { transform: translateY(100vh) scale(0.8); opacity: 1; }
            100% { transform: translateY(-10vh) scale(1.2); opacity: 0; }
        }

        .game-card {
            background: rgba(255, 255, 255, 0.82);
            backdrop-filter: blur(16px);
            border: 2px solid rgba(255, 255, 255, 0.9);
            border-radius: 28px;
            padding: 25px 20px;
            max-width: 380px;
            width: 100%;
            text-align: center;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.12);
            position: relative;
            z-index: 10;
        }

        .badge {
            display: inline-block;
            background: linear-gradient(45deg, #ff758c, #ff7eb3);
            color: white;
            font-family: 'Press Start 2P', cursive;
            font-size: 9px;
            padding: 6px 14px;
            border-radius: 20px;
            margin-bottom: 12px;
            letter-spacing: 1px;
            box-shadow: 0 4px 12px rgba(255, 117, 140, 0.3);
        }

        h1 {
            color: #333;
            font-size: 1.3rem;
            margin-bottom: 6px;
            font-weight: 700;
        }

        p.subtitle {
            color: #666;
            font-size: 0.85rem;
            margin-bottom: 18px;
        }

        /* Grid Puzzle Box */
        .puzzle-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin: 15px auto;
            max-width: 270px;
        }

        .tile {
            aspect-ratio: 1;
            background: linear-gradient(135deg, #ffffff, #ffe3ec);
            border: 2px solid #ffb6c1;
            border-radius: 16px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 28px;
            cursor: pointer;
            transition: all 0.25s ease;
            box-shadow: 0 5px 12px rgba(255, 182, 193, 0.4);
            user-select: none;
        }

        .tile:hover {
            transform: scale(1.06);
            background: #fff;
        }

        .tile.unlocked {
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            border-color: #ff4757;
            color: white;
            animation: pop 0.3s ease;
        }

        @keyframes pop {
            0% { transform: scale(0.8); }
            50% { transform: scale(1.15); }
            100% { transform: scale(1); }
        }

        /* Message Box */
        .result-box {
            display: none;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
            margin-top: 10px;
        }

        .result-box h2 {
            color: #ff4757;
            font-size: 1.25rem;
            margin-bottom: 10px;
        }

        .result-box p {
            color: #4a4a4a;
            font-size: 0.95rem;
            line-height: 1.6;
            margin-bottom: 12px;
        }

        .btn {
            background: linear-gradient(45deg, #a1c4fd, #c2e9fb);
            color: #2c3e50;
            border: none;
            padding: 12px 24px;
            font-size: 14px;
            font-weight: 600;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 6px 18px rgba(161, 196, 253, 0.5);
            transition: all 0.3s ease;
            width: 100%;
            margin-top: 10px;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 22px rgba(161, 196, 253, 0.7);
        }

        .note-tag {
            background: rgba(255, 230, 238, 0.8);
            border-left: 4px solid #ff758c;
            padding: 10px 12px;
            border-radius: 8px;
            text-align: left;
            font-size: 0.88rem;
            color: #444;
            margin: 12px 0;
        }
    </style>
</head>
<body>

    <!-- Floating Background Elements -->
    <div class="sparkle" style="left: 12%; animation-duration: 6s;">✨</div>
    <div class="sparkle" style="left: 30%; animation-duration: 4.5s;">💖</div>
    <div class="sparkle" style="left: 70%; animation-duration: 7s;">🌷</div>
    <div class="sparkle" style="left: 85%; animation-duration: 5.5s;">⭐</div>

    <div class="game-card">
        <!-- Puzzle Phase -->
        <div id="puzzleScreen">
            <div class="badge">PUZZLE QUEST 🧩</div>
            <h1>Solve for a Secret 💌</h1>
            <p class="subtitle">Tap all the heart pieces to complete the puzzle!</p>

            <div class="puzzle-grid" id="grid">
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
                <div class="tile" onclick="clickTile(this)">❓</div>
            </div>

            <p style="font-size: 0.8rem; color: #888; margin-top: 10px;">Progress: <span id="count">0</span>/9 pieces</p>
        </div>

        <!-- Unlocked Message Phase -->
        <div id="resultScreen" class="result-box">
            <div class="badge" style="background: linear-gradient(45deg, #2ed573, #7bed9f);">PUZZLE SOLVED! 🏆</div>
            <h2>For Mikaella Jane ✨</h2>
            
            <div class="note-tag">
                <strong>Hey Mikaella,</strong><br>
                Just wanted to remind you to take care of yourself today!
            </div>

            <p>
                Be careful always, okay? Don't skip meals and take little breaks when you're busy. Wishing you a super bright and happy day ahead! 💖
            </p>

            <button class="btn" onclick="extraHearts()">Send Love Back 💕</button>
        </div>
    </div>

    <script>
        let unlockedCount = 0;
        const heartIcons = ['💖', '🌸', '✨', '💕', '🌷', '🎀', '💌', '☀️', '💖'];

        function clickTile(tile) {
            if (!tile.classList.contains('unlocked')) {
                tile.classList.add('unlocked');
                tile.innerText = heartIcons[unlockedCount];
                unlockedCount++;
                document.getElementById('count').innerText = unlockedCount;

                // Subtle mini pop effect
                confetti({
                    particleCount: 15,
                    spread: 40,
                    origin: { y: 0.7 }
                });

                if (unlockedCount === 9) {
                    setTimeout(completePuzzle, 500);
                }
            }
        }

        function completePuzzle() {
            // Big victory confetti!
            confetti({
                particleCount: 120,
                spread: 80,
                origin: { y: 0.6 },
                colors: ['#ff758c', '#a1c4fd', '#ffffff', '#ffd1dc']
            });

            document.getElementById('puzzleScreen').style.display = 'none';
            const res = document.getElementById('resultScreen');
            res.style.display = 'block';
            setTimeout(() => {
                res.style.opacity = '1';
            }, 50);
        }

        function extraHearts() {
            confetti({
                particleCount: 100,
                spread: 100,
                origin: { y: 0.6 },
                colors: ['#ff4757', '#ff758c', '#ffffff']
            });
        }
    </script>
</body>
</html>
