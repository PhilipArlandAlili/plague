<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Just Type | Home</title>
</head>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        height: 100%;
        width: 100%;
        background-color: #323437;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    header {
        height: 20%;
        width: 80%;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .logo img {
        height: 100px;
    }

    a {
        color: #ededed;
        font-size: 20px;
        margin: 40px 20px;
        text-decoration: none;
    }

    .container {
        height: 500px;
        width: 90%;
        display: flex;
        justify-content: center;
    }

    .game-container,
    .form-container {
        height: 80%;
        width: 40%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        color: #ededed;
    }

    .form-container {
        display: flex;
        font-size: 20px;
    }

    .form-container input,
    .form-container textarea {
        border-radius: 10px;
        padding-left: 10px;
        height: 60px;
        width: 300px;
        margin: 8px;
    }

    .form-container button {
        height: 40%;
        width: 40%;
        margin-top: 8px;
    }

    .game-container {
        display: none;
    }

    .form {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin-bottom: 20px;
    }

    .game-container textarea {
        height: 22%;
        width: 60%;
        text-align: center;
        margin: 10px 10px;
        border-radius: 10px;
        resize: none;
        font-size: 18px;
    }

    button {
        margin-top: 20px;
        height: 10%;
        border-radius: 10px;
        width: 20%;
        background-color: #E2B714;
        border: none;
        cursor: pointer;
    }

    button:hover {
        background-color: gold;
    }

    button:disabled {
        background-color: #666;
        cursor: not-allowed;
    }

    p {
        font-size: 18px;
    }
</style>

<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="">
        </div>
        <nav>
            <a href="index.php">Home</a>
        </nav>
    </header>

    <div class="container">
        <div class="form-container" id="form-container">
            <form id="name-form" class="form">
                <label for="player-name">Enter Name to Play the Game!</label>
                <input type="text" id="player-name" placeholder="Enter Name" required>
                <button type="button" onclick="submitName()">Submit</button>
            </form>
        </div>

        <div class="game-container" id="game-container">
            <h1 id="word-display"></h1>
            <p id="welcome"></p>
            <textarea id="user-input" placeholder="Start typing..." rows="4"></textarea>
            <p id="feedback"></p>
            <p id="timer">Time: 0 seconds</p>
            <button onclick="startGame()" id="btn-start">Start Game</button>
        </div>
    </div>

    <script>
        const words = [
            "An apple a day keeps the doctor away.",
            "Bananas in the morning provide a good source of potassium.",
            "Elderberry syrup, known for its benefits to the immune system.",
            "Mango trees in the backyard bear sweet and juicy fruits."
        ];

        let currentWordIndex;
        let currentWord;
        let startTime;
        let timerInterval;
        let isGameActive = false;

        function submitName() {
            const userName = document.getElementById('player-name').value.trim();

            if (userName !== '') {
                document.getElementById('welcome').textContent = `Welcome ${userName}! Click Start Game to Start`;
                document.getElementById('form-container').style.display = 'none';
                document.getElementById('game-container').style.display = 'flex';
            } else {
                alert('Please enter a name.');
            }
        }

        function startGame() {
            if (isGameActive) return;

            isGameActive = true;
            currentWordIndex = Math.floor(Math.random() * words.length);
            currentWord = words[currentWordIndex];

            document.getElementById('word-display').textContent = currentWord;
            document.getElementById('user-input').value = '';
            document.getElementById('welcome').textContent = '';
            document.getElementById('feedback').textContent = '';
            document.getElementById('timer').textContent = 'Time: 0 seconds';
            document.querySelector('button[onclick="startGame()"]').disabled = true;

            document.getElementById('user-input').focus();
            startTime = new Date().getTime();
            timerInterval = setInterval(updateTimer, 100);

            document.getElementById('user-input').addEventListener('input', checkInput);
        }

        function updateTimer() {
            const currentTime = new Date().getTime();
            const elapsedTime = (currentTime - startTime) / 1000;
            document.getElementById('timer').textContent = `Time: ${elapsedTime.toFixed(1)} seconds`;
        }

        function checkInput() {
            const userInput = document.getElementById('user-input').value.trim();
            const userName = document.getElementById('player-name').value.trim();

            if (userInput === currentWord) {
                isGameActive = false;
                const endTime = new Date().getTime();
                const elapsedTime = (endTime - startTime) / 1000;
                clearInterval(timerInterval);

                const feedback = `Congratulations ${userName}!`;
                document.getElementById('feedback').textContent = feedback;
                document.getElementById('user-input').removeEventListener('input', checkInput);
                document.querySelector('button[onclick="startGame()"]').disabled = false;
            }
        }

        // Cleanup function to prevent memory leaks
        window.addEventListener('beforeunload', function () {
            if (timerInterval) {
                clearInterval(timerInterval);
            }
        });
    </script>
</body>

</html>