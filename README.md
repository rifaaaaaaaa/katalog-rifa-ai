<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Katalog Rifa AI</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Rifa AI</h1>
    </header>

    <section class="catalog">
        <div class="product">
            <img src="golden.png" alt="Rifa AI GOLDEN">
            <h2>Rifa AI GOLDEN</h2>
            <p>Super Plus: 9000/bulan</p>
            <p class="price"><span class="old-price">Rp 13.000</span> Rp 9.000</p>
        </div>

        <div class="product">
            <img src="regular.png" alt="Rifa AI REGULAR">
            <h2>Rifa AI REGULAR</h2>
            <p>Super Plus: 7000/bulan</p>
            <p class="price"><span class="old-price">Rp 11.000</span> Rp 7.000</p>
        </div>

        <div class="product">
            <img src="lite.png" alt="Rifa AI LITE">
            <h2>Rifa AI LITE</h2>
            <p>GRATIS (Free), Bebas Iklan</p>
        </div>
    </section>

    <button class="contact-button" onclick="sendMessage()">Kirim Pesan</button>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f5f5f5;
}

header {
    background: linear-gradient(to right, #0057b7, #009688);
    padding: 20px;
    color: white;
    font-size: 24px;
}

.catalog {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

.product {
    background: white;
    padding: 15px;
    margin: 10px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 80%;
    max-width: 400px;
}

.product img {
    width: 80px;
}

.price {
    font-size: 18px;
    font-weight: bold;
}

.old-price {
    text-decoration: line-through;
    color: red;
}

.contact-button {
    background-color: #25D366;
    color: white;
    border: none;
    padding: 15px;
    font-size: 18px;
    border-radius: 5px;
    margin: 20px;
    cursor: pointer;
}

.contact-button:hover {
    background-color: #1da851;
}
function sendMessage() {
    window.location.href = "https://wa.me/628xxxxxxxxxx?text=Halo,%20saya%20tertarik%20dengan%20Rifa%20AI!";
}
