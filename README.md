<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boom, It's Picasso!</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            font-size: 3rem;
            font-weight: bold;
            color: white;
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: background 1s;
        }
    </style>
</head>
<body>
    <div>Boom, It's Picasso!</div>

    <script>
        function changeColor() {
            const colors = ["red", "blue", "green", "purple", "orange", "yellow", "pink"];
            document.body.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
        }

        setInterval(changeColor, 1000);
    </script>
</body>
</html>
