<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grounding AI</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #f5e6d0;
        }

        .navbar {
            width: 100%;
            height: 80px;
            background-color: #f5e6d0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        .navbar-left {
            display: flex;
            flex-direction: column;
        }

        .navbar-title {
            font-size: 24px;
            font-weight: bold;
        }

        .navbar-subtitle {
            font-size: 14px;
            color: #555;
        }

        .navbar-menu {
            display: flex;
            gap: 20px;
            list-style: none;
        }

        .navbar-menu a {
            color: #8B0000;
            text-decoration: none;
        }

        .image-section {
            width: 100%;
            height: calc(100vh - 80px);
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .image-section img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            padding: 20px;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="navbar-left">
            <div class="navbar-title">Grounding AI</div>
            <div class="navbar-subtitle">AI Atlas of AI</div>
        </div>
        <ul class="navbar-menu">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Who We Are</a></li>
            <li><a href="#">Methodology</a></li>
        </ul>
    </nav>
    <div class="image-section">
        <img src="/assets/images/HTRM-4.png" alt="AI Visualization">
    </div>
</body>
</html>
