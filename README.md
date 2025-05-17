[Uploading RD_chu<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>RD_chuki Gang</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial Black', Arial, sans-serif;
            background-color: #121212;
            color: white;
        }
        #welcome-screen {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: linear-gradient(135deg, #009966, #004d40);
        }
        #welcome-screen h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px black;
        }
        #enter-btn {
            font-size: 24px;
            padding: 12px 30px;
            background-color: #45a049;
            border: none;
            border-radius: 10px;
            color: white;
            cursor: pointer;
            box-shadow: 0 0 8px #45a049;
            transition: background-color 0.3s ease;
        }
        #enter-btn:hover {
            background-color: rgba(69, 160, 73, 0.9);
        }
        #main-content {
            display: none;
            padding: 20px;
            background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1470&q=80') no-repeat center center fixed;
            background-size: cover;
            min-height: 100vh;
        }
        header {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-bottom: 20px;
            background-color: rgba(0,0,0,0.7);
            padding: 10px 20px;
            border-radius: 12px;
            box-shadow: 0 0 10px #00b0ff;
        }
        header img {
            height: 80px;
            border-radius: 10px;
            box-shadow: 0 0 10px #00b0ff;
        }
        header h1 {
            font-size: 36px;
            color: #00b0ff;
            text-shadow: 2px 2px 4px black;
            margin: 0;
        }
        header p {
            color: #a0d8ff;
            font-size: 18px;
            margin: 0;
        }
        main a {
            display: inline-block;
            margin: 20px 0;
            font-size: 22px;
            color: #00b0ff;
            text-decoration: none;
            background-color: rgba(0, 176, 255, 0.15);
            padding: 10px 20px;
            border-radius: 12px;
            box-shadow: 0 0 8px #00b0ff;
            transition: background-color 0.3s ease;
        }
        main a:hover {
            background-color: rgba(0, 176, 255, 0.4);
        }
        .frases {
            font-size: 20px;
            font-style: italic;
            margin: 40px 20px 20px;
            color: #00b0ff; /* azul brillante */
            text-shadow: 1px 1px 3px black;
            text-transform: uppercase;
            line-height: 1.5em;
            background-color: rgba(0,0,0,0.6);
            padding: 20px;
            border-radius: 15px;
        }
        .suscribete {
            margin-top: 40px;
            font-size: 28px;
            font-weight: bold;
            color: #007acc;
            text-shadow: 2px 2px 4px black;
            text-transform: uppercase;
            text-align: center;
        }
        .social {
            margin: 40px 0;
            display: flex;
            gap: 30px;
            justify-content: center;
        }
        .social a svg {
            width: 40px;
            height: 40px;
            filter: drop-shadow(0 0 3px black);
            transition: transform 0.3s ease;
        }
        .social a:hover svg {
            transform: scale(1.2);
        }
        .game {
            margin-top: 40px;
            background-color: rgba(0,0,0,0.7);
            padding: 20px;
            border-radius: 15px;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
            box-shadow: 0 0 15px #ff4500;
            text-align: center;
        }
        .game h2 {
            margin-bottom: 15px;
            color: #ff4500;
            text-shadow: 2px 2px 5px black;
        }
        .game input[type=number] {
            font-size: 18px;
            padding: 8px;
            width: 150px;
            border-radius: 8px;
            border: none;
            margin-right: 10px;
            text-align: center;
        }
        .game button {
            font-size: 18px;
            padding: 8px 15px;
            background-color: #ff4500;
            border: none;
            border-radius: 8px;
            color: white;
            cursor: pointer;
            box-shadow: 0 0 8px #ff4500;
            transition: background-color 0.3s ease;
        }
        .game button:hover {
            background-color: #e03e00;
        }
        #result {
            margin-top: 20px;
            font-size: 20px;
            min-height: 28px;
            text-shadow: 1px 1px 3px #004d40;
        }
    </style>
</head>
<body>

    <div id="welcome-screen">
        <h1>¡Bienvenido a RD_chuki Gang!</h1>
        <button id="enter-btn">Entrar</button>
    </div>

    <div id="main-content">
        <header>
            <img src="ChatGPT Image 4 may 2025, 18_32_35.png" alt="Logo RD_chuki Gang" />
            <div>
                <h1>RD_chuki Gang</h1>
                <p>¡Bienvenidos al canal de RD_chuki Gang! Aquí encontrarás contenido sobre MTA RP y más.</p>
            </div>
        </header>
        <main>
            <a href="https://youtube.com/@rd_chuki01?si=oQ6HCEYI1UtNMCIS" target="_blank" rel="noopener noreferrer">Visita mi canal de YouTube</a>

            <div class="frases">
                <p>“El flow dominicano no se compra, se nace con él. Aquí jugamos con estilo, talento y pura vibra positiva.”</p>
                <p>“Si no te caes, no aprendes. Si no aprendes, no creces. ¡Aquí se crece siempre!”</p>
                <p>“Gaming no es solo un hobby, es nuestra pasión. ¡Con RD_chuki Gang, siempre pa’lante!”</p>
                <p>“La comunidad es clave. Aquí, tú eres parte de la familia. ¡Únete y seamos invencibles juntos!”</p>
            </div>

            <div class="suscribete">¡SUSCRÍBETE Y MÁNTENLO REAL CON RD_CHUKI!</div>

            <div class="social" aria-label="Redes sociales">
                <a href="https://youtube.com/@rd_chuki01" target="_blank" rel="noopener noreferrer" aria-label="YouTube">
                    <svg role="img" viewBox="0 0 24 24" fill="#FF0000" xmlns="http://www.w3.org/2000/svg">
                        <title>YouTube</title>
                        <path d="M23.498 6.186c-.276-1.04-1.09-1.855-2.13-2.13C19.846 3.5 12 3.5 12 3.5s-7.846 0-9.367.556c-1.04.276-1.854 1.09-2.13 2.13C.5 7.707.5 12 .5 12s0 4.293.003 5.814c.276 1.04 1.09 1.854 2.13 2.13 1.52.556 9.367.556 9.367.556s7.846 0 9.367-.556c1.04-.276 1.854-1.09 2.13-2.13C23.5 16.293 23.5 12 23.5 12s0-4.293-.002-5.814zM9.75 15.02V8.98L15.5 12l-5.75 3.02z"/>
                    </svg>
                </a>
                <a href="https://www.twitch.tv/rd_chuki" target="_blank" rel="noopener noreferrer" aria-label="Twitch">
                    <svg role="img" viewBox="0 0 24 24" fill="#9146FF" xmlns="http://www.w3.org/2000/svg">
                        <title>Twitch</title>
                        <path d="M2 2v20l4-4h6l6-6V2H2zm16 12-4 4h-5l-2 2V4h11v10z"/>
                        <path d="M15 7h1v5h-1zm-4 0h1v5H11z"/>
                    </svg>
                </a>
                <a href="https://kick.com/rd_chuki" target="_blank" rel="noopener noreferrer" aria-label="Kick">
                    <svg role="img" viewBox="0 0 24 24" fill="#7C4DFF" xmlns="http://www.w3.org/2000/svg">
                        <title>Kick</title>
                        <path d="M12 2L3 7v10l9 5 9-5V7l-9-5zM10 17h-2v-6h2v6zm6-6h-2v6h2v-6z"/>
                    </svg>
                </a>
            </div>

            <div class="game">
                <h2>Juego: Adivina el Número</h2>
                <p>Adivina un número del 1 al 100. ¡Solo tienes 7 intentos!</p>
                <input type="number" id="guessInput" min="1" max="100" placeholder="Tu número" />
                <button onclick="guessNumber()">Adivinar</button>
                <div id="result"></div>
                <button onclick="resetGame()" style="margin-top: 15px; background-color:#ff4500; color:#fff;">Reiniciar Juego</button>
            </div>
        </main>
    </div>

<script>
    const enterBtn = document.getElementById('enter-btn');
    const welcomeScreen = document.getElementById('welcome-screen');
    const mainContent = document.getElementById('main-content');

    enterBtn.addEventListener('click', () => {
        welcomeScreen.style.display = 'none';
        mainContent.style.display = 'block';
    });

    let secretNumber = Math.floor(Math.random() * 100) + 1;
    let attemptsLeft = 7;

    function guessNumber() {
        const input = document.getElementById('guessInput');
        const result = document.getElementById('result');
        const guess = Number(input.value);
        if (!guess || guess < 1 || guess > 100) {
            result.textContent = 'Por favor, ingresa un número válido entre 1 y 100.';
            return;
        }

        if (attemptsLeft <= 0) {
            result.textContent = 'Se acabaron tus intentos! El número era ' + secretNumber + '.';
            return;
        }

        attemptsLeft--;

        if (guess === secretNumber) {
            result.textContent = `¡Felicidades! Adivinaste el número ${secretNumber} con ${7 - attemptsLeft} intentos. 🎉`;
            attemptsLeft = 0; // para bloquear más intentos
        } else if (guess > secretNumber) {
            result.textContent = `Muy alto! Te quedan ${attemptsLeft} intentos.`;
        } else {
            result.textContent = `Muy bajo! Te quedan ${attemptsLeft} intentos.`;
        }

        if (attemptsLeft === 0 && guess !== secretNumber) {
            result.textContent += ` Juego terminado. El número correcto era ${secretNumber}.`;
        }

        input.value = '';
        input.focus();
    }

    function resetGame() {
        secretNumber = Math.floor(Math.random() * 100) + 1;
        attemptsLeft = 7;
        document.getElementById('result').textContent = '';
        document.getElementById('guessInput').value = '';
    }
</script>

</body>
</html>
ki Gang.html…]()
