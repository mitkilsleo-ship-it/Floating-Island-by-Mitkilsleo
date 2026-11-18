<div align="center">

# 🏝️ Floating Island By Mitkilsleo

**Интерактивный «Динамический остров» для Windows в стиле iOS с кастомизацией, музыкой и виджетами.**

[![Release](https://shields.io)](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases)
[![Platform](https://shields.io)](https://github.com)
[![.NET](https://shields.io)](https://dotnet.microsoft.com)

[Скачать последний релиз](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases) · [English Version](#-english)

</div>

> [!WARNING]
> **Alpha-версия:** Программа находится в активной разработке. Будем рады вашим отзывам и звёздам ⭐ в репозитории!

---

## ✨ Основные возможности
* 🎵 **Музыка и Discord:** Мини-плеер с эквалайзером и интеграция с Discord (аватар, статус голоса, мут).
* 📂 **Инструменты и мониторинг:** Полка для файлов (Shelf), системный мониторинг (Wi-Fi, VPN, батарея), таймеры, погода и скриншоты.
* 🎨 **Кастомизация:** Темы Glass, Matte, Wood и градиенты.

---

## 🚀 Быстрый старт
1. Установите **[.NET](https://dotnet.microsoft.com)**.
2. Скачайте архив из раздела **[Releases](https://github.com/mitkilsleo-ship-it/Floating-Island-by-Mitkilsleo/releases)** и распакуйте на Рабочий стол.
3. Запустите `build.bat`, подождите 15–30 секунд и откройте приложение из папки **`out`**.

---

## 🗑️ Удаление
Для версий новее Alpha v0.1 просто закройте программу и удалите её папку. 

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
