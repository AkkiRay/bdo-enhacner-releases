# 📦 BDO Deborica Enhancer — Releases  

Все официальные сборки приложения: полный инсталлятор, дифференциальный пакет, конфиг авто-апдейта и исходники.  
All official application builds: full installer, differential package, auto-update config and source code.

---

## 🚀 Версия 1.0.2 / Version 1.0.2  
**Дата / Date:** 2025-07-06

| 📦 Тип / Type                  | Файл / File                                                                                                                                                                  | Размер / Size |
|:-------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------|
| 🔄 Дифференциальный пакет       | [bdo-enhancer-monitor-1.0.2-x64.nsis.7z](https://github.com/AkkiRay/bdo-enhacner-releases/releases/download/v1.0.2/bdo-enhancer-monitor-1.0.2-x64.nsis.7z)                     | 110 MB        |
| 🛠 Полный инсталлятор           | [install-bdo-enhancer-1.0.2.exe](https://github.com/AkkiRay/bdo-enhacner-releases/releases/download/v1.0.2/intall-bdo-enhancer-1.0.2.exe)                                        | 679 KB        |
| 📄 Конфигурация авто-апдейта    | [latest.yml](https://github.com/AkkiRay/bdo-enhacner-releases/releases/download/v1.0.2/latest.yml)                                                                              | 596 Bytes     |
| 📦 Исходники (zip)              | [Source code (zip)](https://github.com/AkkiRay/bdo-enhacner-releases/archive/refs/tags/v1.0.2.zip)                                                                              | —             |
| 📦 Исходники (tar.gz)           | [Source code (tar.gz)](https://github.com/AkkiRay/bdo-enhacner-releases/archive/refs/tags/v1.0.2.tar.gz)                                                                         | —             |

---

## 💾 Установка / Installation

1. **Новая установка / New install**  
   Скачайте и запустите полный инсталлятор и следуйте мастеру.  
   Download and run the full installer and follow the wizard.

2. **Обновление / Update**  
   - Запустите дифференциальный пакет для быстрого патча:  
     Run differential package for a quick patch:  
     ```bash
     bdo-enhancer-monitor-1.0.2-x64.nsis.7z
     ```  
   - **или** дождитесь авто-апдейта внутри приложения.  
     or wait for the in-app auto-update.

3. При первом запуске приложение само проверит `latest.yml` и обновится, если вышла новая версия.  
   On first run the app will check `latest.yml` and auto-update if a newer version is available.

---

## 🔄 Авто-обновление / Auto-Update

При каждом запуске приложение:
1. Скачивает и проверяет `latest.yml`.  
   Downloads and checks `latest.yml`.
2. Если есть новая версия — показывает сплэш со спид-метрикой и ETA, скачивает дифференциальный пакет.  
   If a new version exists — shows splash with speed & ETA, downloads the diff package.
3. Применяет обновление и **автоматически перезапускается**.  
   Applies the update and **auto-relaunches**.

---

## 📝 История изменений / Changelog

Полный список изменений в [CHANGELOG.md](https://github.com/AkkiRay/bdo-enhacner-releases/blob/main/CHANGELOG.md).  
See full change log at [CHANGELOG.md](https://github.com/AkkiRay/bdo-enhacner-releases/blob/main/CHANGELOG.md).

---

## 📣 Обратная связь / Feedback

Нашли баг или хотите предложить фичу? Создайте [issue](https://github.com/AkkiRay/bdo-enhacner-releases/issues).  
Found a bug or have a feature request? Open an [issue](https://github.com/AkkiRay/bdo-enhacner-releases/issues).

Спасибо за вклад в развитие!  
Thanks for helping improve BDO Deborica Enhancer!
