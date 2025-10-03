[одностраничный_сайт_куплю_продам (2).html](https://github.com/user-attachments/files/22684526/_._._.2.html)
<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Куплю/Продам — быстро и надежно</title>
  <meta name="description" content="Размещайте объявления о покупке и продаже — простая подача, быстрый отклик, безопасные сделки." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#f5f7fb;--card:#ffffff;--accent:#6c5ce7;--muted:#6b7280;--maxw:1100px}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;line-height:1.5;margin:0;background:var(--bg);color:#111}
    .container{max-width:var(--maxw);margin:36px auto;padding:20px}
    header{display:flex;justify-content:space-between;align-items:center;padding:16px 0}
    .logo{display:flex;gap:12px;align-items:center}
    .logo .mark{width:44px;height:44px;background:linear-gradient(135deg,var(--accent),#a78bfa);border-radius:10px;display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    nav{display:flex;gap:14px}
    nav a{color:var(--muted);text-decoration:none;font-weight:600}
    .btn{background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600}

    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;margin-top:12px}
    .hero h1{font-size:34px;margin:0 0 10px}
    .hero p{color:var(--muted);margin:0 0 18px}
    .search-card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(20,20,50,0.06)}
    .search-row{display:flex;gap:8px}
    .search-row input, .search-row select{flex:1;padding:12px;border-radius:8px;border:1px solid #e6e9f2}
    .search-row button{padding:12px 16px;border-radius:8px;border:none;background:var(--accent);color:#fff;font-weight:700}

    .features{display:flex;gap:14px;margin-top:28px}
    .feature{background:var(--card);padding:14px;border-radius:10px;flex:1;box-shadow:0 6px 18px rgba(20,20,50,0.04)}
    .feature h3{margin:0 0 8px}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:22px}

    .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:18px}
    .card{background:var(--card);border-radius:12px;padding:14px;box-shadow:0 6px 18px rgba(20,20,50,0.04)}
    .card img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    .card h4{margin:10px 0 6px}
    .card p{margin:0;color:var(--muted);font-size:14px}

    .sidebar{background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(20,20,50,0.04)}
    form .field{margin-bottom:12px}
    label{display:block;margin-bottom:6px;font-weight:600}
    input[type="text"], input[type="email"], input[type="file"], textarea, select{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9f2}
    textarea{min-height:110px}
    .muted{color:var(--muted);font-size:13px}

    footer{margin-top:34px;padding:18px 0;color:var(--muted);text-align:center}

    .share{margin-top:20px;text-align:center}
    .share button{background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;font-weight:600;border:none;cursor:pointer}

    /* Responsive */
    @media (max-width:980px){.hero{grid-template-columns:1fr} .cards{grid-template-columns:repeat(2,1fr)} }
    @media (max-width:620px){.cards{grid-template-columns:1fr}.features{flex-direction:column}.nav{display:none}.container{margin:18px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <div class="mark">КП</div>
        <div>
          <div style="font-weight:700">Куплю/Продам</div>
          <div class="muted" style="font-size:13px">Быстро — Надёжно — Удобно</div>
        </div>
      </div>
      <nav>
        <a href="#how">Как это работает</a>
        <a href="#ads">Объявления</a>
        <a href="#contacts">Контакты</a>
        <a class="btn" href="#post">Разместить объявление</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <h1>Разместите объявление и найдите покупателя за считанные часы</h1>
        <p>Создавайте объявления с фото, указывайте цену и опции. Мы поможем быстро найти надежных покупателей и продавцов.</p>

        <div class="features">
          <div class="feature">
            <h3>Быстрая подача</h3>
            <p class="muted">Заполните форму — и объявление появится на сайте сразу.</p>
            <button onclick="alert('Ваше объявление размещено мгновенно!')" class="btn" style="margin-top:10px;width:100%">Попробовать</button>
          </div>
          <div class="feature">
            <h3>Безопасность</h3>
            <p class="muted">Модерация и правила для честных сделок.</p>
            <button onclick="alert('Сделка проходит с защитой!')" class="btn" style="margin-top:10px;width:100%">Подробнее</button>
          </div>
          <div class="feature">
            <h3>Поддержка</h3>
            <p class="muted">Интеграция с аналитикой и подсказки для объявлений.</p>
            <button onclick="alert('Свяжитесь с поддержкой!')" class="btn" style="margin-top:10px;width:100%">Связаться</button>
          </div>
        </div>

        <div class="grid" id="ads">
          <div class="card">
            <input type="file" accept="image/*" onchange="previewImage(event, 'img1')">
            <img id="img1" src="https://via.placeholder.com/600x360.png?text=Товар+1" alt="Товар 1">
            <h4 contenteditable="true">Ноутбук HP — 2020</h4>
            <p class="muted" contenteditable="true">Цена: 120 000 ₸ · Алматинская обл.</p>
          </div>
          <div class="card">
            <input type="file" accept="image/*" onchange="previewImage(event, 'img2')">
            <img id="img2" src="https://via.placeholder.com/600x360.png?text=Товар+2" alt="Товар 2">
            <h4 contenteditable="true">Смартфон — iPhone 12</h4>
            <p class="muted" contenteditable="true">Цена: 95 000 ₸ · Нур-Султан</p>
          </div>
          <div class="card">
            <input type="file" accept="image/*" onchange="previewImage(event, 'img3')">
            <img id="img3" src="https://via.placeholder.com/600x360.png?text=Товар+3" alt="Товар 3">
            <h4 contenteditable="true">Велосипед горный</h4>
            <p class="muted" contenteditable="true">Цена: 40 000 ₸ · Кокшетау</p>
          </div>
        </div>

      </div>

      <aside class="sidebar" id="post">
        <h3 style="margin-top:0">Подать объявление</h3>
        <form id="adForm" onsubmit="return submitAd(event)">
          <div class="field">
            <label for="title">Заголовок</label>
            <input id="title" type="text" placeholder="Кратко опишите товар" required>
          </div>
          <div class="field">
            <label for="price">Цена (₸)</label>
            <input id="price" type="text" placeholder="Например: 120000" required>
          </div>
          <div class="field">
            <label for="region">Регион</label>
            <select id="region">
              <option>Алматы</option>
              <option>Нур-Султан</option>
              <option>Кокшетау</option>
              <option>Другой</option>
            </select>
          </div>
          <div class="field">
            <label for="desc">Описание</label>
            <textarea id="desc" placeholder="Опишите состояние, комплектацию, контакты"></textarea>
          </div>
          <div class="field">
            <label for="email">Email для связи</label>
            <input id="email" type="email" placeholder="example@mail.com" required>
          </div>
          <div class="field">
            <label for="photo">Фото товара</label>
            <input id="photo" type="file" accept="image/*">
          </div>
          <div class="field">
            <button class="btn" type="submit">Разместить</button>
          </div>
          <div class="muted">Нажимая «Разместить», вы соглашаетесь с правилами сайта.</div>
        </form>

        <script>
          function submitAd(e){
            e.preventDefault();
            const t = document.getElementById('title').value.trim();
            const p = document.getElementById('price').value.trim();
            const em = document.getElementById('email').value.trim();
            if(!t || !p || !em){alert('Пожалуйста, заполните обязательные поля.');return false}
            alert('Спасибо! Ваше объявление отправлено на модерацию.');
            document.getElementById('adForm').reset();
            return false;
          }

          function previewImage(event, imgId){
            const reader = new FileReader();
            reader.onload = function(){
              document.getElementById(imgId).src = reader.result;
            }
            reader.readAsDataURL(event.target.files[0]);
          }

          function shareSite(){
            const url = window.location.href.replace('http://','https://');
            navigator.clipboard.writeText(url);
            alert('Ссылка скопирована: ' + url);
          }
        </script>
      </aside>
    </section>

    <section id="how" style="margin-top:28px">
      <h2 style="margin-top:0">Как это работает</h2>
      <div class="cards">
        <div class="card">
          <h4>1. Создайте объявление</h4>
          <p class="muted">Добавьте фото, описание и цену — это займет пару минут.</p>
        </div>
        <div class="card">
          <h4>2. Получите отклики</h4>
          <p class="muted">Покупатели свяжутся с вами прямо по контактам в объявлении.</p>
        </div>
        <div class="card">
          <h4>3. Завершите сделку</h4>
          <p class="muted">Договаривайтесь о доставке и оплате безопасно.</p>
        </div>
      </div>
    </section>

    <section id="contacts" style="margin-top:28px;display:flex;gap:12px;align-items:flex-start">
      <div style="flex:1;background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(20,20,50,0.04)">
        <h3 style="margin-top:0">Контакты</h3>
        <p class="muted">Свяжитесь с нами по email: support@example.com или заполните форму ниже.</p>
        <form onsubmit="alert('Сообщение отправлено!');return false">
          <input type="text" placeholder="Ваше имя" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9f2;margin-bottom:8px">
          <input type="email" placeholder="Email" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9f2;margin-bottom:8px">
          <textarea placeholder="Ваше сообщение" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9f2;margin-bottom:8px"></textarea>
          <button class="btn" style="width:100%">Отправить</button>
        </form>
      </div>
      <div style="width:320px;background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(20,20,50,0.04)">
        <h3 style="margin-top:0">Подписка</h3>
        <p class="muted">Получать лучшие предложения и советы по размещению.</p>
        <form onsubmit="alert('Спасибо!');return false">
          <input type="email" placeholder="Email" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9f2;margin-bottom:8px">
          <button class="btn" style="width:100%">Подписаться</button>
        </form>
      </div>
    </section>

    <div class="share">
      <button onclick="shareSite()">Поделиться ссылкой (https)</button>
    </div>

    <footer>
      © 2025 Куплю/Продам — Все права защищены · Правила и безопасность
    </footer>
  </div>
</body>
</html>
