<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mini App</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
        #counter { font-size: 2em; margin-bottom: 20px; }
        .button-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 300px; /* O'zingizga kerakli balandlik */
        }
        .round-button {
            width: 150px; /* Tugmaning kengligi */
            height: 150px; /* Tugmaning balandligi */
            border-radius: 50%; /* Doira shakli */
            background: url('cucumber.png') no-repeat center center; /* Bodring rasmi */
            background-size: cover; /* Rasmning tugma ichida to'liq ko'rinishi uchun */
            border: none;
            cursor: pointer;
            outline: none;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <div id="counter">Hisoblagich: 0</div>
    <div class="button-container">
        <button class="round-button" onclick="incrementCounter()"></button>
    </div>
    <script>
        let counter = 0;
        function incrementCounter() {
            counter++;
            document.getElementById('counter').innerText = 'Hisoblagich: ' + counter;
        }
    </script>
</body>
</html>
