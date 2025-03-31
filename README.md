<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIFF KOPITIAM MENU</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(to right, #f8f9fa, #ecf0f1);
            color: #333;
        }

        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 40px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            backdrop-filter: blur(8px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        h1 a {
            font-family: 'Playfair Display', serif;
            text-decoration: none;
            font-size: 40px;
            color: #34495e;
            font-weight: 700;
            transition: all 0.3s ease-in-out;
        }

        h1 a:hover {
            color: #e67e22;
        }

        h1 a:active {
            transform: scale(0.98);
        }

        h2 {
            font-size: 24px;
            color: #e67e22;
            border-left: 5px solid #e67e22;
            padding-left: 15px;
            margin-top: 40px;
            font-weight: 600;
        }

        .menu-item {
            display: flex;
            align-items: center;
            padding: 15px;
            margin-bottom: 10px;
            background: rgba(255, 255, 255, 0.6);
            border-radius: 12px;
            transition: all 0.4s ease-in-out;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(5px);
        }

        .menu-item:hover {
            transform: scale(1.05);
            background: linear-gradient(135deg, #ffffff, #f9e79f);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

        .menu-item img {
            width: 85px;
            height: 85px;
            object-fit: cover;
            border-radius: 12px;
            border: 2px solid #e67e22;
        }

        .menu-text {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex: 1;
            padding: 0 20px;
        }

        .menu-name {
            font-size: 18px;
            font-weight: 600;
            color: #2c3e50;
        }

        .menu-price {
            font-size: 18px;
            font-weight: 700;
            color: #e67e22;
            transition: color 0.3s;
        }

        .menu-item:hover .menu-price {
            color: #d35400;
        }

        @media (max-width: 600px) {
            .menu-item {
                flex-direction: column;
                align-items: center;
                text-align: center;
                padding: 20px;
            }

            .menu-text {
                flex-direction: column;
                gap: 8px;
                padding-top: 10px;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>
            <a href="http://127.0.0.1:5500/index.html" target="_blank">
                TIFF KOPITIAM MENU
            </a>
        </h1>

        <h2>Main Course</h2>
        <section class="menu-item">
            <img src="nasilemak.png" alt="Nasi Lemak Special">
            <div class="menu-text">
                <span class="menu-name">Nasi Lemak Special</span>
                <span class="menu-price">RM 9.50</span>
            </div>
        </section>
        <section class="menu-item">
            <img src="chickenrice.png" alt="Hainanese Chicken Rice">
            <div class="menu-text">
                <span class="menu-name">Hainanese Chicken Rice</span>
                <span class="menu-price">RM 8.50</span>
            </div>
        </section>

        <h2>Appetizer</h2>
        <section class="menu-item">
            <img src="kayatoast.png" alt="Kaya Toast">
            <div class="menu-text">
                <span class="menu-name">Kaya Toast</span>
                <span class="menu-price">RM 4.00</span>
            </div>
        </section>
        <section class="menu-item">
            <img src="currypuff.png" alt="Curry Puff">
            <div class="menu-text">
                <span class="menu-name">Curry Puff</span>
                <span class="menu-price">RM 3.50</span>
            </div>
        </section>

        <h2>Beverages</h2>
        <section class="menu-item">
            <img src="tehtarik.png" alt="Teh Tarik">
            <div class="menu-text">
                <span class="menu-name">Teh Tarik</span>
                <span class="menu-price">RM 3.50</span>
            </div>
        </section>
        <section class="menu-item">
            <img src="teho.png" alt="Kopi O">
            <div class="menu-text">
                <span class="menu-name">Kopi O</span>
                <span class="menu-price">RM 2.50</span>
            </div>
        </section>

        <h2>Side Dish</h2>
        <section class="menu-item">
            <img src="egg.png" alt="Fried Egg">
            <div class="menu-text">
                <span class="menu-name">Fried Egg</span>
                <span class="menu-price">RM 2.00</span>
            </div>
        </section>
        <section class="menu-item">
            <img src="sambal.png" alt="Sambal Anchovies">
            <div class="menu-text">
                <span class="menu-name">Sambal Anchovies</span>
                <span class="menu-price">RM 3.00</span>
            </div>
        </section>
    </div>
</body>

</html>
