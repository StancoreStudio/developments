<div align="center">

# Разработки Stancore

**Каталог продуктов Stancore Studio** — отдельный репозиторий-витрина.

Сюда вынесены разработки студии, чтобы профиль организации оставался манифестом, а линейка продуктов жила в одном месте.

[![Org](https://img.shields.io/badge/Org-StancoreStudio-111827?style=for-the-badge&logo=github)](https://github.com/StancoreStudio)
[![Telegram](https://img.shields.io/badge/Telegram-TheStancore-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/TheStancore)
[![Discord](https://img.shields.io/badge/Discord-LetsWorld-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/letsworld)

</div>

---

## Зачем этот репозиторий

| Задача | Решение |
| --- | --- |
| Не смешивать манифест студии и карточки продуктов | Профиль оргa — в `.github`, продукты — здесь |
| Быстро понять, чем студия занимается в коде | Две флагманские линейки ниже |
| Дать единую точку входа контрибьюторам | Ссылки, статус, стек, куда слать issue |

Это **индекс**, а не монорепозиторий с исходниками. Исходный код — в репозиториях продуктов.

---

## Флагманы

### 1. Monolith

<a href="https://github.com/StancoreStudio/Monolith">
  <img src="https://img.shields.io/badge/Monolith-platform%20core-7C3AED?style=for-the-badge&logo=github&logoColor=white" alt="Monolith"/>
</a>

**Слой:** ядро / платформа  
**Репозиторий:** [StancoreStudio/Monolith](https://github.com/StancoreStudio/Monolith)  
**Статус:** в активной разработке  

**Monolith** — фундамент экосистемы Stancore. Платформа, на которой собираются сервисы студии: общие контракты, модули, жизненный цикл приложений, единые правила качества.

Задачи продукта:

- дать проектам студии **один** технический каркас вместо зоопарка самописных «ядер»;
- держать границы модулей явными: данные, домен, интеграции;
- масштабировать нагрузку без переписывания всего стека «с нуля»;
- быть местом, куда складываются внутренние стандарты (логирование, конфиги, ошибки, API).

Кому смотреть репозиторий: бэкенд, инфраструктура, архитектура сервисов.

---

### 2. AnchorJS

<a href="https://github.com/StancoreStudio/AnchorJS">
  <img src="https://img.shields.io/badge/AnchorJS-javascript%20dx-06B6D4?style=for-the-badge&logo=javascript&logoColor=white" alt="AnchorJS"/>
</a>

**Слой:** JavaScript / DX / клиент  
**Репозиторий:** [StancoreStudio/AnchorJS](https://github.com/StancoreStudio/AnchorJS)  
**Статус:** в активной разработке  

**AnchorJS** — JavaScript-библиотека Stancore. Клиентский слой экосистемы: якоря и навигация по контенту, удобство документации и UI, API, которое можно подключить в веб-инструменты студии.

Задачи продукта:

- ускорить сборку документации и интерфейсов без тяжёлого фреймворка «на каждый чих»;
- дать предсказуемый, маленький API;
- стыковаться с продуктами на Monolith (админки, справка, публичные страницы);
- держать DX на уровне «подключил — работает».

Кому смотреть репозиторий: фронтенд, документация, дизайн-системы, веб-инструменты.

---

## Сводка

| Продукт | Репозиторий | Слой | Для кого |
| --- | --- | --- | --- |
| **Monolith** | [Monolith](https://github.com/StancoreStudio/Monolith) | Платформа | Сервисы, ядро, инфра |
| **AnchorJS** | [AnchorJS](https://github.com/StancoreStudio/AnchorJS) | JavaScript | Клиент, DX, docs/UI |

```text
Stancore Studio
├── developments     ← вы здесь (каталог)
├── Monolith         ← ядро
└── AnchorJS         ← JS-слой
```

---

## Связанные контуры (не этот репозиторий)

Игровое и медиа-направления живут рядом с кодом, но не подменяют его:

| Направление | Где |
| --- | --- |
| LetsWorld (Minecraft) | [letsworld.ru](https://www.letsworld.ru) · `mc.letsworld.ru` · [Discord](https://discord.gg/letsworld) · [бот](https://t.me/letsworldbot) |
| Канал студии | [t.me/TheStancore](https://t.me/TheStancore) |
| AtomAI | исследовательский контур, технический перерыв |

---

## Как контрибьютить

1. Выбери продукт: **Monolith** или **AnchorJS**.
2. Прочитай README этого репозитория.
3. Открой issue с контекстом (что сломано / что предлагаешь) или PR с узким диффом.
4. Не смешивай правки ядра и клиентской библиотеки в одном PR.

Вопросы без кода — в [Telegram-канал](https://t.me/TheStancore). Баги по игре LetsWorld — в Discord проекта, не сюда.

---

## Лицензии

Лицензия указывается **в репозитории продукта**. Этот каталог сам по себе — документация витрины.

---

<div align="center">

[Организация](https://github.com/StancoreStudio) · [Monolith](https://github.com/StancoreStudio/Monolith) · [AnchorJS](https://github.com/StancoreStudio/AnchorJS) · [Telegram](https://t.me/TheStancore)

</div>
