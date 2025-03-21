<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Día de las Flores Amarillas</title>
    <style>
        body {
            background-color: black;
            margin: 0;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            position: relative;
        }
        
        h1 {
            color: yellow;
            font-size: 3rem;
            font-family: 'Arial', sans-serif;
            text-shadow: 0 0 10px rgba(255, 255, 0, 0.8);
            animation: glow 2s infinite alternate;
            z-index: 10;
            position: relative;
        }

        @keyframes glow {
            from { text-shadow: 0 0 10px rgba(255, 255, 0, 0.8); }
            to { text-shadow: 0 0 20px rgba(255, 255, 0, 1), 0 0 30px rgba(255, 255, 0, 0.8); }
        }

        .flower {
            position: absolute;
            width: 100px;
            height: 100px;
            display: flex;
            justify-content: center;
            align-items: center;
            opacity: 0;
            animation: fadeInOut 5s infinite;
        }

        .petal {
            position: absolute;
            width: 40px;
            height: 80px;
            background-color: yellow;
            border-radius: 50%;
        }

        .petal:nth-child(1) { transform: rotate(0deg) translateY(-20px); }
        .petal:nth-child(2) { transform: rotate(45deg) translateY(-20px); }
        .petal:nth-child(3) { transform: rotate(90deg) translateY(-20px); }
        .petal:nth-child(4) { transform: rotate(135deg) translateY(-20px); }
        .petal:nth-child(5) { transform: rotate(180deg) translateY(-20px); }
        .petal:nth-child(6) { transform: rotate(225deg) translateY(-20px); }
        .petal:nth-child(7) { transform: rotate(270deg) translateY(-20px); }
        .petal:nth-child(8) { transform: rotate(315deg) translateY(-20px); }

        .center {
            position: absolute;
            width: 30px;
            height: 30px;
            background-color: orange;
            border-radius: 50%;
        }

        @keyframes fadeInOut {
            0%, 100% { opacity: 0; }
            50% { opacity: 1; }
        }

        #play-audio {
            background-color: yellow;
            border: none;
            padding: 10px 20px;
            font-size: 1rem;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Para mi princesita Sahad</h1>
    <button id="play-audio">Reproducir Música</button>
    <audio id="background-audio" autoplay loop>
        <source src="audio/Tsss.mp3" type="audio/mp3">
        Tu navegador no soporta el audio.
    </audio>
    <script>
        function createFlower(x, y, delay) {
            const flower = document.createElement('div');
            flower.classList.add('flower');
            document.body.appendChild(flower);
            
            for (let i = 0; i < 8; i++) {
                const petal = document.createElement('div');
                petal.classList.add('petal');
                flower.appendChild(petal);
            }

            const center = document.createElement('div');
            center.classList.add('center');
            flower.appendChild(center);

            flower.style.left = `${x}px`;
            flower.style.top = `${y}px`;
            flower.style.animationDelay = `${delay}s`;
        }

        const positions = [];
        const rows = 6, cols = 10;
        const spacingX = window.innerWidth / cols;
        const spacingY = window.innerHeight / rows;
        
        for (let i = 0; i < rows; i++) {
            for (let j = 0; j < cols; j++) {
                let offsetX = j * spacingX;
                let offsetY = i * spacingY;
                if (Math.abs(offsetX - window.innerWidth / 2) > 150 || Math.abs(offsetY - window.innerHeight / 2) > 100) {
                    positions.push([offsetX, offsetY]);
                }
            }
        }
        
        positions.forEach((pos, index) => {
            createFlower(pos[0], pos[1], index * 0.2);
        });

        document.getElementById("play-audio").addEventListener("click", function() {
            const audio = document.getElementById("background-audio");
            audio.play();
        });
    </script>
</body>
</html>
