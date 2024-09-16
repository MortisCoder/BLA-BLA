<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
    <audio id="myAudio"
