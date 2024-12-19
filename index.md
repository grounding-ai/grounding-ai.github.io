<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fullscreen Image</title>
    <style>
        /* Reset styles */
        html, body {
            margin: 0;
            padding: 0;
        }

        /* Header styling */
        header {
            background-color: #f5e6d0; /* Match the beige color */
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
            font-size: 1.5rem;
        }

        header nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #b04b4b; /* Match the red link color */
            font-weight: bold;
        }

        /* Fullscreen image section */
        .fullscreen-image {
            position: relative;
            width: 100%;
            height: calc(100vh - 70px); /* Adjust to account for the header height */
            overflow: hidden;
        }

        .fullscreen-image img {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            min-width: 100%;
            min-height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Grounding AI</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#who-we-are">Who We Are</a>
            <a href="#methodology">Methodology</a>
        </nav>
    </header>

</head>
<body>
    <div class="fullscreen-image">
        <img src="/assets/images/HTRM-1.png" alt="Fullscreen Image">
    </div>
</body>
</html>
