<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ООО "Kazakh IT" — Лучшая IT-компания</title>
  <style>
    /* Плавная прокрутка */
    html {
      scroll-behavior: smooth;
    }

    /* Общие стили */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background: linear-gradient(135deg, #000000, #001f3f);
      color: #f0f0f0;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #0066cc, #00a86b);
      color: white;
      padding: 20px 0;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
    .logo {
      width: 120px;
      height: 120px;
      background-color: white;
      border-radius: 50%;
      margin: 0 auto 15px;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }
    .logo img {
      width: 100%;
      height: 100%;
      object-fit: contain;
      border-radius: 50%;
    }
    nav {
      background: #2c3e50;
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #00a86b;
    }
    section {
      max-width: 1200px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      text-align: center;
      margin-bottom: 25px;
      color: #ffffff;
    }
    .rules {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .rules ol {
      padding-left: 20px;
      font-size: 18px;
      color: #333;
    }
    .rules li {
      margin-bottom: 12px;
    }
    .team {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }
    .employee {
      background: white;
      width: 220px;
      padding: 20px;
      border-radius: 12px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    .employee h3 {
      margin-top: 10px;
      color: #0066cc;
    }
    .employee p {
      color: #333;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 25px;
      margin-top: 20px;
    }
    .product {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      text-align: left;
      color: #333;
    }
    .product-header {
      background: #0066cc;
      color: white;
      padding: 12px 15px;
      font-weight: bold;
      font-size: 18px;
    }
    .product-body {
      padding: 15px;
      font-size: 14px;
    }
    .product-body p {
      margin: 8px 0;
    }
    .product-body strong {
      color: #0066cc;
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <!-- Шапка сайта -->
  <header>
    <div class="logo">
      <img src="https://i.imgur.com/5s7FQjL.png" alt="Логотип Kazakh IT" />
    </div>
    <h1>ООО "Kazakh IT"</h1>
    <p>Надёжность. Технологии. Уважение.</p>
  </header>

  <!-- Навигация -->
  <nav>
    <a href="#rules">Правила</a>
    <a href="#team">Сотрудники</a>
    <a href="#products">Товары</a>
  </nav>

  <!-- Правила -->
  <section id="rules">
    <h2>Правила работы в ООО "Kazakh IT"</h2>
    <div class="rules">
      <ol>
        <li><strong>Не ругаться.</strong></li>
        <li><strong>Быть вежливым.</strong></li>
        <li><strong>Уважать всех работников.</strong></li>
        <li><strong>Перерыв два раза в день.</strong></li>
        <li><strong>Не опаздывать.</strong></li>
        <li><strong>Соблюдать технику безопасности.</strong></li>
        <li><strong>Не засорять чат.</strong></li>
      </ol>
    </div>
  </section>

  <!-- Сотрудники -->
  <section id="team">
    <h2>Наша команда</h2>
    <div class="team">
      <div class="employee">
        <div class="logo">👤</div>
        <h3>Евгений</h3>
        <p>Владелец</p>
      </div>
      <div class="employee">
        <div class="logo">👔</div>
        <h3>Захар</h3>
        <p>Директор</p>
      </div>
      <div class="employee">
        <div class="logo">🧹</div>
        <h3>Константин</h3>
        <p>Уборщик</p>
      </div>
      <div class="employee">
        <div class="logo">🧮</div>
        <h3>Кирилл</h3>
        <p>Бухгалтер</p>
      </div>
    </div>
  </section>

  <!-- Товары -->
  <section id="products">
    <h2>Наши товары</h2>
    <div class="products">
      <!-- Ноутбуки 1–25 -->
      <div class="product">
        <div class="product-header">Dell XPS 13 9315</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1250U</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 13.4", 1920×1200, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.2 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">MacBook Air M2</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Apple M2</p>
          <p><strong>ОЗУ:</strong> 16 ГБ Unified</p>
          <p><strong>Видеокарта:</strong> Apple M2 GPU (8 ГБ)</p>
          <p><strong>Экран:</strong> 13.6", 2560×1664, Liquid Retina</p>
          <p><strong>ОС:</strong> macOS</p>
          <p><strong>Вес:</strong> 1.24 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">ThinkPad X1 Carbon</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1365U</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 14.0", 1920×1200, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.12 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">HP Spectre x360 14</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1355U</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 13.5", 3000×2000, OLED, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.49 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">ASUS ZenBook 14X</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i9-13900H</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 3050 (6 ГБ)</p>
          <p><strong>Экран:</strong> 14.5", 2880×1800, OLED, 90 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.7 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Acer Swift 3</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 7 7730U</p>
          <p><strong>ОЗУ:</strong> 16 ГБ DDR4</p>
          <p><strong>Видеокарта:</strong> AMD Radeon</p>
          <p><strong>Экран:</strong> 14.0", 1920×1080, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.21 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Surface Laptop 5</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1255U</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 13.5", 2256×1504, PixelSense, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.27 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">MSI Summit E13 Flip</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1260P</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 13.3", 1920×1080, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.5 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Lenovo Yoga 9i</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1360P</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 14.0", 3840×2400, OLED, 90 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.58 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Dell Inspiron 16 Plus</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-13620H</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4060 (8 ГБ)</p>
          <p><strong>Экран:</strong> 16.0", 3072×1920, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 2.05 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">ASUS ROG Zephyrus G14</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 9 7940HS</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4060 (8 ГБ)</p>
          <p><strong>Экран:</strong> 14.0", 2560×1600, OLED, 120 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.72 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">HP Envy 16</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i9-13900H</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4070 (8 ГБ)</p>
          <p><strong>Экран:</strong> 16.0", 3840×2400, OLED, 120 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 2.1 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">MacBook Pro 14 M3</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Apple M3</p>
          <p><strong>ОЗУ:</strong> 16 ГБ Unified</p>
          <p><strong>Видеокарта:</strong> Apple M3 GPU (10 ГБ)</p>
          <p><strong>Экран:</strong> 14.2", 3024×1964, Mini-LED, 120 Гц</p>
          <p><strong>ОС:</strong> macOS</p>
          <p><strong>Вес:</strong> 1.6 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Lenovo Legion 5 Pro</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 7 7745HX</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4070 (8 ГБ)</p>
          <p><strong>Экран:</strong> 16.0", 2560×1600, IPS, 165 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 2.52 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Acer Predator Helios 16</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i9-13900HX</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4080 (12 ГБ)</p>
          <p><strong>Экран:</strong> 16.0", 2560×1600, IPS, 165 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 2.6 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Razer Blade 14</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 9 7940HS</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4070 (8 ГБ)</p>
          <p><strong>Экран:</strong> 14.0", 2560×1600, OLED, 165 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.8 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">MSI Stealth 16 Studio</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i9-13900H</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4080 (12 ГБ)</p>
          <p><strong>Экран:</strong> 16.0", 2560×1600, IPS, 240 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 2.2 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Huawei MateBook X Pro</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1360P</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 14.2", 3120×2160, IPS, 90 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.26 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Samsung Galaxy Book3</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1360P</p>
          <p><strong>ОЗУ:</strong> 16 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 13.3", 2880×1800, AMOLED, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.29 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">LG Gram 17</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-1360P</p>
          <p><strong>ОЗУ:</strong> 32 ГБ LPDDR5</p>
          <p><strong>Видеокарта:</strong> Intel Iris Xe</p>
          <p><strong>Экран:</strong> 17.0", 2560×1600, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.35 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">MacBook Pro 16 M3 Max</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Apple M3 Max</p>
          <p><strong>ОЗУ:</strong> 64 ГБ Unified</p>
          <p><strong>Видеокарта:</strong> M3 Max GPU (40 ГБ)</p>
          <p><strong>Экран:</strong> 16.2", 3456×2234, Mini-LED, 120 Гц</p>
          <p><strong>ОС:</strong> macOS</p>
          <p><strong>Вес:</strong> 2.14 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Alienware m18</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 9 7845HX</p>
          <p><strong>ОЗУ:</strong> 64 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 4090 (16 ГБ)</p>
          <p><strong>Экран:</strong> 18.0", 2560×1440, IPS, 165 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 4.14 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">ASUS Vivobook Pro 15</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 7 7735HS</p>
          <p><strong>ОЗУ:</strong> 16 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 3050 (4 ГБ)</p>
          <p><strong>Экран:</strong> 15.6", 2880×1620, OLED, 120 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.8 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Lenovo IdeaPad Slim 5</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> AMD Ryzen 7 7730U</p>
          <p><strong>ОЗУ:</strong> 16 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> AMD Radeon</p>
          <p><strong>Экран:</strong> 15.6", 1920×1080, IPS, 60 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.85 кг</p>
        </div>
      </div>
      <div class="product">
        <div class="product-header">Surface Laptop Studio</div>
        <div class="product-body">
          <p><strong>Процессор:</strong> Intel Core i7-12700H</p>
          <p><strong>ОЗУ:</strong> 32 ГБ DDR5</p>
          <p><strong>Видеокарта:</strong> RTX 3050 Ti (4 ГБ)</p>
          <p><strong>Экран:</strong> 14.4", 2400×1600, PixelSense Flow, 120 Гц</p>
          <p><strong>ОС:</strong> Windows 11</p>
          <p><strong>Вес:</strong> 1.8 кг</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Подвал -->
  <footer>
    <p>&copy; 2025 ООО "Kazakh IT". Все права защищены.</p>
    <p>Волгоград, Россия | Тел: +7 927 061-83-89</p>
  </footer>

</body>
</html>