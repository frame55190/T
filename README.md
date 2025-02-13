<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To Bai'Toey 💕</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            font-family: 'Great Vibes', cursive;
            text-align: center;
            position: relative;
            color: white;
        }
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap');
        .hidden {
            display: none;
        }
        .message {
            font-size: 36px;
            color: white;
            margin-top: 20px;
            font-weight: bold;
            background: rgba(255, 255, 255, 0.2);
            padding: 25px;
            border-radius: 20px;
            backdrop-filter: blur(15px);
            box-shadow: 0 0 30px rgba(255, 255, 255, 0.4);
            animation: fadeIn 2s ease-in-out;
            width: 60%;
                }
        button {
            padding: 15px 40px;
            font-size: 24px;
            background: linear-gradient(90deg, #ff5f6d, #ffc371);
            color: white;
            border: none;
            border-radius: 15px;
            cursor: pointer;
            transition: 0.4s;
            box-shadow: 0 5px 20px rgba(255, 95, 109, 0.5);
            font-family: 'Great Vibes', cursive;
        }
        button:hover {
            background: linear-gradient(90deg, #ff416c, #ff4b2b);
            box-shadow: 0 5px 25px rgba(255, 65, 108, 0.6);
        }
        .heart {
            font-size: 80px;
            animation: heartbeat 1.5s infinite, fadeIn 2s ease-in-out;
            color: #ff3d67;
            margin-top: 15px;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.5); }
            100% { transform: scale(1); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <h1 style="text-shadow: 3px 3px 15px rgba(0, 0, 0, 0.4);">💖 สุขสันต์วันวาเลนไทน์! 💖</h1>
    <button onclick="showMessage()">💌 ส่งถึงคนพิเศษ 💌</button>
    <p id="valentineMessage" class="hidden message">✨ สุขสันต์วันวาเลนไทน์ ในวันวาเลนไทน์นี้ 
        ขอให้รอยยิ้มของพี่สดใสเหมือนดวงดาวบนฟ้านะแล้วก็ขอให้สอบผ่านในวันพรุ่งนี้ด้วยล่ะ ตั้งใจมากๆ อย่าดื้ออย่าซน อย่าขี้บ่นด้วย555 จุ๊บๆ 💕
    </p>
    <p class="heart hidden" id="heart">❤️</p>
    
    <script>
        function showMessage() {
            document.getElementById('valentineMessage').classList.remove('hidden');
            document.getElementById('heart').classList.remove('hidden');
        }
    </script>
</body>
</html>
