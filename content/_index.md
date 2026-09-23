+++
title = "Дальнобойный Программист"
draft = false
+++

<!-- РЯД 1: ДЛЯ БУДУЩИХ ВАЙБКОДЕРОВ -->
<div class="main-section-title">Для будущих вайбкодеров</div>
<div class="custom-grid grid-blue">

  <div class="custom-card">
    <div class="card-icon">🚀</div>
    <h3 class="card-title">Вайбкодер/H3>
    <p class="card-text">Задаешь вайб — ИИ пишет код. Как ставить задачи нейросетям так, чтобы получать рабочий софт с первого промпта.</p>
  </div>

  <div class="custom-card">
    <div class="card-icon">🏛️</div>
    <h3 class="card-title">Архитектура</h3>
    <p class="card-text">Связываем модули, базы данных и логику. Проектирование сложных отказоустойчивых систем без рутины.</p>
  </div>

  <div class="custom-card">
    <div class="card-icon">🧙‍♂️</div>
    <h3 class="card-title">Правда о вайбкодинге</h3>
    <p class="card-text">Как не поломать ноги на сложных проектах. Честный разбор ограничений ИИ без инфоцыганства и иллюзий.</p>
  </div>

  <div class="custom-card">
    <div class="card-icon">📂</div>
    <h3 class="card-title">Готовые проекты</h3>
    <p class="card-text">Боты, исходный код, детальные разборы архитектуры. Забирай готовые модули в свои проекты и повторяй.</p>
  </div>

</div>

## О чем этот сайт

Здесь я рассказываю, как стать разработчиком без унылого чтения тонны учебников и на практике показываю, какие серьезные продукты на этом можно строить.

**"Вайбкодер"** — человек, который задает нейросети направление, логику и архитектуру, а ИИ генерирует рутинный код. Я не трачу часы на поиск пропущенной точки с запятой — я знаю, как связать тяжелые модули между собой.

## Для бизнеса

Telegram-боты, которые намертво закрывают рутину: автоматический расчет объемов, фиксация дефектов, транспортная логистика, снабжение и интеграция сложных баз данных.

<!-- РЯД 2: ДЛЯ БИЗНЕСА -->
<div class="custom-grid grid-cyan">

  <div class="custom-card">
    <div class="card-icon">📐</div>
    <h3 class="card-title">Калькуляция объемов</h3>
    <p class="card-text">Автоматический расчет объемов материалов с учетом коэффициентов усадки, утряски и плотности по СНиП за секунды.</p>
  </div>

  <div class="custom-card">
    <div class="card-icon">📷</div>
    <h3 class="card-title">Фиксация дефектов</h3>
    <p class="card-text">Железобетонная фиксация нарушений на объекте с фото, геопривязкой и точным таймстампом. Исключает споры с подрядчиками.</p>
  </div>

  <div class="custom-card">
    <div class="card-icon">🚚</div>
    <h3 class="card-title">Транспорт и логистика</h3>
    <p class="card-text">Цифровое распределение заявок, контроль статусов снабжения объектов и автоматическое построение маршрутов без звонков.</p>
  </div>

  <div class="custom-card">
    <div class="card-icon">⛏️</div>
    <h3 class="card-title">Снабжение и майнинг</h3>
    <p class="card-text">Оперативный учет остатков на складах, автоматическое формирование заявок и координация поставок в едином интерфейсе.</p>
  </div>

</div>

<!-- БЛОК С КНОПКАМИ СВЯЗИ -->
<div class="buttons-container">
  <a href="https://t.me" target="_blank" class="btn btn-tg">
    <span>🌐</span> Мой Telegram
  </a>
  <a href="https://vc.ru" target="_blank" class="btn btn-vc">
    <span>📄</span> Блог на VC.ru
  </a>
</div>


<!-- ЕДИНЫЙ СТИЛЬНЫЙ CSS ДЛЯ СТРАНИЦЫ -->
<style>
.main-section-title {
  font-family: system-ui, -apple-system, sans-serif;
  color: #00d2ff;
  font-size: 20px;
  font-weight: bold;
  margin-top: 30px;
  margin-bottom: 15px;
}

.custom-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
  margin: 20px 0 40px 0;
  font-family: system-ui, -apple-system, sans-serif;
}

.custom-card {
  background: #1a1f2c; 
  border-radius: 12px;
  padding: 24px 20px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  text-align: left;
  min-height: 200px;
  transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

/* Настройки цветов для первого ряда (Вайбкодеры) */
.grid-blue .custom-card {
  border: 1px solid rgba(0, 212, 255, 0.15);
}
.grid-blue .custom-card:hover {
  border-color: rgba(0, 212, 255, 0.6);
  box-shadow: 0 8px 25px rgba(0, 212, 255, 0.15);
  transform: translateY(-5px);
}
.grid-blue .card-title {
  color: #00d2ff;
}

/* Настройки цветов для второго ряда (Бизнес) */
.grid-cyan .custom-card {
  border: 1px solid rgba(0, 212, 255, 0.15);
}
.grid-cyan .custom-card:hover {
  border-color: rgba(0, 212, 255, 0.7);
  box-shadow: 0 8px 25px rgba(0, 212, 255, 0.2);
  transform: translateY(-5px);
}
.grid-cyan .card-title {
  color: #ffffff;
}

.card-icon {
  font-size: 32px;
  margin-bottom: 12px;
  filter: drop-shadow(0 2px 4px rgba(0,0,0,0.5));
}

.card-title {
  font-size: 18px;
  font-weight: bold;
  line-height: 1.2;
  margin: 0 0 10px 0;
}

.card-text {
  color: #94a3b8;
  font-size: 14px;
  line-height: 1.4;
  margin: 0;
  opacity: 0.9;
}

/* Стили кнопок */
.buttons-container {
  display: flex;
  gap: 15px;
  margin-top: 25px;
  margin-bottom: 30px;
  flex-wrap: wrap;
  font-family: system-ui, -apple-system, sans-serif;
}

.btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  font-size: 15px;
  transition: all 0.2s ease;
}

.btn-tg {
  border: 1px solid #00d2ff;
  color: #00d2ff;
  background: rgba(0, 212, 255, 0.03);
}

.btn-tg:hover {
  background: #00d2ff;
  color: #111111;
  box-shadow: 0 0 15px rgba(0, 212, 255, 0.4);
}

.btn-vc {
  border: 1px solid #ff4d4d;
  color: #ff4d4d;
  background: rgba(255, 77, 77, 0.03);
}

.btn-vc:hover {
  background: #ff4d4d;
  color: #ffffff;
  box-shadow: 0 0 15px rgba(255, 77, 77, 0.4);
}
</style>