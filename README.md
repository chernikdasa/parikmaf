
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Парикмахерская</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f0f1;
            color: #5c4b73;
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: #d8a1c3;
            color: white;
            text-align: center;
            padding: 10px;
        }
        .service {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px 0;
            background: white;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .booking {
            margin-top: 20px;
            padding: 10px;
            background-color: #f1d3e0;
        }
    </style>
</head>
<body>

<header>
    <h1>Парикмахерская "Стиль Локонов"</h1>
</header>

<div class="service">
    <h3>Стрижка Мужская</h3>
    <img src="male-haircut.jpg" alt="Мужская стрижка">
    <p>Цена: 800 руб.</p>
</div>

<div class="service">
    <h3>Стрижка Женская</h3>
    <img src="female-haircut.jpg" alt="Женская стрижка">
    <p>Цена: 1200 руб.</p>
</div>

<div class="service">
    <h3>Укладка Волос</h3>
    <img src="hair-styling.jpg" alt="Укладка волос">
    <p>Цена: 1000 руб.</p>
</div>

<div class="booking">
    <h2>Запись на услугу</h2>
    <form action="#" method="post">
        <input type="text" name="name" placeholder="Ваше имя" required><br>
        <input type="tel" name="phone" placeholder="Ваш номер телефона" required><br>
        <select name="service" required>
            <option value="" disabled selected>Выберите услугу</option>
            <option value="Мужская стрижка">Мужская стрижка</option>
            <option value="Женская стрижка">Женская стрижка</option>
            <option value="Укладка волос">Укладка волос</option>
        </select><br>
        <input type="submit" value="Записаться">
    </form>
</div>

</body>
</html>
