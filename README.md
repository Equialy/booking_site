# Book&Go - Система онлайн-записи

Простая и элегантная система онлайн-записи, созданная с использованием чистых HTML, CSS и JavaScript без фреймворков.



### Основные возможности

- 📅 **Онлайн-запись** - клиенты могут записаться через удобную форму
- 🎛️ **Панель управления** - просмотр и управление всеми записями
- 📊 **Статистика** - отображение общего количества записей
- 🗂️ **Категоризация** - разделение на предстоящие и прошедшие записи
- 💾 **Локальное хранение** - данные сохраняются в браузере
- 📱 **Адаптивный дизайн** - работает на всех устройствах

## 🛠️ Технологии

- **HTML5** - семантическая разметка
- **CSS3** - современные стили, Grid, Flexbox
- **JavaScript ES6+** - интерактивность и логика
- **LocalStorage** - хранение данных

## 📁 Структура проекта

```
book_and_go/
├── index.html          # Главная страница
├── booking.html        # Форма записи
├── success.html        # Страница подтверждения
├── dashboard.html      # Панель управления
├── styles.css          # Все стили проекта
├── script.js          # JavaScript логика
└── README.md          # Документация
```

## 🚀 Установка и запуск

### Способ 1: Простое открытие
1. Открыть `index.html` в любом современном браузере
2. Готово! 

### Способ 2: Локальный сервер (рекомендуется)

#### С Python:
```bash
python -m http.server 8000

Открыть http://localhost:8000
```




## 📖 Использование

### Создание записи
1. Перейдите на страницу "Запись" или нажмите "Записаться сейчас"
2. Заполните все обязательные поля формы
3. Выберите дату (не ранее сегодняшнего дня)
4. Выберите удобное время
5. Нажмите "Записаться"

### Управление записями
1. Откройте "Панель управления"
2. Просматривайте записи во вкладках "Предстоящие" и "Прошедшие"
3. Удаляйте ненужные записи кнопкой корзины
4. Создавайте новые записи кнопкой "Новая запись"

## 🎨 Особенности дизайна

- **Современный UI** - чистый и минималистичный интерфейс
- **Цветовая схема** - профессиональные синие оттенки
- **Типографика** - читаемые шрифты и правильная иерархия
- **Интерактивность** - плавные переходы и hover-эффекты
- **Иконки** - SVG иконки для лучшей производительности

## 💻 Техническая реализация

### HTML
- Семантические теги для лучшей доступности
- Валидная разметка

### CSS
- Flexbox и Grid для современной верстки
- CSS переменные для удобства поддержки
- Mobile-first подход
- Модульная организация стилей

### JavaScript
- ES6+ синтаксис
- Модульная архитектура с классами
- Работа с LocalStorage API
- Обработка событий и валидация форм

## 🔧 Основные компоненты

### Класс для работы с данными:
- Сохранение записей в LocalStorage
- Получение и фильтрация записей
- Генерация уникальных ID

### Система уведомлений:
- Показ сообщений об успехе/ошибке
- Автоматическое скрытие
- Анимированное появление

### Утилиты для работы с датами:
- Форматирование дат на русском языке
- Определение предстоящих записей

## 📱 Адаптивность

Проект полностью адаптивен и корректно отображается на:
- 📱 Мобильных устройствах (320px+)
- 📱 Планшетах (768px+)
- 💻 Десктопах (1024px+)
- 🖥️ Больших экранах (1200px+)

## 💻 Доступность

- Семантическая HTML разметка
- Контрастные цвета для лучшей читаемости
- Альтернативный текст для изображений



## 💻 Известные ограничения

- Данные хранятся только локально в браузере
- Нет серверной валидации

## 🤝 Вклад в проект

Предложения по улучшению приветствуются!

Если у вас есть вопросы по проекту или предложения по улучшению, буду рад обратной связи!




