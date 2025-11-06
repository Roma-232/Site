---
marp: true
theme: gaia
class:
  - lead
  - invert
style: |
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700;900&display=swap');
  
  section {
    font-family: 'Montserrat', sans-serif;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    position: relative;
    overflow: hidden;
  }
  
  section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: 
      radial-gradient(circle at 20% 80%, rgba(120, 119, 198, 0.3) 0%, transparent 50%),
      radial-gradient(circle at 80% 20%, rgba(255, 119, 198, 0.2) 0%, transparent 50%),
      radial-gradient(circle at 40% 40%, rgba(120, 219, 255, 0.15) 0%, transparent 50%);
    animation: float 20s infinite linear;
    z-index: -1;
  }
  
  h1, h2, h3 {
    font-weight: 900;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    animation: fadeInDown 1s ease-out;
  }
  
  h1 {
    font-size: 4rem;
    background: linear-gradient(45deg, #ff6b6b, #feca57, #48dbfb, #ff9ff3);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: gradientShift 3s infinite alternate;
  }
  
  h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
  }
  
  h3 {
    font-size: 1.8rem;
    color: #feca57;
  }
  
  ul {
    text-align: left;
    margin: 2rem auto;
    max-width: 600px;
  }
  
  li {
    font-size: 1.3rem;
    margin: 1rem 0;
    padding: 1rem;
    background: rgba(255,255,255,0.1);
    border-radius: 10px;
    backdrop-filter: blur(10px);
    border-left: 4px solid #48dbfb;
    animation: slideInLeft 0.8s ease-out;
    transition: transform 0.3s ease;
  }
  
  li:hover {
    transform: translateX(10px);
    background: rgba(255,255,255,0.2);
  }
  
  .btn {
    display: inline-block;
    background: linear-gradient(45deg, #ff6b6b, #feca57);
    color: white;
    padding: 15px 30px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2rem;
    margin: 1rem;
    box-shadow: 0 8px 25px rgba(255, 107, 107, 0.4);
    transition: all 0.3s ease;
    animation: pulse 2s infinite;
  }
  
  .btn:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 35px rgba(255, 107, 107, 0.6);
  }
  
  .price {
    font-size: 2rem;
    font-weight: bold;
    color: #feca57;
    animation: bounce 2s infinite;
  }
  
  .service-card {
    background: rgba(255,255,255,0.1);
    padding: 2rem;
    border-radius: 20px;
    margin: 2rem 0;
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.2);
    animation: fadeInUp 1s ease-out;
    transition: transform 0.3s ease;
  }
  
  .service-card:hover {
    transform: translateY(-10px);
    background: rgba(255,255,255,0.15);
  }
  
  .contact-item {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1rem;
    margin: 1rem 0;
    font-size: 1.3rem;
    animation: fadeIn 1s ease-out;
  }
  
  .emoji {
    font-size: 2rem;
    animation: bounce 2s infinite;
  }
  
  @keyframes float {
    0%, 100% { transform: translateY(0px) rotate(0deg); }
    50% { transform: translateY(-20px) rotate(180deg); }
  }
  
  @keyframes fadeInDown {
    from {
      opacity: 0;
      transform: translateY(-50px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(50px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  @keyframes slideInLeft {
    from {
      opacity: 0;
      transform: translateX(-50px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  @keyframes pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
  }
  
  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
    40% { transform: translateY(-10px); }
    60% { transform: translateY(-5px); }
  }
  
  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    100% { background-position: 100% 50%; }
  }
  
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }
  
  .footer {
    margin-top: 3rem;
    font-size: 0.9rem;
    opacity: 0.8;
  }
---

# SiteUp
## Создание сайтов

![bg](https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80)

---

## Навигация

<ul>
<li>🏠 **Главная**</li>
<li>⭐ **Преимущества**</li>
<li>🛠️ **Услуги**</li>
<li>👥 **О нас**</li>
<li>📞 **Контакты**</li>
</ul>

---

## Главный экран

# СОЗДАНИЕ САЙТОВ

**Ваш сайт — визитная карточка вашего бизнеса, отражение вашей индивидуальности и профессионального подхода.**

**Мы создаем уникальные веб-проекты, способные привлечь клиентов, подчеркнуть ваш бренд и эффективно решать бизнес-задачи.**

[Обсудить проект](z1(1).html){.btn}

---

## Что вы получите, обратившись к нам?

<ul>
<li>💎 **Уникальное предложение**<br>Отличающееся от конкурентов благодаря оригинальному дизайну и продуманному функционалу</li>

<li>⚡ **Быстрая загрузка**<br>И удобный интерфейс, гарантирующий высокую посещаемость и лояльность аудитории</li>

<li>📱 **Адаптивность**<br>Оптимизация под любые устройства и браузеры, адаптация под SEO-требования</li>
</ul>

---

## Преимущества (продолжение)

<ul>
<li>🎧 **Поддержка**<br>Сопровождение на всех этапах реализации проекта и после его запуска</li>

<li>📈 **Увеличение продаж**<br>Привлечение клиентов через поисковые системы и увеличение конверсии</li>

<li>🏅 **Повышение узнаваемости**<br>Формирование профессионального имиджа и демонстрация экспертности</li>
</ul>

---

## Наши услуги

### 🎯 Лендинг
<div class="price">от 25000₽</div>

<div class="service-card">
**Landing page (лендинг)** — страница для конкретных рекламных кампаний, позволяющая фокусировать внимание пользователей на одном продукте или услуге. Такой ресурс идеально подойдет для стартапа, нового товара или события.

[Оставить заявку](z11(1).html){.btn}
</div>

---

### 💼 Сайт-визитка
<div class="price">от 10000₽</div>

<div class="service-card">
**Сайт-визитка** — лёгкое и доступное представление компании в Интернете, включающее контактные данные, описание продуктов и портфолио выполненных работ. Подходит небольшим фирмам и частным специалистам.

[Оставить заявку](z111(1).html){.btn}
</div>

---

### 🏢 Корпоративный сайт
<div class="price">от 40000₽</div>

<div class="service-card">
**Корпоративный сайт** — полнофункциональная площадка для крупных организаций, предоставляющая подробную информацию о продуктах, услугах, новостях и событиях компании. Может включать обширный каталог продукции, блог, форму регистрации и многое другое.

[Оставить заявку](z1111(1).html){.btn}
</div>

---

## О Нас

<div class="service-card">
**Наша студия** — это профессиональная команда разработчиков, дизайнеров и маркетологов, объединившихся ради одной важной миссии: создавать современные и эффективные сайты, которые помогают развивать ваш бизнес.

**Мы знаем**, что сайт — это не просто набор страниц и картинок, а мощный инструмент для построения отношений с аудиторией, расширения клиентской базы и увеличения дохода.

[Обсудить проект](z1(1).html){.btn}
</div>

---

## Контакты

<div class="contact-item">
<span class="emoji">📞</span> **Телефон:** +7 962 782 20 51
</div>

<div class="contact-item">
<span class="emoji">✉️</span> **Email:** d89627822051@mail.ru
</div>

<div class="contact-item">
<span class="emoji">📱</span> **Телеграмм:** [@websitetomsk](https://t.me/websitetomsk)
</div>

<div class="contact-item">
<span class="emoji">👥</span> **VK:** [vk.com/id549383607](https://vk.com/id549383607)
</div>

---

<div class="footer">
**© 2025 SiteUp. Все права защищены.**

- [Политика конфиденциальности](policy.html)
- [Согласие на обработку персональных данных](pers.html)
</div>
