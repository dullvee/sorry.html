<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sad Kitten</title>
    <style>
        body {
            background-color: black;
            height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px #000000;
            font-size: 2em;
            flex-direction: column;
        }
        .image-container {
            position: relative;
            width: 300px; /* Adjust the width as needed */
            height: 300px; /* Adjust the height as needed */
            background-image: url('sad_kitten.jpeg');
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center;
        }
        .text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="image-container">
        <div class="text">I'm sorry for being pain in the ass. I love you.</div>
    </div>
</body>
</html>
