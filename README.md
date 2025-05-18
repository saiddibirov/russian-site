# russian-site
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Pomoshnik</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Blog Pomoshnik</h1>
            <nav>
                <a href="#">Главная</a>
                <a href="#">Услуги</a>
                <a href="#">Контакты</a>
                <a href="#">О нас</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h2>Ваш надёжный помощник в продвижении</h2>
            <p>Быстрый старт, простое управление, настоящие результаты.</p>
        </div>
    </section>

    <section class="services">
        <div class="container">
            <h2>Наши услуги</h2>
            <div class="cards">
                <div class="card">
                    <h3>Продвижение Instagram</h3>
                    <p>Настоящие подписчики и лайки. Без ботов.</p>
                </div>
                <div class="card">
                    <h3>Раскрутка Telegram</h3>
                    <p>Подписчики и просмотры для вашего канала.</p>
                </div>
                <div class="card">
                    <h3>Продвижение TikTok</h3>
                    <p>Просмотры, лайки и фолловеры.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Blog Pomoshnik. Все права защищены.</p>
        </div>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Pomoshnik</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Blog Pomoshnik</h1>
            <nav>
                <a href="#">Главная</a>
                <a href="#">Услуги</a>
                <a href="#">Контакты</a>
                <a href="#">О нас</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h2>Ваш надёжный помощник в продвижении</h2>
            <p>Быстрый старт, простое управление, настоящие результаты.</p>
        </div>
    </section>

    <section class="services">
        <div class="container">
            <h2>Наши услуги</h2>
            <div class="cards">
                <div class="card">
                    <h3>Продвижение Instagram</h3>
                    <p>Настоящие подписчики и лайки. Без ботов.</p>
                </div>
                <div class="card">
                    <h3>Раскрутка Telegram</h3>
                    <p>Подписчики и просмотры для вашего канала.</p>
                </div>
                <div class="card">
                    <h3>Продвижение TikTok</h3>
                    <p>Просмотры, лайки и фолловеры.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Blog Pomoshnik. Все права защищены.</p>
        </div>
    </footer>
</body>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #121212;
    color: #e0e0e0;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
    padding: 20px 0;
}

header {
    background-color: #1f1f1f;
    padding: 20px 0;
    border-bottom: 1px solid #333;
}

header h1 {
    font-size: 28px;
    color: #ffffff;
}

nav {
    margin-top: 10px;
}

nav a {
    color: #bbbbbb;
    text-decoration: none;
    margin-right: 20px;
    font-size: 16px;
    transition: color 0.3s;
}

nav a:hover {
    color: #ffffff;
}

.hero {
    background: linear-gradient(to right, #222, #333);
    color: #ffffff;
    text-align: center;
    padding: 60px 20px;
}

.hero h2 {
    font-size: 32px;
    margin-bottom: 10px;
}

.services {
    background-color: #181818;
    padding: 40px 0;
}

.services h2 {
    text-align: center;
    margin-bottom: 30px;
    font-size: 26px;
    color: #ffffff;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.card {
    background-color: #2a2a2a;
    border-radius: 8px;
    padding: 20px;
    width: 300px;
    box-shadow: 0 0 12px rgba(0,0,0,0.4);
    transition: transform 0.2s;
}

.card:hover {
    transform: translateY(-5px);
}

.card h3 {
    margin-bottom: 10px;
    font-size: 20px;
    color: #ffffff;
}

.card p {
    color: #cccccc;
}

footer {
    background-color: #1f1f1f;
    color: #999999;
    text-align: center;
    padding: 20px 0;
    font-size: 14px;
}
