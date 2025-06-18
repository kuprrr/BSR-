# BSR-
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BSR Auto</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>BSR Auto</h1>
        <nav>
            <a href="#catalog">Каталог</a>
            <a href="#add-car">Добавить объявление</a>
        </nav>
    </header>

    <section id="catalog">
        <h2>Каталог автомобилей</h2>
        <div id="car-list">
            <!-- Здесь будут отображаться объявления -->
        </div>
    </section>

    <section id="add-car">
        <h2>Добавить объявление</h2>
        <form id="car-form">
            <input type="text" id="brand" placeholder="Марка" required>
            <input type="text" id="model" placeholder="Модель" required>
            <input type="number" id="year" placeholder="Год" required>
            <input type="number" id="mileage" placeholder="Пробег (км)" required>
            <input type="number" id="price" placeholder="Цена" required>
            <input type="text" id="contact" placeholder="Контакт" required>
            <textarea id="description" placeholder="Описание"></textarea>
            <button type="submit">Добавить</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 BSR Auto</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
