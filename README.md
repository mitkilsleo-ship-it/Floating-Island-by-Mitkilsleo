<div align="center">

# 🏝️ Floating Island By Mitkilsleo

**Интерактивный «Динамический остров» для Windows в стиле iOS с кастомизацией, музыкой и виджетами.**

[![[Release](📦)](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases)]
[![Platform]🪟 Windows 10 / 11)]
[![[.NET](🟣)](https://dotnet.microsoft.com)]

[Скачать последний релиз](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases) · [English Version](#-english)

</div>

> [!WARNING]
> **Alpha-версия:** Программа находится в активной разработке. Будем рады вашим отзывам и звёздам ⭐ в репозитории!

---

## ✨ Список возможностей Floating Island

### 🎵 Музыка и звук
* **Мини-плеер и главный плеер:** Компактный вид с живым эквалайзером и развёрнутая версия с обложкой, прогресс-баром и эффектом halftone blur.
* **Управление громкостью:** Встроенный плавно анимированный регулятор громкости.

### 🎧 Интеграция с Discord
* **Динамическая аватарка:** Появляется рядом с островком во время голосовой активности без сдвига интерфейса.
* **Индикация статусов:** Зелёное свечение при разговоре, приглушённый серый вид в молчании и красный контур при выключенном микрофоне.
* **Быстрый мут:** Переключение микрофона по клику на аватарку и настройка зон подсветки (только аватарка или весь остров).

### 📊 Системный мониторинг и сеть
* **Нагрузка ПК:** Визуальная индикация загрузки компонентов системы с прогресс-барами.
* **Подключения:** Мониторинг статуса Wi-Fi, Bluetooth, активных VPN и режима полёта.

### 📂 Файлы и уведомления
* **File Shelf (Полка):** Буфер для временного хранения и быстрого перетаскивания файлов.
* **Уведомления:** Автоматическое отслеживание и показ уведомлений о завершенных загрузках файлов.

### ⏱️ Утилиты, погода и действия
* **Быстрые действия:** Инструменты для создания скриншотов и записи экрана.
* **Время:** Таймеры, секундомеры, будильники и напоминания.
* **Погода:** Определение геолокации и поиск погоды по городам.

### 🎨 Кастомизация и интерфейс
* **Дизайн:** Модульная iOS-структура с переключением материалов (Стекло/Glass, Матовый/Matte, Дерево/Wood, Градиент/Gradient).
* **Эффекты:** Плавные переходы, кастомное свечение (Glow) и поддержка GIF-анимаций.
* **Управление:** Кнопки для скрытия островка и полного завершения работы программы.

---

## 🚀 Быстрый старт
1. Установите **[.NET](https://dotnet.microsoft.com)**.
2. Скачайте архив из раздела **[Releases](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases)** и распакуйте на Рабочий стол.
3. Запустите `build.bat`, подождите 15–30 секунд и откройте приложение из папки **`out`**.

---

## 🗑️ Удаление
Для версий новее Alpha v0.1 просто закройте программу через кнопку в приложении и удалите её папку. 

<details>
<summary><b>Команда для удаления устаревшей Alpha v0.1 (PowerShell от имени администратора)</b></summary>

```powershell
\(d = Get-CimInstance Win32_SystemDriver \vert{} Where-Object PathName -like '*FloatingIsland.sys*'\)d | Select Name, State, PathName
foreach (\(x in\)d) { sc.exe stop \(x.Name; sc.exe delete\)x.Name }
```
</details>

---

<div align="center" id="-english">

# 🏝️ Floating Island (English)

**An interactive iOS-style Dynamic Island for Windows with custom widgets, music controls, and Discord integration.**

</div>

## 🚀 Quick Start & Uninstallation
* Install **[.NET](https://dotnet.microsoft.com)**, download the release from [GitHub](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases), run `build.bat`, and launch from the `out` folder.
* For legacy Alpha v0.1 removal, use the PowerShell command from the Russian section above as Administrator.
