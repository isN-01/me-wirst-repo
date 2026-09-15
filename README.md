<h1 id="нигаматуллин ислам">Нигаматуллин Ислам <code>Junior Web Developer</code></h1>
<p><em>Студент колледжа, увлеченный аналитикой и работой с данными.</em></p>
<h2 id="оглавление">Оглавление</h2>
<ul>
    <li><a href="#заголовки">Заголовки</a></li>
    <li><a href="#форматирование-текста">Форматирование текста</a></li>
    <li><a href="#таблицы">Таблицы</a></li>
    <li><a href="#код">Код</a></li>
    <li><a href="#списки">Списки</a></li>
    <li><a href="#ссылки-и-изображения">Ссылки и изображения</a></li>
    <li><a href="#цитаты-и-разделители">Цитаты и разделители</a></li>
    <li><a href="#алерты-github">Алерты GitHub</a></li>
    <li><a href="#html-в-markdown">HTML в Markdown</a></li>
    <li><a href="#сноски-и-формулы">Сноски и формулы</a></li>
  </ul>
<hr>

  <!-- 1. ЗАГОЛОВКИ -->
  <h2 id="заголовки">1. Заголовки</h2>

  <div class="callout callout-note">
    <div class="callout-title">ℹ️ Note</div>
    Пробел после символов <code>#</code> обязателен по стандарту CommonMark.
  </div>

  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Синтаксис</th>
        <th style="text-align: center;">Результат</th>
        <th style="text-align: right;">Уровень</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: left;"><code># Заголовок 1</code></td>
        <td style="text-align: center;"><strong style="font-size: 1.25rem;">Заголовок 1</strong></td>
        <td style="text-align: right;">h1</td>
      </tr>
      <tr>
        <td style="text-align: left;"><code>## Заголовок 2</code></td>
        <td style="text-align: center;"><strong style="font-size: 1.1rem;">Заголовок 2</strong></td>
        <td style="text-align: right;">h2</td>
      </tr>
      <tr>
        <td style="text-align: left;"><code>### Заголовок 3</code></td>
        <td style="text-align: center;"><strong style="font-size: 1rem;">Заголовок 3</strong></td>
        <td style="text-align: right;">h3</td>
      </tr>
      <tr>
        <td style="text-align: left;"><code>#### Заголовок 4</code></td>
        <td style="text-align: center;"><strong style="font-size: 0.9rem;">Заголовок 4</strong></td>
        <td style="text-align: right;">h4</td>
      </tr>
      <tr>
        <td style="text-align: left;"><code>##### Заголовок 5</code></td>
        <td style="text-align: center;"><strong style="font-size: 0.85rem;">Заголовок 5</strong></td>
        <td style="text-align: right;">h5</td>
      </tr>
      <tr>
        <td style="text-align: left;"><code>###### Заголовок 6</code></td>
        <td style="text-align: center;"><strong style="font-size: 0.8rem; color: #8b949e;">Заголовок 6</strong></td>
        <td style="text-align: right;">h6</td>
      </tr>
    </tbody>
  </table>

  <hr>

  <!-- 2. ФОРМАТИРОВАНИЕ ТЕКСТА -->
  <h2 id="форматирование-текста">2. Форматирование текста</h2>

  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Синтаксис</th>
        <th style="text-align: left;">Результат</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>**Жирный**</code> или <code>__Жирный__</code></td>
        <td><strong>Жирный</strong></td>
      </tr>
      <tr>
        <td><code>*Курсив*</code> или <code>_Курсив_</code></td>
        <td><em>Курсив</em></td>
      </tr>
      <tr>
        <td><code>***Жирный курсив***</code></td>
        <td><strong><em>Жирный курсив</em></strong></td>
      </tr>
      <tr>
        <td><code>~~Зачеркнутый текст~~</code></td>
        <td><del>Зачеркнутый текст</del></td>
      </tr>
      <tr>
        <td><code>Строка 1&lt;br&gt;Строка 2</code> или <code>2 пробела в конце</code></td>
        <td>Принудительный перенос строки внутри абзаца</td>
      </tr>
    </tbody>
  </table>

  <hr>

  <!-- 3. ТАБЛИЦЫ -->
  <h2 id="таблицы">3. Таблицы (GFM Tables)</h2>

  <p>Разделительная строка из дефисов <code>---</code> обязательна. Позиция двоеточия <code>:</code> задает выравнивание.</p>

  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Шаблон разделителя</th>
        <th style="text-align: left;">Правило выравнивания</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>:---</code> или <code>---</code></td>
        <td>По левому краю (значение по умолчанию).</td>
      </tr>
      <tr>
        <td><code>:---:</code></td>
        <td>По центру (двоеточия с обеих сторон).</td>
      </tr>
      <tr>
        <td><code>---:</code></td>
        <td>По правому краю (двоеточие справа).</td>
      </tr>
      <tr>
        <td><code>\|</code></td>
        <td>Экранирование символа пайпа <code>|</code> внутри ячейки таблицы.</td>
      </tr>
    </tbody>
  </table>

  <p>Пример таблицы с выравниванием:</p>

  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Влево</th>
        <th style="text-align: center;">По центру</th>
        <th style="text-align: right;">Вправо</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: left;">L-01</td>
        <td style="text-align: center;">C-01</td>
        <td style="text-align: right;">R-01</td>
      </tr>
      <tr>
        <td style="text-align: left;">L-02</td>
        <td style="text-align: center;">C-02</td>
        <td style="text-align: right;">R-02</td>
      </tr>
    </tbody>
  </table>

  <hr>

  <!-- 4. КОД -->
  <h2 id="код">4. Код (Code Blocks &amp; Inline)</h2>

  <p>Инлайн-код: <code>git status</code></p>

  <p>Блок кода с указанием языка для подсветки синтаксиса:</p>

<pre><code class="language-bash">#!/usr/bin/env bash
# Быстрое создание структуры учебного проекта
mkdir -p src/{styles,scripts,assets} docs
touch src/index.html src/styles/main.css src/scripts/app.js docs/README.md
echo "Каркас проекта успешно развернут!"</code></pre>

  <p>Поддерживаемые идентификаторы языков: <code>bash</code>, <code>python</code>, <code>json</code>, <code>yaml</code>, <code>html</code>, <code>js</code>.</p>

  <hr>

  <!-- 5. СПИСКИ -->
  <h2 id="списки">5. Списки (Lists)</h2>

  <h3>Маркированный список</h3>
  <ul>
    <li>Элемент 1</li>
    <li>Элемент 2
      <ul>
        <li>Вложенный (2 пробела)</li>
      </ul>
    </li>
  </ul>

  <h3>Нумерованный список</h3>
  <ol>
    <li>Первый пункт</li>
    <li>Второй пункт</li>
    <li>Третий пункт</li>
  </ol>

  <h3>Чек-лист задач</h3>
  <ul>
    <li class="task-list-item"><input type="checkbox" checked disabled> Выполненная задача</li>
    <li class="task-list-item"><input type="checkbox" disabled> Невыполненная задача</li>
  </ul>

  <hr>

  <!-- 6. ССЫЛКИ И ИЗОБРАЖЕНИЯ -->
  <h2 id="ссылки-и-изображения">6. Ссылки и изображения</h2>

  <table>
    <thead>
      <tr>
        <th style="text-align: left;">Синтаксис</th>
        <th style="text-align: left;">Описание</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>[Текст ссылки](https://domain.ru)</code></td>
        <td><a href="https://domain.ru">Текст ссылки</a> (внешний абсолютный URL)</td>
      </tr>
      <tr>
        <td><code>[Гайд по установке](docs/install.md)</code></td>
        <td>Относительная ссылка на локальный файл внутри репозитория.</td>
      </tr>
      <tr>
        <td><code>![Alt текст](path/to/image.png)</code></td>
        <td>Вставка изображения (отличие от ссылки — префикс <code>!</code>).</td>
      </tr>
      <tr>
        <td><code>[![Alt](badge.png)](https://url.ru)</code></td>
        <td>Изображение-ссылка (клиентский переход по клику на картинку/бейдж).</td>
      </tr>
      <tr>
        <td><code>&lt;https://domain.ru&gt;</code></td>
        <td>Автоматическая ссылка по сырому URL.</td>
      </tr>
    </tbody>
  </table>

  <div class="callout callout-tip">
    <div class="callout-title">💡 Tip</div>
    Для якорных ссылок внутри файла используйте правило слага GitHub/GitLab: нижний регистр, пробелы заменяются дефисом <code>-</code>, знаки пунктуации удаляются. Пример: <code>[Перейти к установке](#установка-проекта)</code>.
  </div>
