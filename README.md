
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strona z klikalnymi obrazkami</title>
    <style>
        body {
            background-color: yellow; /* Żółte tło */
            margin: 0; /* Usunięcie marginesów */
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh; /* Wysokość strony na cały widok */
        }

        h1 {
            color: red; /* Czerwony kolor tekstu */
            font-size: 3em;
            animation: bounce 2s infinite alternate; /* Animacja */
        }

        .image-container {
            display: flex;
            justify-content: center;
            margin-top: 20px; /* Odstęp od napisu */
        }

        .image-container img {
            width: 100px; /* Szerokość obrazu */
            height: auto; /* Dostosowanie wysokości proporcjonalnie */
            margin: 0 15px; /* Marginesy między obrazami */
        }

        .number-container {
            display: flex;
            justify-content: center;
            margin-top: 30px; /* Odstęp od obrazów */
        }

        .number {
            font-size: 2em; /* Rozmiar czcionki */
            margin: 0 30px; /* Marginesy między napisami */
        }
    </style>
</head>
<body>

    <center><h1>Crossout Market</h1></center>

    <div class="image-container">
        <a href="test1.html"><img src="1.png" alt="Opis zdjęcia 1"></a>
        <a href="test2.html"><img src="2.png" alt="Opis zdjęcia 2"></a>
        <a href="test3.html"><img src="3.png" alt="Opis zdjęcia 3"></a>
        <a href="test4.html"><img src="4.png" alt="Opis zdjęcia 4"></a>
        <a href="test5.html"><img src="5.png" alt="Opis zdjęcia 5"></a>
    </div>

    <div class="number-container">
        <div class="number">9999</div>
        <div class="number">9999</div>
        <div class="number">9999</div>
        <div class="number">9999</div>
        <div class="number">9999</div>
    </div>

</body>
</html>
