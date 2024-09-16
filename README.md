<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>BLA-BLA</title>
<meta name="generator" content="Jekyll v3.10.0" />
<meta property="og:title" content="BLA-BLA" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://mortiscoder.github.io/BLA-BLA/" />
<meta property="og:url" content="https://mortiscoder.github.io/BLA-BLA/" />
<meta property="og:site_name" content="BLA-BLA" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="BLA-BLA" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"BLA-BLA","name":"BLA-BLA","url":"https://mortiscoder.github.io/BLA-BLA/"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/BLA-BLA/assets/css/style.css?v=e849e2cde136304a0c9c3f760917b97df0fc3f70">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/BLA-BLA/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://mortiscoder.github.io/BLA-BLA/">BLA-BLA</a></h1>
      

      <p>&lt;!DOCTYPE html&gt;</p>
<html lang="ru">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>мой сайт без ChatGPT</title>
    <style>
        /* Стиль заголовка */
        header {
            color: rgb(71, 11, 11);
            text-align: center;
            margin: 20px 0;
        }

        /* Стиль для всего тела страницы */
        body {
            background-color: rgb(101, 16, 16);
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* Стиль для кнопки */
        button {
            border: none;
            cursor: pointer;
            padding: 10px 20px;
            font-size: 20px;
            background-color: rgb(135, 0, 0);
            color: rgb(92, 0, 0);
            margin: 20px;
            text-align: center;
            border-radius: 5px;
            z-index: 1;
            position: relative;
        }

        /* Анимация для кнопки при нажатии */
        button:active {
            animation: press 0.2s ease forwards;
        }

        @keyframes press {
            0% {
                transform: scale(0.95);
            }
            100% {
                transform: scale(1);
            }
        }

        /* Адаптивность */
        @media (max-width: 600px) {
            button {
                font-size: 16px;
                padding: 8px 16px;
            }

            header {
                font-size: 24px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать!</h1>
    </header>
    <div>
        <button id="button">Нажмите</button>
    </div>

    <!-- Элемент аудио для воспроизведения звука -->
    <audio id="myAudio" src="spukane-4.mp3" preload="metadata"></audio>

    <!-- JavaScript код -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const button = document.getElementById('button');
            const audio = document.getElementById('myAudio');

            function playAudio() {
                if (audio) {
                    audio.currentTime = 0; // Устанавливаем время воспроизведения в начало
                    audio.play().catch(error => {
                        console.error("Ошибка воспроизведения аудио:", error);
                    });
                } else {
                    console.error("Аудио элемент не найден.");
                }
            }

            if (button) {
                button.addEventListener('click', () => {
                    playAudio();
                });
            } else {
                console.error("Кнопка не найдена.");
            }
        });
    </script>
</body>
</html>


      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  </body>
</html>
