<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <title>Kedvenc Játékaim</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #f0f0f0;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        h1 {
            color: #00ffcc;
        }
        .game {
            background-color: #2b2b2b;
            border-radius: 10px;
            padding: 20px;
            margin: 20px auto;
            max-width: 600px;
            box-shadow: 0 0 10px rgba(0,0,0,0.6);
        }
        img {
            max-width: 100%;
            border-radius: 10px;
        }
        .rating {
            font-size: 24px;
            color: gold;
        }
        button {
            margin-top: 15px;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            background-color: #00ffcc;
            color: #000;
            cursor: pointer;
        }
        button:hover {
            background-color: #00ccaa;
        }
    </style>
</head>
<body>

    <h1>🎮 A Kedvenc Játékaim 🎮</h1>

    <div class="game">
        <h2>GTA 5</h2>
        <img src="https://upload.wikimedia.org/wikipedia/en/a/a5/Grand_Theft_Auto_V.png" alt="GTA 5 borító">
        <p>A GTA 5 egy nyílt világú akciójáték, ahol bármit megtehetsz: autóverseny, küldetések, bankrablások vagy csak szórakozás Los Santosban!</p>
        <div class="rating">⭐⭐⭐⭐⭐</div>
    </div>

    <div class="game">
        <h2>CS:GO</h2>
        <img src="https://upload.wikimedia.org/wikipedia/en/6/6f/CSGOcoverMarch2020.jpg" alt="CS:GO borító">
        <p>A Counter-Strike: Global Offensive egy pörgős lövöldözős játék, ahol a csapatmunka és a reflexek számítanak. Klasszikus!</p>
        <div class="rating">⭐⭐⭐⭐☆</div>
    </div>

    <button onclick="alert('Köszi, hogy megnézted a kedvenc játékaimat!')">Tetszett az oldalam</button>

</body>
</html>
