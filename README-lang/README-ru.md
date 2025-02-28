<h1 align="center">
⚡️AI Short
</h1>
<p align="center">
    <a href="/README-en.md">English</a> | <a href="/README.md">中文</a> |
<a href="./README-es.md">Español</a> |
<a href="./README-ja.md">日本語</a> |
<a href="./README-ko.md">한국어</a> |
<a href="./README-fr.md">Français</a> |
<a href="./README-de.md">Deutsch</a> |
<a href="./README-it.md">Italiano</a> |
Русский |
<a href="./README-pt.md">Português</a> |
<a href="./README-ar.md">العربية</a> |
<a href="./README-hi.md">हिन्दी</a> |
<a href="./README-bn.md">বাংলা</a>
</p>
<p align="center">
    <em>ChatGPT Shortcut, Maximize your Efficiency and Productivity</em>
</p>

## Почему использовать AiShort?

AiShort предоставляет сжатый и простой в использовании список инструкций AI. Даже без понимания подсказок, вы легко найдете подходящие для различных сценариев подсказки, фильтруя и искать, тем самым повышая свою продуктивность.

🚀 **Подсказки в один клик**: С помощью одного клика вы можете получить множество подсказок, тщательно отобранных экспертами. Отправьте их в AI языковые модели, например, ChatGPT, и вы получите ожидаемый вывод.

💻 **Повышение продуктивности**: Используя оптимизированные подсказки, вы можете получить более точную и практичную обратную связь, тем самым эффективно улучшая вашу работоспособность.

🌍 **Оптимизация для неанглоязычных языков**: Мы предлагаем переводы английских подсказок на 12 главных мировых языков и поддерживаем ответы по умолчанию на вашем родном языке, что удобно для носителей неанглийских языков для понимания и использования.

💾 **Сохранить подсказки**: Удобно собирать, редактировать и управлять своими любимыми подсказками для будущего использования.

🌐 **Поделиться подсказками**: Поделитесь своими любимыми подсказками, сотрудничайте с другими и вдохновляйте больше идей.

🗳️ **Система голосования сообщества**: Подобно Product Hunt или Reddit, платформа управляется сообществом. Лучшие подсказки будут выдвинуты на главную страницу.

📦 **Готов к использованию**: Просто посетите https://www.aishort.top/ru/ для начала использования.

Источники подсказок AiShort включают выборки из интернета, общие поделки сообщества, и [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts). Мы будем регулярно обновляться, чтобы предоставить вам новые подсказки и вдохновение. Чтобы понять, как использовать AiShort, пожалуйста, обратитесь к [руководству пользователя](https://www.aishort.top/ru/docs/guides/getting-started).

Приглашаем вас присоединиться к нашему сообществу Discord для обмена идеями и отзывами.

<a href="https://discord.gg/PZTQfJ4GjX">
   <img src="https://img.shields.io/discord/1048780149899939881?color=%2385c8c8&label=Discord&logo=discord&style=for-the-badge" alt="чат в Discord" />
</a>

## Расширение браузера

Расширение браузера AiShort (ChatGPT Shortcut) поддерживает Chrome и Edge с функциональностью, согласующейся с веб-версией и регулярно обновляемой. Расширение может быть автоматически активировано при загрузке страницы ChatGPT, или вы можете активировать окно расширения, нажав горячую клавишу `Alt+Shift+S`.

<a href="https://chrome.google.com/webstore/detail/chatgpt-shortcut/blcgeoojgdpodnmnhfpohphdhfncblnj">
  <img src="https://img.newzone.top/2023-06-05-12-28-49.png?imageMogr2/format/webp"  alt="Chrome" valign="middle" /></a>

<a href="https://microsoftedge.microsoft.com/addons/detail/chatgpt-shortcut/hnggpalhfjmdhhmgfjpmhlfilnbmjoin">
  <img src="https://img.newzone.top/2023-06-05-12-26-20.png?imageMogr2/format/webp" alt="Edge" valign="middle" /></a>

## Развертывание

### Развертывание с помощью Vercel

[![Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Frockbenben%2FChatGPT-Shortcut%2Ftree%2Fgh-pages)

### Установка

```shell
# Установка
yarn

# Локальная разработка
yarn start

# Сборка: Эта команда генерирует статический контент в директорию `build`
yarn build
```

## Синхронизация обновлений

Если вы развернули свой собственный проект на Vercel одним щелчком, вам может понадобиться решить проблему постоянных обновлений. Это связано с тем, что Vercel по умолчанию создает новый проект для вас, а не клонирует текущий проект, что мешает корректному обнаружению обновлений. Рекомендуется следовать следующим шагам для повторного развертывания:

1. Удалите предыдущий репозиторий.
2. Используйте кнопку "fork" (клонирование) в правом верхнем углу страницы, чтобы клонировать текущий проект.
3. На странице [Vercel New Project](https://vercel.com/new) выберите недавно клонированный проект в разделе Import Git Repository и продолжайте развертывание.

### Автоматические обновления

> В случае возникновения ошибки при выполнении Upstream Sync, выполните вручную одну синхронизацию форка.

После клонирования проекта из-за ограничений GitHub необходимо вручную включить Workflows на странице Actions вашего форка и активировать действие Upstream Sync. После активации обновления будут автоматически выполняться ежедневно.

![Автоматические обновления](https://img.newzone.top/2023-05-19-11-57-59.png?imageMogr2/format/webp)

![Включение автоматических обновлений](https://img.newzone.top/2023-05-19-11-59-26.png?imageMogr2/format/webp)

### Ручные обновления

Если

 вы хотите выполнить ручное обновление немедленно, вы можете обратиться к [документации GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork), чтобы узнать, как синхронизировать клонированный проект с исходным кодом.

Не стесняйтесь поддержать этот проект, поставив звезду или подписавшись на него, или следите за автором, чтобы быть в курсе своевременных уведомлений о новых функциональных обновлениях.
