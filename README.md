<!DOCTYPE html>
<html lang="mn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CS Non Pro League by Richdad</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Orbitron', sans-serif;
      margin: 0;
      background-color: #0d0d0d;
      color: #f5f5f5;
      line-height: 1.6;
    }
    header, footer {
      background: #1a1a1a;
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: #f5f5f5;
      text-decoration: none;
    }
    .container {
      max-width: 960px;
      margin: auto;
      padding: 20px;
    }
    h1, h2 {
      color: #ffcc00;
    }
    form input, form button {
      padding: 10px;
      margin: 5px 0;
      width: 100%;
      border: none;
      border-radius: 5px;
    }
    form button {
      background-color: #ffcc00;
      color: #000;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>CS Non Pro League by Richdad</h1>
    <nav>
      <a href="#about">Тухай</a>
      <a href="#info">Мэдээлэл</a>
      <a href="#register">Бүртгүүлэх</a>
      <a href="#contact">Холбоо барих</a>
    </nav>
  </header>

  <div class="container">
    <section id="about">
      <h2>Лигийн тухай</h2>
      <p>CS Non Pro League-д тавтай морил – Монголын сонирхогч багуудад зориулсан онлайн CS2 тэмцээн. Сарын бүрийн тэмцээнд оролцож, мөнгөн шагнал болон нэр хүндийн төлөө өрсөлдөөрэй!</p>
    </section>

    <section id="info">
      <h2>Тэмцээний мэдээлэл</h2>
      <ul>
        <li>🎯 Тоглоом: Counter-Strike 2 (CS2)</li>
        <li>📍 Хэлбэр: Онлайн, зөвхөн Монгол</li>
        <li>💸 Бүртгэлийн хураамж: Баг бүрт 50,000₮</li>
        <li>🏆 Шагналын сан:
          <ul>
            <li>1-р байр – 60%</li>
            <li>2-р байр – 15%</li>
            <li>3-р байр – 7.5%</li>
            <li>Үлдсэн хувь нь серверийн зардалд</li>
          </ul>
        </li>
        <li>📅 Хугацаа: Сарын бүр</li>
      </ul>
    </section>

    <section id="register">
      <h2>Баг бүртгүүлэх</h2>
      <form action="#" method="post">
        <input type="text" placeholder="Багийн нэр" required />
        <input type="text" placeholder="Ахлагчийн нэр" required />
        <input type="email" placeholder="Имэйл хаяг" required />
        <input type="text" placeholder="Discord хэрэглэгчийн нэр" required />
        <button type="submit">Бүртгүүлэх</button>
      </form>
    </section>

    <section id="contact">
      <h2>Холбоо барих</h2>
      <p>Холбоо барих мэдээлэл: Тун удахгүй</p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 CS Non Pro League by Richdad. Бүх эрх хуулиар хамгаалагдсан.</p>
  </footer>
</body>
</html>
