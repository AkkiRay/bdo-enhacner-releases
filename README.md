# 📦 BDO Deborica Enhancer — Releases  

Все официальные сборки приложения:  
– Дифференциальный пакет (быстрый апдейт)  
– Полный инсталлятор (с нуля)  
– Конфиг авто-апдейта  
– Исходники для сборки  
All official app builds:  
– Diff package (quick patch)  
– Full installer (fresh install)  
– Auto-update config  
– Source code  

---

## 🚀 Последняя версия / Latest Release

| Версия / Version | Дата / Date       | 🔄 Diff-пакет / Diff Package                                                                                                             | 🛠 Full installer                                                                                                                     | 📄 latest.yml                                           |
|:-----------------|:------------------|:-------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------|
| **1.0.2**        | 2025-07-06        | [bdo-enhancer-monitor-1.0.2-x64.nsis.7z](https://github.com/AkkiRay/bdo-enhacner-releases/releases/download/v1.0.2/bdo-enhancer-monitor-1.0.2-x64.nsis.7z) — 110 MB | [install-bdo-enhancer-1.0.2.exe](https://github.com/AkkiRay/bdo-enhacner-releases/releases/download/v1.0.2/bdo-enhancer-monitor-web-setup-1.0.2.exe) — 679 KB | [latest.yml](https://github.com/AkkiRay/bdo-enhacner-releases/releases/download/v1.0.2/latest.yml) — 596 Bytes |

> **Примечание / Note:**  
> – Если вы уже используете предыдущую версию, запустите Diff-пакет для мгновенного обновления.  
> – Для чистой установки используйте Full installer.  
> – Авто-апдейт срабатывает при каждом запуске приложения.  
>  
> – If you have the previous version installed, run the Diff package for an instant patch.  
> – For a fresh setup, use the Full installer.  
> – In-app auto-update runs on every app launch.  

---

## 📥 Установка / Installation Guide

### 🆕 1. Новая установка / Fresh Install  
1. Скачайте **Full installer**:  
2. Запустите `.exe` и следуйте мастеру установки.  
3. Дождитесь окончания процесса: создадутся ярлыки и корневая папка.  
4. Запустите приложение через меню «Пуск» или ярлык на рабочем столе.  

1. Download the **Full installer**:  
2. Run the `.exe` and follow the setup wizard.  
3. Wait until installation completes: shortcuts and program folder will be created.  
4. Launch the app from Start Menu or desktop shortcut.  

### 🔄 2. Обновление вручную / Manual Update (Diff)  
1. Закройте запущенное приложение.  
2. Скачайте **Diff-пакет**:  
3. Распакуйте содержимое в папку установки (обычно `C:\Users\<You>\AppData\Local\Programs\BDO Deborica Enhancer`).  
4. Перезапустите приложение — новая версия применена.  

1. Close the running app.  
2. Download the **Diff package**:  
3. Extract its contents into the install directory (e.g. `C:\Users\<You>\AppData\Local\Programs\BDO Deborica Enhancer`).  
4. Relaunch the app — new version is applied.  

---

## 🔄 Авто-обновление / In-App Auto-Update

При каждом старте приложение автоматически:  
1. Загружает `latest.yml` из GitHub Releases.  
2. Сверяет локальную версию с удалённой.  
3. Если есть обновление — показывает сплэш-экран с:  
- прогресс-баром (%)  
- объёмом скачанного/итого (МБ)  
- скоростью (МБ/с) и ETA  
4. Скачивает Diff-пакет (`.7z`) и сам применяет обновление.  
5. Перезапускает приложение в актуальной версии.  

On every launch the app automatically:  
1. Fetches `latest.yml` from GitHub Releases.  
2. Compares local version with remote.  
3. If an update exists — shows a splash with:  
- progress bar (%)  
- downloaded/total size (MB)  
- speed (MB/s) & ETA  
4. Downloads the Diff package (`.7z`) and applies the update.  
5. Relaunches itself in the up-to-date version.  

---

## 📝 История изменений / Changelog

Полная история изменений в репозитории:  
➡️ [CHANGELOG.md](https://github.com/AkkiRay/bdo-enhacner-releases/blob/main/CHANGELOG.md)  

Full change log is maintained here:  
➡️ [CHANGELOG.md](https://github.com/AkkiRay/bdo-enhacner-releases/blob/main/CHANGELOG.md)  

---

## 🛠️ Решение проблем / Troubleshooting

| Симптом / Symptom                                 | Возможная причина / Cause                  | Решение / Solution                                               |
|:--------------------------------------------------|:-------------------------------------------|:-----------------------------------------------------------------|
| Сплэш сразу закрывается без загрузки / Splash closes immediately | нет интернета или GitHub Releases недоступен | Проверьте соединение; откройте [latest.yml](...) в браузере      |

---

## 📣 Обратная связь / Feedback

У вас есть идеи или вы нашли баг?  
➡️ Откройте [issue](https://github.com/AkkiRay/bdo-enhacner-releases/issues)  

Found a bug or got a feature request?  
➡️ Create an [issue](https://github.com/AkkiRay/bdo-enhacner-releases/issues)  

Спасибо за вклад!  
Thanks for contributing!
