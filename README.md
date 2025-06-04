<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Музыка — Music World</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #111;
      color: #fff;
    }

    header {
      background: #1db954;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    section {
      padding: 2rem;
      text-align: center;
    }

    .player {
      margin-top: 1rem;
    }

    audio {
      width: 80%;
      max-width: 600px;
      margin-top: 1rem;
    }

    footer {
      background: #000;
      padding: 1rem;
      text-align: center;
      color: #888;
      font-size: 0.9rem;
    }

    .btn {
      display: inline-block;
      background: #1db954;
      color: white;
      padding: 0.7rem 1.2rem;
      border-radius: 30px;
      text-decoration: none;
      margin-top: 1rem;
    }

    a.btn:hover {
      background: #17a44d;
    }
  </style>
</head>
<body>

  <header>
    <h1>Музыкальный Мир</h1>
    <p>Погрузись в звуки, которые вдохновляют</p>
  </header>

  <section>
    <h2>О проекте</h2>
    <p>Мы делимся лучшей музыкой: от классики до современных битов. Вдохновение, ритм, душа — всё здесь.</p>
    <a href="#player" class="btn">Слушать музыку</a>
  </section>

  <section id="player" class="player">
    <h2>Слушай прямо сейчас</h2>
    <audio controls>
      <source src="your-audio.mp3" type="audio/mpeg">
      Ваш браузер не поддерживает воспроизведение аудио.
    </audio>
    <p style="color: #aaa;">* Замените ссылку на свой аудиофайл</p>
  </section>

  <section>
    <h2>Контакты</h2>
    <p>📧 music@example.com</p>
    <p>📱 +7 (900) 123-45-67</p>
  </section>

  <footer>
    &copy; 2025 Музыкальный Мир. Все права защищены.
  </footer>

</body>
</html>
