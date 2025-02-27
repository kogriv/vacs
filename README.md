# vaczzz

Program for collecting and analyzing vacancies

## Проект VAC - Умный поиск и анализ вакансий

### Описание проекта
Проект VAC - это интеллектуальная система для автоматизации поиска работы, находящаяся в активной разработке.

### Цель проекта
Упростить поиск работы, предоставить пользователям возможность быстро и эффективно искать вакансии, а также предоставить дополнительные инструменты для анализа и оценки возможностей рынка труда.

### Доступ
В открытом доступе находится текущее описание проекта. Также здесь будут размещаться некоторые аналитические выкладки. Основной код находится в приватном репозитории.

### Текущий функционал
- ✅ Парсер вакансий с HeadHunter API
- ✅ Настраиваемые параметры поиска:
  - Поиск по городам
  - Поиск по ключевым словам 
  - Поиск похожих вакансий по резюме
- ✅ Автоматическая дедупликация данных
- ✅ Сохранение в PostgreSQL
- ✅ Гибкая конфигурация через файлы и переменные окружения

### План развития
1. **Текущий этап**: Парсер вакансий ✓
2. **ML-модуль**: Отбор релевантных вакансий
3. **Чат-бот**: Автоматизация откликов и коммуникации с работодателями

### Установка и запуск

#### Предварительные требования
- Python 3.8+
- PostgreSQL
- Токен HeadHunter API

#### Требуется настройка:
- Файл `data/vacs.txt` - список поисковых запросов
- Файл `data/cities.txt` - список городов
- `.env` файл с токеном HeadHunter API

```bash
python main.py
```

### Преимущества проекта
- 🎯 Интеллектуальный анализ релевантности вакансий
- ⚡ Экономия времени на рутинных задачах поиска работы
- 🔄 Автоматическое обновление базы вакансий
- 📊 Возможность масштабного анализа рынка труда
- 🛠 Модульная архитектура для простого расширения

### Значимость
Проект решает актуальную проблему эффективного поиска работы, сокращая время на:

- Мониторинг новых вакансий
- Анализ требований работодателей
- Отбор подходящих предложений
- Массовую рассылку откликов

### Перспективы
Развитие проекта направлено на создание полноценного AI-ассистента по поиску работы, способного:

- Самостоятельно анализировать рынок труда
- Выбирать наиболее подходящие вакансии
- Формировать персонализированные отклики
- Вести первичные переговоры с работодателями

