# 📰 NewsNow

NewsNow — это современное новостное iOS-приложение, написанное на SwiftUI с использованием архитектуры MVVM. Приложение загружает новости с помощью [NewsAPI.org](https://newsapi.org), позволяет пользователю переключаться между категориями, добавлять статьи в избранное и просматривать их в отдельной вкладке. Интерфейс адаптирован под светлую и тёмную тему, а также содержит анимации и кастомные элементы управления.

<p float="left">
  <img src="https://github.com/user-attachments/assets/411de79f-23f8-4bcd-b289-716b9b8dd3fe" width="30%" />
</p>

---

## 🔧 Технологии

- SwiftUI
- MVVM
- AsyncImage
- UserDefaults
- NavigationView, TabView
- Toolbar + Sheet
- NewsAPI (собственный API-ключ)

---

## ✨ Функции

- 🔄 Загрузка новостей по категориям (Technology, Business, Health и др.)
- ⭐️ Добавление и удаление избранных новостей
- 💾 Сохранение избранных статей между сессиями через `UserDefaults`
- 🎨 Кастомный выбор категории через `sheet` с тёмным фоном
- 🌓 Поддержка тёмной и светлой темы
- ⚡️ Анимации появления карточек на обоих экранах
- 🔁 Pull-to-refresh
- 📱 Полная адаптация под разные экраны

---

## 📲 Скриншоты

<p float="left">
  <img src="https://github.com/user-attachments/assets/bd7a817c-29b2-49f2-afa4-e41c8a7d4492" width="30%" />
  <img src="https://github.com/user-attachments/assets/75887f31-0c8d-402d-9d2f-a6a7ec4ec72a" width="30%" />
  <img src="https://github.com/user-attachments/assets/b30a9abf-58a7-45b3-ba63-2d56d9b1d17f" width="30%" />
</p>

---

## 🚀 Как запустить

1. Получите API-ключ на [newsapi.org](https://newsapi.org/)
2. В файле `NewsViewModel.swift` замените ключ:

```swift
private let apiKey = "ВСТАВЬТЕ_СЮДА_СВОЙ_API_КЛЮЧ"
