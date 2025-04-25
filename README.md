<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інтернет-магазин риболовних снастей</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; padding: 10px 0; text-align: center; }
        .container { width: 80%; margin: 20px auto; }
        .nav { display: flex; justify-content: space-around; background-color: #444; padding: 10px 0; }
        .nav a { color: white; text-decoration: none; padding: 10px 20px; }
        .search { text-align: center; margin-bottom: 20px; }
        .search input { padding: 10px; width: 300px; }
        .category { margin: 20px 0; }
        .category h2 { text-align: center; }
        .product-list { display: flex; flex-wrap: wrap; justify-content: space-around; }
        .product { background-color: white; padding: 15px; margin: 10px; border-radius: 8px; width: 200px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .product img { width: 100%; height: 150px; object-fit: cover; }
        .product h3 { text-align: center; }
        .product p { text-align: center; font-size: 14px; color: #777; }
        .cart { display: flex; justify-content: space-between; margin: 20px 0; }
        .cart a { color: #444; text-decoration: none; padding: 10px 20px; background-color: #ddd; border-radius: 5px; }
        .footer { background-color: #333; color: white; text-align: center; padding: 10px 0; position: fixed; width: 100%; bottom: 0; }
        .delivery-form { margin-top: 20px; }
        .delivery-form input, .delivery-form select, .delivery-form button { padding: 10px; margin: 10px 0; width: 100%; max-width: 300px; }
    </style>
</head>
<body>

<header>
    <h1>Інтернет-магазин риболовних снастей</h1>
</header>

<div class="nav">
    <a href="#home">Головна</a>
    <a href="#products">Товари</a>
    <a href="#about">Про нас</a>
    <a href="#contact">Контакти</a>
</div>

<div class="container">
    <div class="search">
        <input type="text" placeholder="Пошук товарів..." />
    </div>

    <div id="products" class="category">
        <h2>Категорії товарів</h2>
        <div class="product-list">
            <div class="product">
                <img src="https://via.placeholder.com/200x150" alt="Вудка" />
                <h3>Вудка</h3>
                <p>Ціна: 500 грн</p>
                <button>Додати в кошик</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150" alt="Котушка" />
                <h3>Котушка</h3>
                <p>Ціна: 700 грн</p>
                <button>Додати в кошик</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150" alt="Ласо" />
                <h3>Ласо</h3>
                <p>Ціна: 150 грн</p>
                <button>Додати в кошик</button>
            </div>
        </div>
    </div>

    <div class="cart">
        <a href="#">Переглянути кошик</a>
        <a href="#">Оформити замовлення</a>
    </div>

    <div class="delivery-form">
        <h2>Форма доставки</h2>
        <input type="text" placeholder="Ваше ім'я" />
        <input type="email" placeholder="Ваш email" />
        <input type="text" placeholder="Адреса доставки" />
        <select>
            <option>Виберіть метод доставки</option>
            <option>Кур'єр</option>
            <option>Самовивіз</option>
        </select>
        <button>Оформити замовлення</button>
    </div>
</div>

<div class="footer">
    <p>&copy; 2025 Інтернет-магазин риболовних снастей</p>
</div>

</body>
</html>
