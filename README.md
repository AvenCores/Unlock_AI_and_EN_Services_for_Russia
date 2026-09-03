<div align="center">
    <a href="https://www.youtube.com/@avencores/" target="_blank">
      <img src="https://github.com/user-attachments/assets/338bcd74-e3c3-4700-87ab-7985058bd17e" alt="YouTube" height="40">
    </a>
    <a href="https://t.me/avencoresyt" target="_blank">
      <img src="https://github.com/user-attachments/assets/939f8beb-a49a-48cf-89b9-d610ee5c4b26" alt="Telegram" height="40">
    </a>
    <a href="https://vk.ru/avencoresreuploads" target="_blank">
      <img src="https://github.com/user-attachments/assets/dc109dda-9045-4a06-95a5-3399f0e21dc4" alt="VK" height="40">
    </a>
    <a href="https://dzen.ru/avencores" target="_blank">
      <img src="https://github.com/user-attachments/assets/bd55f5cf-963c-4eb8-9029-7b80c8c11411" alt="Dzen" height="40">
    </a>
</div>

![maxresdefault](https://github.com/user-attachments/assets/a7333079-3bd3-405e-9a9e-c1f63191c1cf)

<p align="center">
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia"><img src="https://img.shields.io/badge/shell-3670A0?style=for-the-badge&logo=shell&logoColor=ffdd54" alt="Shell"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge" alt="GPL-3.0 License"></a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/releases/latest"><img src="https://img.shields.io/github/v/release/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=for-the-badge" alt="Latest release"></a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/stargazers"><img src="https://img.shields.io/github/stars/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=for-the-badge" alt="GitHub stars"></a>
  <img src="https://img.shields.io/github/forks/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=for-the-badge" alt="GitHub forks">
  <a href="https://github.com/AvenCores/open-antigravity-patcher/watchers">
  <img src="https://img.shields.io/github/watchers/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=for-the-badge" alt="GitHub Watchers"></a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/releases"><img src="https://img.shields.io/github/downloads/AvenCores/Unlock_AI_and_EN_Services_for_Russia/total?style=for-the-badge" alt="Downloads"></a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/pulls"><img src="https://img.shields.io/github/issues-pr/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=for-the-badge" alt="GitHub pull requests"></a>
  <a href="https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/issues"><img src="https://img.shields.io/github/issues/AvenCores/Unlock_AI_and_EN_Services_for_Russia?style=for-the-badge" alt="GitHub issues"></a>
</p>

# Unlock AI & EN Services for Russia

> 🛡️ **Magisk/KernelSU-модуль, позволяющий обходить региональные блокировки зарубежных сервисов ИИ, соцсетей, игр и других ресурсов из России, а также блокирующий вредные сайты.**
>
> Под капотом — кастомизированный `/system/etc/hosts` из репозитория <a href="https://github.com/ImMALWARE/dns.malw.link">dns.malw.link</a> с ручной верификацией адресов, регулярными обновлениями и автоматической доставкой через встроенный механизм OTA.

---

## 📑 Содержание
1. [Возможности](#-возможности)
2. [Требования](#-требования)
3. [Установка](#-установка)
4. [Обновление](#-обновление)
5. [Поддерживаемые сервисы](#-поддерживаемые-сервисы)
6. [ЧаВо](#-чаво)
7. [Журнал изменений](#%EF%B8%8F-журнал-изменений)
8. [Лицензия](#-лицензия)
9. [Поддержать автора](#-поддержать-автора)

---

## 🚀 Возможности
* Разблокировка более 70 популярных AI-, медиа- и облачных сервисов.
* OTA-обновления модуля (см. `update.json`).
* Защита от вредоносных сайтов: скримеров и IP-логгеров.
* Для сервисов без отдельной сетевой блокировки РКН работает без VPN, прокси и сторонних приложений.

---

## ⚙️ Требования
* Android 8.0+
* **Magisk** v23.0+ **или** **KernelSU** v0.8.0+
* Отсутствие других модулей, которые изменяют файл `hosts` (например, AdGuard-based адблокеры).

---

## 📥 Установка
1. Скачайте последний релиз `Unlock_AI_and_EN_Services_for_Russia.VX.Y.Z.zip` из раздела [Releases](https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/releases/latest).
2. В Magisk/KernelSU нажмите «Установить из памяти» и укажите скачанный ZIP.
3. После успешной прошивки перезагрузите устройство, чтобы применить изменения.

> **Важно:** Если при установке возникает ошибка — сначала установите версию [v1.0.1](https://github.com/AvenCores/Unlock_AI_and_EN_Services_for_Russia/releases/tag/V1.0.1) и затем обновитесь до последней. _Некоторые прошивки (особенно с A-only разделами) могут конфликтовать с новым форматом ZIP._

---

## ♻️ Обновление
* Модуль проверяет наличие новой версии при каждом запуске Magisk/KernelSU-менеджера.
* При появлении апдейта вы увидите уведомление с предложением скачать и установить ZIP напрямую.
* Changelog автоматически подтягивается из [`changelog.md`](./changelog.md).

---

## 🌍 Поддерживаемые сервисы
Список формируется на основе содержимого [`system/etc/hosts`](./source/system/etc/hosts) и регулярно пополняется. Ниже перечислены основные пользовательские сервисы; помимо них в `hosts` также включены вспомогательные API, CDN и домены авторизации этих платформ.

> **Важно:** модуль не обходит прямые блокировки РКН на сетевом уровне. Если конкретный сервис заблокирован РКН по IP / SNI / TLS или иным способом, без дополнительных средств (VPN, прокси, zapret, byebyedpi и т.п.) он работать не будет.

### 📱 Социальные сети и медиа
* Instagram (включая CDN и E2EE чаты) • TikTok • Truth Social • Twitch • Patreon

### 🧠 ИИ и ассистенты
* **OpenAI:** ChatGPT, Sora, Operator, API, CDN (oaistatic, oaiusercontent)
* **Anthropic:** Claude (API, Console)
* **X.AI:** Grok
* **Google:** Gemini, AI Studio, Generative Language API, NotebookLM, Jules, Stitch, AI Test Kitchen
* **Microsoft:** Copilot, Bing (Sydney, Edge Services)
* **Разработка:** GitHub Copilot, JetBrains AI, Codeium (Windsurf), Trae.ai, Manus
* **Инструменты:** ElevenLabs (API, Reader), DeepL (API, Write, Voice)

### 🎮 Игры и гейминг
* **Supercell:** Clash Royale, Clash of Clans, Brawl Stars, Squad Busters, mo.co, Supercell ID / Store
* **Microsoft / Xbox:** Xbox Auth, Xbox Cloud Gaming (xGPU) • Microsoft Rewards
* **Другое:** Parsec (Cloud Gaming) • OpenBitTorrent (Tracker)

### 🎵 Музыка
* Spotify (включая API, Dealer, CDN) • Tidal • Deezer

### 🧩 Разработка и создание контента
* GitHub API • JetBrains (Datalore, Plugins, Downloads, Account) • Linear • Canva • Framer • Autodesk • NVIDIA Developer • Guided Hacking • Tria.ge (Malware Analysis)

### ☁️ Сервисы и веб-платформы
* Tailscale • Notion • Weather.com • Internet Archive • Qwant • Imgur • Intel • Dell • Broadcom • Elgato • Dyson • Rutor • ntc.party • OneTrust (Geolocation/Consent)

### ⌚️ Здоровье
* Fitbit (Google)

### 💳 Платежи и финтех
* Square / Squareup • Pump.fun

---

## 🚫 Блокировка угроз, рекламы и скама (Правила `0.0.0.0`)
Огромный массив доменов перенаправляется на `0.0.0.0` для защиты пользователя. Вот основные категории блокируемых угроз:

### 🛑 Рекламные сети, аналитика и трекеры
* **Мобильная и веб-аналитика:** Appsflyer, Adjust, Branch, Swrve, Amplitude, Mixpanel, CleverTap, Airship.
* **Рекламные биржи и сети:** Criteo, Taboola, Outbrain, AdColony, DoubleClick, Unity Ads, IronSource, Vungle.
* **Телеметрия:** Сборщики данных смарт-ТВ, браузеров и мобильных приложений.

### 🕵️ IP-логгеры и деанонимизаторы
* Сервисы для скрытого перехвата IP-адреса и сбора данных: `iplogger.*`, `grabify.*`, `blasze.tk`, `gyazo.*` и тысячи их зеркал.

### 💀 Скримеры и шок-контент
* Классические шок-сайты и треш-контент: `2girls1cup.ws`, `1man1jar.org`, `goatse.*`, `tubgirl.*`, `lemonparty.org`, `meatspin` и т.д.

### 💸 Массовый крипто-скам и фейковые ИИ-трейдеры
* **Фальшивые платформы:** Блокируются **сотни** доменов, маскирующихся под легальные инвестиции и ИИ-трейдинг.
* **Паттерны скама:** `immediate-*`, `bitcoin-*`, `quantum-*`, `yuan-*`, `oil-profit`, `trade-*`, `bit-*`, `crypto-*` (например, *Immediate Edge, Quantum AI, Yuan Pay Group, Bitcoin Code, Oil Zero*).

### 🎣 Фишинг и поддельные панели входа
* **Корпоративный фишинг:** Фейковые страницы авторизации Webmail, Zimbra, cPanel, Outlook.
* **Соцсети:** Клонированные страницы входа Facebook, Instagram, TikTok.
* **Мошеннические ссылки:** Поддельные уведомления о доставке (Colissimo, DHL), "проверках безопасности" и компрометации аккаунтов.

### 🛒 Скам-маркетплейсы и фейковые магазины
* **Платформы объявлений:** Фишинговые зеркала Vinted, OLX, Allegro, eBay.
* **Бронирования:** Фейковые копии Booking, Airbnb (ссылки на "верификацию" и "возврат средств").
* **Фейковые бренды:** Магазины-клон, продающие контрафакт или крадущие данные карт (PEPCO, Super-Pharm, Wittchen, Ochnik, Nike, Skechers, Jysk, Thursday Boots).

### 🏴‍☠️ Опасные пиратские стриминги
* Зараженные и фишинговые сайты "бесплатного" кино и сериалов: `zalukaj`, `cda-vod`, `filman`, `efilmy`, `vodplay`, `ekino`, `kinoman` и сотни связанных с ними поддоменов-сателлитов.

### 🎰 Онлайн-казино, ставки и фейковые "раздачи"
* Vulkan Vegas, Ice Casino, GGBet, National Casino и тысячи их партнерских "зеркал".
* Фейковые опросы, "выигрыши" iPhone/Samsung, генераторы кодов и сайты из серии "заработок в сети".

### 🦠 Вредоносное ПО (Malware) и Adware
* Фейковые антивирусы, "очистители реестра" (Registry Cleaners), пиратский софт с троянами, загрузчики майнеров (CoinHive и аналоги) и рекламное ПО (Adware).

> Полный список доменов смотрите в [`hosts`](./source/system/etc/hosts).

---

## ❓ ЧаВо
<details>
<summary>Почему некоторые сервисы всё ещё недоступны?</summary>

Вероятно, ваш DNS-сервер подменяет ответы. Смените его на публичный (Google: `8.8.8.8`, Cloudflare: `1.1.1.1`) или используйте DoH/DoT.

</details>

<details>
<summary>Работает ли модуль в приложениях, а не только в браузере?</summary>

Тестирование проводится в первую очередь на веб-версии сервисов. Нативные приложения могут использовать дополнительные проверки региона, поэтому 100% работоспособность не гарантируется.

</details>

<details>
<summary>Можно ли использовать модуль вместе с рекламными блокировщиками?</summary>

Приоритизируйте этот модуль: убедитесь, что ваше приложение-адблокер <u>не перезаписывает</u> `/system/etc/hosts` после перезагрузки.

</details>

---

## 🗒️ Журнал изменений
Последние изменения см. в [changelog.md](./changelog.md).

---

## 📜 Лицензия
Проект распространяется на условиях [GPL-3.0 License](./LICENSE).

---

# 💰 Поддержать автора
+ **SBER**: `2202 2050 1464 4675`
