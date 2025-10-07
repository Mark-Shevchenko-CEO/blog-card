<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Blog Preview Card</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <main>
    <h1 class="visually-hidden">Картка блогу</h1>

    <article class="card" role="article">
      <div class="card__media">
        <img class="card__img" src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=1200&auto=format&fit=crop" alt="Ілюстрація до статті: ноутбук, чашка кави та блокнот на столі" />
      </div>

      <div class="card__body">
        <span class="card__tag" aria-label="Категорія">DESIGN</span>
        <span class="card__meta" aria-label="Дата публікації">Опубліковано 07 жовтня 2025</span>

        <h2 class="card__title">
          <a href="#" target="_self" rel="bookmark">10 порад з Flexbox і CSS Grid для чистих інтерфейсів</a>
        </h2>

        <p class="card__desc">Як поєднувати грід для макролейауту, а флекс — для дрібних груп елементів. Плюс дрібні лайфхаки з gap, auto-fit та мінімальними треками.</p>

        <div class="card__author">
          <img class="card__avatar" src="https://images.unsplash.com/photo-1599566150163-29194dcaad36?q=80&w=256&auto=format&fit=crop" alt="Аватар автора" />
          <div class="card__author-info">
            <span class="card__author-name">Шевченко Марко</span>
            <span class="card__author-role">Студент • Другий курс</span>
          </div>
        </div>
      </div>
    </article>
  </main>
</body>
</html>
