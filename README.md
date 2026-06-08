# Тетрис / Tetris

> Классический тетрис с современными визуальными эффектами!

🇷🇺 Классический тетрис с современными визуальными эффектами — SRS-вращение, удержание фигуры, предпросмотр следующей, призрачная фигура, DAS, таблица рекордов и поддержка геймпада.

🇬🇧 Classic Tetris with modern visual effects — SRS rotation, hold piece, next piece preview, ghost piece, DAS, leaderboard, and gamepad support.

---

## 🎮 Как играть / How to Play

### ⌨️ Клавиатура / Keyboard

| Клавиша | Действие (RU) | Action (EN) |
|---------|---------------|-------------|
| ← → | Двигать влево/вправо | Move left/right |
| ↓ | Мягкий дроп (ускорить) | Soft drop |
| ↑ | Повернуть фигуру | Rotate piece |
| Пробел | Жёсткий дроп | Hard drop |
| C | Удержать фигуру | Hold piece |
| P / Esc | Пауза | Pause |

### 🎮 Геймпад / Gamepad

| Кнопка | Действие (RU) | Action (EN) |
|--------|---------------|-------------|
| D-pad ← → | Двигать влево/вправо | Move left/right |
| D-pad ↓ | Мягкий дроп | Soft drop |
| A | Повернуть фигуру | Rotate piece |
| B | Удержать фигуру | Hold piece |
| Start | Пауза | Pause |

### 📱 Мобильные устройства / Mobile

Управление осуществляется с помощью сенсорных жестов на игровом поле:
- **Свайп влево/вправо** — перемещение фигуры
- **Свайп вниз** — мягкий дроп
- **Тап** — повернуть фигуру
- **Свайп вверх** — жёсткий дроп

---

## ✨ Возможности / Features

- 🎨 **Современные визуальные эффекты** — стеклянные блоки с градиентами, бликами и свечением
- 🔄 **SRS (Super Rotation System)** — классическая система вращения с wall kicks
- 👻 **Призрачная фигура** — отображение места посадки фигуры
- 📦 **Удержание фигуры (Hold)** — возможность сохранить фигуру на потом
- 👁️ **Предпросмотр следующей фигуры** — заранее видна следующая фигура
- ⚡ **DAS (Delayed Auto Shift)** — плавное ускорение при удержании клавиши
- 🏆 **Таблица рекордов** — топ-10 результатов сохраняется в localStorage
- 🔊 **Звуковые эффекты** — синтезированные звуки через Web Audio API
- 🌐 **Двуязычный интерфейс** — русский / English
- 🎮 **Поддержка геймпада** — управление через Gamepad API
- 📱 **PWA** — установка на домашний экран, работа офлайн

---

## 🚀 Деплой на GitHub Pages / Deployment to GitHub Pages

### Шаг 1: Создайте репозиторий

```bash
# Создайте новый репозиторий на GitHub, например: tetris-pwa
# Клонируйте его
git clone https://github.com/YOUR_USERNAME/tetris-pwa.git
cd tetris-pwa
```

### Шаг 2: Скопируйте файлы

Скопируйте содержимое папки `pwa/tetris/` в корень репозитория:

```
tetris-pwa/
├── index.html
├── manifest.json
├── sw.js
├── icon-192.png
├── icon-512.png
└── README.md
```

### Шаг 3: Закоммитьте и отправьте

```bash
git add .
git commit -m "Initial Tetris PWA"
git push origin main
```

### Шаг 4: Включите GitHub Pages

1. Откройте репозиторий на GitHub
2. Перейдите в **Settings** → **Pages**
3. В **Source** выберите **Deploy from a branch**
4. Выберите ветку `main` и папку `/ (root)`
5. Нажмите **Save**

### Шаг 5: Готово! 🎉

Через пару минут ваше приложение будет доступно по адресу:
```
https://YOUR_USERNAME.github.io/tetris-pwa/
```

> **Примечание:** Если вы деплоите в подпапку (например, `https://username.github.io/project/`), убедитесь, что `start_url` в `manifest.json` и пути в `sw.js` корректны. Для корневого деплоя используйте `.` как `start_url`.

---

## 🛠 Технологии / Tech Stack

| Технология | Описание |
|------------|----------|
| **HTML5** | Семантическая разметка |
| **Canvas 2D** | Рендеринг игрового поля и фигур |
| **Vanilla JS** | Чистый JavaScript без зависимостей |
| **Web Audio API** | Синтезированные звуковые эффекты |
| **Gamepad API** | Поддержка контроллеров |
| **Service Worker** | Офлайн-работа и кэширование |
| **Web App Manifest** | Установка как PWA |

**Никаких зависимостей!** — ни npm, ни bundler, ни фреймворков. Просто откройте `index.html` в браузере.

---

## 📸 Скриншот / Screenshot

<!-- Скриншот будет добавлен позже / Screenshot to be added later -->
![Tetris Screenshot](./screenshot.png)

---

## 📄 Лицензия / License

MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
