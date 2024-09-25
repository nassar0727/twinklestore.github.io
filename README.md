# twinkle-store
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Twinkle Store</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100vh;
            background-color: #f7e8d3; /* Match background color */
            font-family: 'Poppins', sans-serif; /* Matching font */
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .container {
            text-align: center;
            margin-left: 10%;
            animation: fadeIn 3s ease-in-out;
        }
        img {
            max-width: 200px;
            height: auto;
        }
        h1 {
            font-size: 2.5rem;
            color: #333;
            margin-top: 20px;
        }
        .instagram-button {
            margin-top: 30px;
            padding: 10px 20px;
            background-color: #f09433;
            background-image: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s ease-in-out;
        }
        .instagram-button:hover {
            background-color: #bc1888;
        }

        /* Add logo in the bottom left corner */
        .small-logo {
            position: absolute;
            bottom: 20px;
            left: 20px;
            max-width: 80px;
        }

        /* Product photos on the right */
        .product-grid {
            position: absolute;
            right: 0;
            display: grid;
            grid-template-columns: repeat(2, 150px);
            gap: 10px;
            margin-right: 10%;
            animation: slideInRight 2s ease-in-out;
        }
        .product-grid img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .product-grid img:hover {
            transform: scale(1.1);
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes slideInRight {
            0% { transform: translateX(100%); }
            100% { transform: translateX(0); }
        }
    </style>
</head>
<body>

    <!-- Main content in the center -->
    <div class="container">
        <img src="logo.png" alt="Twinkle Store Logo">
        <h1>Twinkle online store</h1>
        <h2>coming soon ...</h2>
        <a href="https://www.instagram.com/__twinkle.store__?igsh=NnQyNWhkdm5teDRr" target="_blank" class="instagram-button">Contact me on Instagram</a>
    </div>

    <!-- Small logo in the bottom left corner -->
    <img src="Capture.png" alt="Small Logo" class="small-logo">

    <!-- Product photos on the right -->
    <div class="product-grid">
        <img src="product1.jpg" alt="Product 1">
        <img src="product2.jpg" alt="Product 2">
        <img src="product3.jpg" alt="Product 3">
        <img src="p0.jpeg" alt="Product 4">
        <img src="p5.jpeg" alt="Product 5">
        <img src="p6.jpeg" alt="Product 6">
        <img src="p7.jpeg" alt="Product 7">
        <img src="p8.jpeg" alt="Product 8">
        <img src="p9.jpeg" alt="Product 9">
        <img src="product4.jpg" alt="Product 4">
    </div>

</body>
</html>