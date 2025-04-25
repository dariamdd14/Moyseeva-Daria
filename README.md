# Moyseeva-Daria
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
  <title>Афиша независимых театров</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container header">
      <h1>Афиша независимых театров</h1>
      <input type="text" placeholder="Поиск спектаклей..." />
    </div>
  </header>

 <nav class="nav-menu container">
    <a href="index.html">Главная</a>
    <a href="repertoire.html">Афиша</a>
    <a href="theatres.html">Театры</a>
    <a href="about.html">О проекте</a>
  </nav>

  <section class="banner">
    <img src="images/groza.png" alt="Гроза" />
    <div class="banner-text">
      <h2>Гроза</h2>
      <p>Театр на Окраине</p>
      <p>27 апреля, 19:00</p>
      <a href="#" class="button">Купить билет</a>
    </div>
  </section>

  <section class="afisha">
    <div class="container">
      <h3>Афиша на неделю</h3>
      <div class="cards">
        <div class="card">
          <img src="images/chaika.jpg" alt="Чайка" />
          <div class="card-info">
            <h4>Чайка</h4>
            <p>Драма</p>
            <p>24 апреля, 19:00</p>
          </div>
        </div>
        <div class="card">
          <img src="images/saltan.jpg" alt="Сказка о царе Салтане" />
          <div class="card-info">
            <h4>Сказка о царе Салтане</h4>
            <p>Сказка</p>
            <p>25 апреля, 12:00</p>
          </div>
        </div>
        <div class="card">
          <img src="images/revizor.jpg" alt="Ревизор" />
          <div class="card-info">
            <h4>Ревизор</h4>
            <p>Комедия</p>
            <p>26 апреля, 19:30</p>
          </div>
        </div>
        <div class="card">
          <img src="images/prenakaz.jpg" alt="Преступление и наказание" />
          <div class="card-info">
            <h4>Преступление и наказание</h4>
            <p>Драма</p>
            <p>28 апреля, 18:00</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</body>
</html>
