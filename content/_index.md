---
description: Pretty cool description
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Call to Action</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .image-container {
            display: absolute;
            transform: rotate(15deg);
            margin-bottom: 20px;
            transition: transform 0.3s ease;
        }
        .image-container:hover {
            display: absolute;
            transform: rotate(40deg);
            margin-bottom: 20px;
        }
        .cta-button {
            display: inline-block;
            background-color: #007bff;
            color: white;
            padding: 15px 30px;
            font-size: 20px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            z-index:1;
        }
        .cta-button:hover {
            background-color: #0056b3;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="image-container">
        <img src="./books/img/3d_book.png" alt="3d book" width="300">
    <br>
    </div>
    <a href="https://a.co/d/j1ZJTWB" class="cta-button">Get Your Copy Today!</a>
</body>
</html>