<h1 id="нигаматуллин ислам">Нигаматуллин Ислам <code>Junior Web Developer</code></h1>
<p><em>Студент колледжа, увлеченный аналитикой и работой с данными.</em></p>
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
  <p>Привет! Я закончил 11 классов и пока знаю только школьную программу по информатике. Сейчас мой фокус — переход от простых задач из учебника к реальной разработке: командной строке, системам контроля версий и написанию своего кода.</p>

  <div class="callout callout-note">
    <div class="callout-title">ℹ️ Note</div>
    В данный момент я активно ищу учебную практику или ментора по направлению <strong>Frontend / DevOps</strong>.
  </div>

  <div class="callout callout-tip">
    <div class="callout-title">💡 Tip</div>
    При написании коммитов я строго придерживаюсь формата Conventional Commits: <code>feat:</code>, <code>fix:</code>, <code>refactor:</code>, <code>docs:</code>.
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
        <td style="text-align: left;"><strong>Git &amp; Git Bash</strong></td>
        <td style="text-align: center;">Базовый CLI</td>
        <td style="text-align: right;">30+ часов практики</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>VS Code &amp; Plugins</strong></td>
        <td style="text-align: center;">Продвинутый</td>
        <td style="text-align: right;">Ежедневная среда</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>HTML5 &amp; CSS3</strong></td>
        <td style="text-align: center;">Уверенный | Семантика</td>
        <td style="text-align: right;">4 учебных проекта</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>JavaScript (ES6+)</strong></td>
        <td style="text-align: center;">В процессе изучения</td>
        <td style="text-align: right;">Решение задач</td>
      </tr>
      <tr>
        <td style="text-align: left;"><strong>Markdown / GFM</strong></td>
        <td style="text-align: center;">Свободно</td>
        <td style="text-align: right;">Документирование</td>
      </tr>
    </tbody>
  </table>

  <hr>

  <h2 id="цели-и-план-обучения">Цели и план обучения</h2>
  <p>Мой личный роадмап на текущий учебный семестр:</p>

  <h3>1. Освоение инструментов (Hard Skills)</h3>
  <ul>
    <li class="task-list-item"><input type="checkbox" checked disabled> Освоить навигацию в терминале без мыши (<code>cd</code>, <code>pwd</code>, <code>ls</code>, <code>mkdir</code>)</li>
    <li class="task-list-item"><input type="checkbox" checked disabled> Оформить визитку профиля на GitHub через Markdown</li>
    <li class="task-list-item"><input type="checkbox" disabled> Опубликовать проект на бесплатном хостинге GitHub Pages</li>
    <li class="task-list-item"><input type="checkbox" disabled> Настроить автоматический линтинг через GitHub Actions</li>
  </ul>

  <h3>2. Учебные и карьерные цели</h3>
  <ul>
    <li class="task-list-item"><input type="checkbox" checked disabled> Создать профиль на GitHub и залить первый репозиторий</li>
    <li class="task-list-item"><input type="checkbox" disabled> Собрать портфолио минимум из 3 полноценных проектов</li>
    <li class="task-list-item"><input type="checkbox" disabled> Провести первое совместное код-ревью через Pull Request</li>
  </ul>

  <hr>

  <h2 id="мой-рабочий-инструментарий">Мой рабочий инструментарий</h2>
  <p>Для быстрой работы в редакторе VS Code я ежедневно использую сочетания клавиш:</p>
  <ul>
    <li>Быстрое открытие файлов: <kbd>Ctrl</kbd> + <kbd>P</kbd></li>
    <li>Множественный курсор: <kbd>Alt</kbd> + клик мыши</li>
    <li>Встроенный терминал: <kbd>Ctrl</kbd> + <kbd>`</kbd></li>
  </ul>

  <p>Мой любимый стартовый bash-скрипт для быстрого развертывания проекта:</p>

<pre><code class="language-bash">#!/usr/bin/env bash
# Быстрое создание структуры учебного проекта
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
    <summary>Нажмите, чтобы посмотреть параметры рабочей станции разработчика</summary>
<pre><code>Окружение:
  ОС: Windows 11 Pro (x64)
  Эмулятор: Git Bash 2.45 (MinGW64)
  Шрифт редактора: JetBrains Mono
  Тема VS Code: GitHub Dark Default</code></pre>
  </details>

  <hr>

  <h2 id="контакты-для-связи">Контакты для связи</h2>

  <ul>
    <li><strong>Учебное заведение:</strong> Колледж цифровых технологий</li>
    <li><strong>Группа:</strong> ИСП-21</li>
    <li><strong>Прямая почта:</strong> <a href="mailto:student@college.edu">student@college.edu</a></li>
  </ul>

  <div class="footnotes">
    <p id="fn1"><a href="#ref1">^ [1]</a>: Git — распределенная система управления версиями, позволяющая отслеживать историю изменений в файлах и координировать работу команды.</p>
  </div>

</div>

</body>
</html>
