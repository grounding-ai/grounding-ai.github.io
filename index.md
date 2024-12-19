<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fullscreen Image</title>
    <style>
        /* Reset body and html styles */
        html, body {
            margin: 0;
            padding: 0;
            height: 100%;
        }

        /* Fullscreen image container */
        .fullscreen-image {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
        }

        /* Styling the image */
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
    <div class="fullscreen-image">
        <img src="/assets/images/HTRM-1.png" alt="Fullscreen Image">
    </div>
</body>
</html>
