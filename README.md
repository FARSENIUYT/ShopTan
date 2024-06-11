<style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            font-weight: 200;
            color: brown;
        }

        #main {
            width: 100%;
            padding: 20px;
            text-align: center;
        }

        h1 {
            margin-top: 100px;
            margin-bottom: 30px;
        }

        img {
            width: 250px;
            margin: 100px auto;
        }

        p {
            width: 350px;
            margin: 0 auto;
            color: chocolate;
            background-color: aliceblue;
        }

        button {
            border: 0;
            border-radius: 10px;
            margin-top: 100px;
            height: 80px;
            width: 300px;
            font-size: 30px;
            font-weight: 1000;
            cursor: pointer;
            transition: all 500ms ease;
            color: dodgerblue;
            background: chartreuse;
        }

        button:hover {
            background: aqua;
        }
</style>
<body>
    <div id="main">
        <h1>Магазин Тян</h1>
        <img src="https://w7.pngwing.com/pngs/360/998/png-transparent-elesis-elsword-anime-crimson-avenger-game-long-hair-cg-artwork-black-hair-fictional-character.png">
        <p>Хочешь купить меня, если да то нажимай кнопку!</p>
        <button id="buy">купить</button>
    </div>
       <script src="https://telegram.org/js/telegram-web-app.js"></script>
</body>
