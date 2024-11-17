<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Купите стильные кепки по выгодной цене!">
    <title>Магазин кепок</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin-bottom: 0.5rem;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 2rem auto;
            text-align: center;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            justify-content: center;
        }

        .product {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        .product:hover {
            transform: scale(1.05);
        }

        .product img {
            max-width: 100%;
            border-radius: 8px;
        }

        .product h2 {
            font-size: 1.2rem;
            margin: 1rem 0;
        }

        .product p {
            color: #555;
            margin: 0.5rem 0 1rem;
        }

        .product button {
            background: #333;
            color: #fff;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .product button:hover {
            background: #555;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: #fff;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Магазин стильных кепок</h1>
        <p>Купите качественные кепки с доставкой по всей стране!</p>
    </header>

    <div class="container">
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Кепка 1">
                <h2>Кепка Classic</h2>
                <p>Удобная и стильная кепка на каждый день.</p>
                <p><strong>Цена: 1200 ₽</strong></p>
                <button>Купить</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Кепка 2">
                <h2>Кепка Sport</h2>
                <p>Идеальный выбор для активного отдыха.</p>
                <p><strong>Цена: 1500 ₽</strong></p>
                <button>Купить</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Кепка 3">
                <h2>Кепка Premium</h2>
                <p>Элегантная кепка для настоящих ценителей.</p>
                <p><strong>Цена: 2000 ₽</strong></p>
                <button>Купить</button>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Магазин кепок. Все права защищены.</p>
    </footer>

</body>
</html>
