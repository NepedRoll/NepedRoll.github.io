<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strona</title>
    <style>
        body {
            background-color: yellow; /* żółte tło */
            margin: 0; /* Usunięcie marginesów */
            display: flex;
            justify-content: center; /* Wyśrodkowanie zawartości na środku poziomo */
            align-items: center; /* Wyśrodkowanie zawartości na środku pionowo */
            height: 100vh; /* Wysokość strony na cały widok */
        }

        h1 {
            text-align: center; /* Wypośrodkowanie tekstu */
            cursor: pointer; /* Zmiana kursora na wskazujący */
            padding: 20px; /* Dodanie odstępu wokół napisu */
        }
    </style>
</head>
<body>

    <h1 onclick="window.location.href = 'test.html';">Strona</h1>

</body>
</html>
