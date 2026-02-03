# 🛒 Django Marketplace Engine
#README.md Был создан Chatgpt.com

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-4.2+-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

Современный и быстрый маркетплейс на Django. Полный цикл: от управления категориями в админке до красивой витрины товаров с адаптивным дизайном.

---

## ✨ Особенности
- **Fullstack-архитектура**: Логика Django + динамические шаблоны HTML.
- **No-Static Design**: Стили встроены в шаблоны (удобно для быстрой разработки без настройки STATIC_ROOT).
- **Bootstrap 5 UI**: Адаптивная сетка, современные карточки товаров и анимации.
- **ORM Power**: Сложные связи (User -> Seller, Category -> Products).
- **SEO-friendly**: Использование Slug для красивых URL категорий.

---

## 🛠 Технологический стек
* **Backend:** Python 3.9+, Django 4+
* **Frontend:** HTML5, CSS3 (Custom), Bootstrap 5 (CDN)
* **Database:** SQLite (по умолчанию)
* **Images:** Pillow (обработка изображений товаров)

---

## 🚀 Быстрый старт на MacBook

### 1. Клонирование и настройка окружения
```bash
# Создаем и активируем виртуальное окружение
python3 -m venv .venv
source .venv/bin/activate

# Устанавливаем зависимости
pip install django Pillow
