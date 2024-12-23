<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гаджеты без проблем: Подготовка к поездкам</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: #007BFF;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        .btn {
            background: white;
            color: #007BFF;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .btn:hover {
            background: #0056b3;
            color: white;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .service-block {
            margin: 20px 0;
        }
        .service-block h3 {
            margin: 10px 0;
        }
        .pricing-table {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        .pricing-card {
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            flex: 1;
            max-width: 300px;
            text-align: center;
            background: #f9f9f9;
        }
        .pricing-card h3 {
            margin: 10px 0;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .contact-form {
            max-width: 600px;
            margin: auto;
            padding: 20px;
            background: #f9f9f9;
            border-radius: 10px;
            border: 1px solid #ddd;
        }
        .contact-form label {
            display: block;
            margin: 10px 0 5px;
        }
        .contact-form input, .contact-form textarea, .contact-form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            background: #007BFF;
            color: white;
            font-size: 1rem;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }
        .contact-form button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Гаджеты без проблем</h1>
        <p>Подготовка ваших устройств для безопасного и удобного использования за границей.</p>
        <a href="#services" class="btn">Узнать больше</a>
    </header>

    <section id="services">
        <h2>Наши услуги</h2>
        <div class="service-block">
            <h3>Очистка устройства</h3>
            <p>Удаление ненужных файлов, оптимизация памяти и повышение производительности.</p>
        </div>
        <div class="service-block">
            <h3>Защита данных</h3>
            <p>Шифрование данных, создание резервных копий и настройка безопасности.</p>
        </div>
        <div class="service-block">
            <h3>Удаление проблемного контента</h3>
            <p>Проверка устройства на соответствие законодательству страны назначения.</p>
        </div>
        <div class="service-block">
            <h3>Установка нужного ПО</h3>
            <p>Настройка VPN, переводчиков, карт и других приложений для поездок.</p>
        </div>
    </section>

    <section id="pricing">
        <h2>Цены</h2>
        <div class="pricing-table">
            <div class="pricing-card">
                <h3>Стандарт</h3>
                <p>$30</p>
                <p>Очистка устройства</p>
                <a href="#" class="btn">Выбрать</a>
            </div>
            <div class="pricing-card">
                <h3>Безопасность+</h3>
                <p>$50</p>
                <p>Очистка + шифрование данных</p>
                <a href="#" class="btn">Выбрать</a>
            </div>
            <div class="pricing-card">
                <h3>Премиум</h3>
                <p>$80</p>
                <p>Полная подготовка устройства</p>
                <a href="#" class="btn">Выбрать</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Свяжитесь с нами</h2>
        <form class="contact-form" action="https://formspree.io/f/your_form_id" method="POST">
            <label for="name">Имя</label>
            <input type="text" id="name" name="name" placeholder="Ваше имя" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Ваш email" required>

            <label for="message">Ваш запрос</label>
            <textarea id="message" name="message" rows="5" placeholder="Опишите, что вам нужно" required></textarea>

            <button type="submit">Отправить</button>
        </form>
    </section>

    <footer>
        <p>Свяжитесь с нами: info@gadget-ready.com | +7 (XXX) XXX-XX-XX</p>
        <p>&copy; 2024 Гаджеты без проблем. Все права защищены.</p>
    </footer>
</body>
</html>
