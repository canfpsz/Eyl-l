<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>♥ EYLÜL ♥</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: radial-gradient(ellipse at center, #1b1b1b 0%, #000000 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
            font-family: 'Courier New', Courier, monospace;
        }
        .heart {
            position: relative;
            width: 200px;
            height: 180px;
            background: #ff4d6d;
            transform: rotate(-45deg);
            animation: pulse 1.5s infinite;
            box-shadow: 0 0 40px rgba(255, 105, 135, 0.8);
        }
        .heart:before,
        .heart:after {
            content: "";
            position: absolute;
            width: 200px;
            height: 180px;
            background: #ff4d6d;
            border-radius: 50%;
        }
        .heart:before {
            top: -100px;
            left: 0;
        }
        .heart:after {
            left: 100px;
            top: 0;
        }
        @keyframes pulse {
            0% { transform: rotate(-45deg) scale(1); }
            50% { transform: rotate(-45deg) scale(1.1); }
            100% { transform: rotate(-45deg) scale(1); }
        }
        .text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotate(45deg);
            color: white;
            font-size: 24px;
            text-shadow: 0 0 10px #fff, 0 0 20px #ff69b4;
        }
    </style>
</head>
<body>
    <div class="heart">
        <div class="text">EYLÜL</div>
    </div>
</body>
</html>
