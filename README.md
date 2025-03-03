<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Клининговая компания в Алматы</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: "Montserrat", sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            text-align: center;
        }
        .hero {
            background: url('cleaning-team.jpg') center/cover no-repeat;
            color: white;
            padding: 100px 0;
        }
        .hero h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }
        .hero .btn {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }
        .services, .why-choose, .pricing, .contact {
            padding: 50px 0;
            background: white;
            margin: 20px 0;
            border-radius: 10px;
        }
        .service-list {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service-item {
            background: #28a745;
            color: white;
            padding: 15px;
            border-radius: 5px;
            margin: 10px;
            font-size: 18px;
        }
        .btn {
            display: inline-block;
            background-color: #ff9800;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 18px;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact input, .contact select, .contact button {
            width: 80%;
            margin: 10px 0;
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .whatsapp-btn {
            display: block;
            background-color: #25d366;
            color: white;
            padding: 10px 20px;
            margin-top: 10px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 18px;
        }
        iframe {
            width: 100%;
            height: 300px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <!-- Главный экран -->
    <header class="hero">
        <div class="container">
            <h1>Профессиональная уборка в Алматы – Надежно, Качественно, Доступно</h1>
            <p>Опытные специалисты по уборке сделают ваш дом или офис безупречно чистым!</p>
            <a href="#contact" class="btn">Получить бесплатный расчет</a>
            <div class="trust-badges">
                <span>1000+ довольных клиентов</span>
                <span>Эко-уборка</span>
                <span>Гарантия 100% качества</span>
            </div>
        </div>
    </header>
    
    <!-- Блок с услугами -->
    <section class="services container">
        <h2>Наши услуги</h2>
        <div class="service-list">
            <div class="service-item">🏡 Уборка квартир и домов</div>
            <div class="service-item">🏢 Уборка офисов</div>
            <div class="service-item">🧼 Генеральная уборка</div>
            <div class="service-item">🏗️ Уборка после ремонта</div>
            <div class="service-item">🚚 Уборка перед переездом</div>
        </div>
    </section>
    
    <!-- Почему выбирают нас? -->
    <section class="why-choose container">
        <h2>Почему выбирают нас?</h2>
        <ul>
            <li>✅ Опытный персонал – дружелюбная, квалифицированная команда.</li>
            <li>✅ Эко-чистящие средства – безопасны для детей и домашних животных.</li>
            <li>✅ Гибкий график работы – уборка в удобное для вас время, 7 дней в неделю.</li>
            <li>✅ Прозрачные и доступные цены – никаких скрытых платежей.</li>
            <li>✅ Гарантия 100% качества – уберем до тех пор, пока вас все не устроит!</li>
        </ul>
    </section>
    
    <!-- Цены и спецпредложения -->
    <section class="pricing container">
        <h2>Цены и спецпредложения</h2>
        <p>Скидка 10% для новых клиентов!</p>
        <a href="#contact" class="btn">Рассчитать стоимость</a>
    </section>
    
    <!-- Контакты и запись -->
    <section class="contact container" id="contact">
        <h2>Свяжитесь с нами</h2>
        <form>
            <input type="text" placeholder="Имя" required>
            <input type="tel" placeholder="Телефон" required>
            <select required>
                <option value="">Выберите услугу</option>
                <option>Уборка квартир</option>
                <option>Уборка офисов</option>
            </select>
            <input type="date" required>
            <button type="submit" class="btn">Оставить заявку</button>
        </form>
        <a href="https://wa.me/77000000000" class="whatsapp-btn">WhatsApp</a>
        <p>Телефон: <a href="tel:+77000000000">+7 (700) 000-00-00</a></p>
        <p>Email: <a href="mailto:info@cleaning.kz">info@cleaning.kz</a></p>
        <iframe src="https://maps.google.com/maps?q=Алматы&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0"></iframe>
    </section>
</body>
</html>
