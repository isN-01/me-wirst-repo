<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>README.md — Превью (HTML-рендер)</title>
  <style>
    :root {
      --bg-color: #0d1117;
      --card-bg: #161b22;
      --border-color: #30363d;
      --text-color: #c9d1d9;
      --heading-color: #f0f6fc;
      --link-color: #58a6ff;
      --code-bg: #161b22;
      --table-row-alt: #161b22;
      --alert-note: #1f6feb;
      --alert-tip: #238636;
      --alert-warning: #9e6a03;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif;
      font-size: 16px;
      line-height: 1.6;
      padding: 40px 20px;
    }

    .markdown-body {
      max-width: 880px;
      margin: 0 auto;
      background-color: #0d1117;
      padding: 32px;
      border: 1px solid var(--border-color);
      border-radius: 8px;
    }

    p {
      margin-top: 0;
      margin-bottom: 16px;
    }

    h1, h2, h3 {
      color: var(--heading-color);
      font-weight: 600;
      line-height: 1.25;
      margin-top: 24px;
      margin-bottom: 16px;
    }

    h1 {
      font-size: 2rem;
      border-bottom: 1px solid var(--border-color);
      padding-bottom: 8px;
    }

    h2 {
      font-size: 1.5rem;
      border-bottom: 1px solid var(--border-color);
      padding-bottom: 6px;
    }

    h3 {
      font-size: 1.2rem;
    }

    a {
      color: var(--link-color);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    hr {
      height: 2px;
      background-color: var(--border-color);
      border: 0;
      margin: 24px 0;
    }

    ul {
      padding-left: 2em;
      margin-bottom: 16px;
    }

    li {
      margin-top: 4px;
    }

    li.task-list-item {
      list-style-type: none;
      margin-left: -1.5em;
    }

    input[type="checkbox"] {
      margin-right: 8px;
      vertical-align: middle;
    }

    code {
      font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
      background-color: rgba(110, 118, 129, 0.4);
      padding: 0.2em 0.4em;
      border-radius: 6px;
      font-size: 85%;
      color: #e6edf3;
    }

    pre {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 6px;
      padding: 16px;
      overflow-x: auto;
      margin-bottom: 16px;
    }

    pre code {
      background-color: transparent;
      padding: 0;
      font-size: 85%;
      color: #e6edf3;
      display: block;
      line-height: 1.45;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 16px;
      display: block;
      overflow-x: auto;
    }

    th, td {
      border: 1px solid var(--border-color);
      padding: 8px 14px;
    }

    th {
      background-color: var(--card-bg);
      font-weight: 600;
      color: var(--heading-color);
    }

    tr:nth-child(2n) {
      background-color: var(--table-row-alt);
    }

    .callout {
      border-left: 4px solid;
      padding: 12px 16px;
      margin-bottom: 16px;
      border-radius: 0 6px 6px 0;
      font-size: 0.95rem;
    }

    .callout-title {
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 6px;
    }

    .callout-note {
      border-color: var(--alert-note);
      background-color: rgba(31, 111, 235, 0.12);
    }
    .callout-note .callout-title { color: #58a6ff; }

    .callout-tip {
      border-color: var(--alert-tip);
      background-color: rgba(35, 134, 54, 0.12);
    }
    .callout-tip .callout-title { color: #3fb950; }

    .callout-warning {
      border-color: var(--alert-warning);
      background-color: rgba(158, 106, 3, 0.15);
    }
    .callout-warning .callout-title { color: #d29922; }

    kbd {
      display: inline-block;
      padding: 3px 6px;
      font-family: ui-monospace, monospace;
      font-size: 11px;
      line-height: 10px;
      color: #c9d1d9;
      vertical-align: middle;
      background-color: #161b22;
      border: 1px solid #30363d;
      border-radius: 6px;
      box-shadow: inset 0 -1px 0 #21262d;
    }

    details {
      border: 1px solid var(--border-color);
      border-radius: 6px;
      padding: 12px;
      margin-bottom: 16px;
      background: var(--card-bg);
      cursor: pointer;
    }

    details summary {
      color: var(--link-color);
      font-weight: 500;
    }

    details pre {
      margin-top: 12px;
      margin-bottom: 0;
    }

    .footnotes {
      font-size: 0.85rem;
      border-top: 1px solid var(--border-color);
      padding-top: 16px;
      margin-top: 32px;
      color: #8b949e;
    }
  </style>
</head>
<body>

<div class="markdown-body">

  <h1 id="начинающий-программист">Начинающий программист <code>Junior Developer</code></h1>

  <p><em>Выпускник 11 классов. Владею только школьной программой по информатике, но хочу развиваться в веб-разработке и программировании.</em></p>

  <hr>

  <h2 id="оглавление">Оглавление</h2>
  <ul>
    <li><a href="#обо-мне">Обо мне</a></li>
    <li><a href="#технологический-стек">Технологический стек</a></li>
    <li><a href="#цели-и-план-обучения">Цели и план обучения</a></li>
    <li><a href="#мой-рабочий-инструментарий">Мой рабочий инструментарий</a></li>
    <li><a href="#системная-конфигурация">Системная конфигурация</a></li>
    <li><a href="#контакты-для-связи">Контакты для связи</a></li>
  </ul>

  <hr>

  <h2 id="обо-мне">Обо мне</h2>
  <p>Привет! Я закончил <strong>11 классов</strong> и пока знаю только <strong>школьную программу</strong> по информатике. Сейчас мой фокус — переход от <del>простых задач из учебника</del> к реальной разработке: командной строке, системам контроля версий Git<sup><a href="#fn1" id="ref1">[1]</a></sup> и написанию своего первого кода.</p>

  <div class="callout callout-note">
    <div class="callout-title">ℹ️ Note</div>
    В данный момент я активно ищу <strong>наставника</strong> или <strong>учебную практику</strong> по направлению <strong>Frontend / Python</strong>.
  </div>

  <div class="callout callout-tip">
    <div class="callout-title">💡 Tip</div>
    Я только начинаю, поэтому стараюсь писать понятные коммиты: <code>feat:</code>, <code>fix:</code>, <code>docs:</code>.
  </div>

  <hr>

  <h2 id="технологический-стек">Технологический стек</h2>
  <p>Мой текущий уровень владения инструментами и технологиями:</p>

  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Инструмент / Технология</th>
        <th style="text-align: center;">Уровень владения</th>
        <th style="text-align: right;">Практика / Опыт</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: left;"><strong>Школьная информатика</strong></td>
        <td style="text-align: center;">Базовый</td>
        <td style="text-align: right;">11 классов</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>Git &amp; GitHub</strong></td>
        <td style="text-align: center;">Начинающий</td>
        <td style="text-align: right;">Первые шаги</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>VS Code</strong></td>
        <td style="text-align: center;">Базовый</td>
        <td style="text-align: right;">Недавно установил</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>HTML5 &amp; CSS3</strong></td>
        <td style="text-align: center;">В процессе изучения</td>
        <td style="text-align: right;">Учебные задания</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>Python</strong></td>
        <td style="text-align: center;">Начальный</td>
        <td style="text-align: right;">Школьный курс</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>Markdown / GFM</strong></td>
        <td style="text-align: center;">Базовый</td>
        <td style="text-align: right;">Оформление README</td>
      </tr>
    </tbody>
  </table>

  <hr>

  <h2 id="цели-и-план-обучения">Цели и план обучения</h2>
  <p>Мой личный план на ближайшее время:</p>

  <h3>1. Освоение основ (Hard Skills)</h3>
  <ul>
    <li class="task-list-item"><input type="checkbox" checked disabled> Закончить 11 классов</li>
    <li class="task-list-item"><input type="checkbox" checked disabled> Установить Git и VS Code</li>
    <li class="task-list-item"><input type="checkbox" disabled> Освоить навигацию в терминале (<code>cd</code>, <code>pwd</code>, <code>ls</code>, <code>mkdir</code>)</li>
    <li class="task-list-item"><input type="checkbox" disabled> Выучить основы HTML и CSS</li>
    <li class="task-list-item"><input type="checkbox" disabled> Начать изучать JavaScript</li>
  </ul>

  <h3>2. Учебные и карьерные цели</h3>
  <ul>
    <li class="task-list-item"><input type="checkbox" checked disabled> Создать профиль на GitHub</li>
    <li class="task-list-item"><input type="checkbox" disabled> Залить первый репозиторий</li>
    <li class="task-list-item"><input type="checkbox" disabled> Сделать первый Pull Request</li>
    <li class="task-list-item"><input type="checkbox" disabled> Найти наставника или учебную практику</li>
  </ul>

  <hr>

  <h2 id="мой-рабочий-инструментарий">Мой рабочий инструментарий</h2>
  <p>Для работы в редакторе VS Code я постепенно осваиваю сочетания клавиш:</p>
  <ul>
    <li>Быстрое открытие файлов: <kbd>Ctrl</kbd> + <kbd>P</kbd></li>
    <li>Встроенный терминал: <kbd>Ctrl</kbd> + <kbd>`</kbd></li>
    <li>Сохранение файла: <kbd>Ctrl</kbd> + <kbd>S</kbd></li>
  </ul>

  <p>Мой первый учебный bash-скрипт для создания структуры проекта:</p>

<pre><code class="language-bash">#!/usr/bin/env bash
# Мой первый скрипт для учебного проекта
mkdir -p src/{styles,scripts,assets} docs
touch src/index.html src/styles/main.css src/scripts/app.js docs/README.md
echo "Каркас проекта успешно развернут!"</code></pre>

  <div class="callout callout-warning">
    <div class="callout-title">⚠️ Warning</div>
    Никогда не коммитьте системные файлы Windows (<code>Thumbs.db</code>, <code>desktop.ini</code>) и файлы окружения (<code>.env</code>) в открытый репозиторий! Всегда добавляйте их в <code>.gitignore</code>.
  </div>

  <hr>

  <h2 id="системная-конфигурация">Системная конфигурация</h2>

  <details>
    <summary>Нажмите, чтобы посмотреть параметры моего учебного компьютера</summary>
<pre><code>Окружение:
  ОС: Windows 11 Home (x64)
  Эмулятор: Git Bash 2.45 (MinGW64)
  Шрифт редактора: Consolas
  Тема VS Code: Dark+ (default dark)</code></pre>
  </details>

  <hr>

  <h2 id="контакты-для-связи">Контакты для связи</h2>

  <ul>
    <li><strong>Образование:</strong> 11 классов</li>
    <li><strong>Почта:</strong> <a href="mailto:beginner@example.com">beginner@example.com</a></li>
  </ul>

  <div class="footnotes">
    <p id="fn1"><a href="#ref1">^ [1]</a>: Git — распределенная система управления версиями, позволяющая отслеживать историю изменений в файлах и координировать работу команды.</p>
  </div>

</div>

</body>
</html>
