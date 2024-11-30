

<body>
    <h1>Git Cheat Sheet</h1>
    <h2>Описание</h2>
    <p>Git — это система контроля версий, которая позволяет отслеживать изменения в коде, работать в командах и управлять репозиториями. Этот файл содержит основные команды, которые помогут вам начать работать с Git.</p>
    <hr>
    <h2>Настройка Git</h2>
    <h3>Установка имени и email</h3>
    <pre><code>git config --global user.name "Ваше Имя"
git config --global user.email "ваш.email@example.com"</code></pre>
    <h3>Просмотр текущих настроек</h3>
    <pre><code>git config --list</code></pre>
    <hr>
    <h2>Основные команды</h2>
    <h3>Создание репозитория</h3>
    <p>Создать новый репозиторий в текущей директории:</p>
    <pre><code>git init</code></pre>
    <h3>Клонирование репозитория</h3>
    <p>Скопировать существующий репозиторий:</p>
    <pre><code>git clone &lt;URL&gt;</code></pre>
    <hr>
    <h3>Работа с файлами</h3>
    <h4>Добавление файлов в индекс (staging area)</h4>
    <pre><code>git add &lt;файл&gt;        # Добавить конкретный файл
git add .             # Добавить все изменения</code></pre>
    <h4>Просмотр статуса</h4>
    <pre><code>git status</code></pre>
    <h4>Фиксация изменений (commit)</h4>
    <pre><code>git commit -m "Описание изменений"</code></pre>
    <hr>
    <h3>Просмотр изменений</h3>
    <h4>История коммитов</h4>
    <pre><code>git log              # Полный журнал
git log --oneline    # Краткий формат</code></pre>
    <h4>Просмотр изменений в файлах</h4>
    <pre><code>git diff            # Изменения в рабочем каталоге
git diff --staged   # Изменения в индексе</code></pre>
    <hr>
    <h3>Работа с ветками</h3>
    <h4>Создание новой ветки</h4>
    <pre><code>git branch &lt;имя_ветки&gt;</code></pre>
    <h4>Переключение на ветку</h4>
    <pre><code>git checkout &lt;имя_ветки&gt;</code></pre>
    <h4>Создание и переключение на ветку</h4>
    <pre><code>git checkout -b &lt;имя_ветки&gt;</code></pre>
    <h4>Слияние веток</h4>
    <p>Переключитесь на основную ветку и выполните:</p>
    <pre><code>git merge &lt;имя_ветки&gt;</code></pre>
    <h4>Удаление ветки</h4>
    <pre><code>git branch -d &lt;имя_ветки&gt;</code></pre>
    <hr>
    <h3>Работа с удалёнными репозиториями</h3>
    <h4>Добавление удалённого репозитория</h4>
    <pre><code>git remote add origin &lt;URL&gt;</code></pre>
    <h4>Просмотр удалённых репозиториев</h4>
    <pre><code>git remote -v</code></pre>
    <h4>Отправка изменений в удалённый репозиторий</h4>
    <pre><code>git push origin &lt;имя_ветки&gt;</code></pre>
    <h4>Получение изменений из удалённого репозитория</h4>
    <pre><code>git pull origin &lt;имя_ветки&gt;</code></pre>
    <hr>
    <h3>Отмена изменений</h3>
    <h4>Отмена изменений в рабочем каталоге</h4>
    <pre><code>git checkout -- &lt;файл&gt;</code></pre>
    <h4>Удаление файла из индекса</h4>
    <pre><code>git reset &lt;файл&gt;</code></pre>
    <h4>Возврат последнего коммита (сохранение изменений)</h4>
    <pre><code>git reset --soft HEAD~1</code></pre>
    <h4>Возврат последнего коммита (без сохранения изменений)</h4>
    <pre><code>git reset --hard HEAD~1</code></pre>
    <hr>
    <h2>Полезные ссылки</h2>
    <ul>
        <li><a href="https://git-scm.com/doc" target="_blank">Официальная документация Git</a></li>
        <li><a href="https://learngitbranching.js.org/" target="_blank">Интерактивный тренажёр Git</a></li>
    </ul>
    <hr>
    <h2>Лицензия</h2>
    <p>Этот справочник предоставлен под лицензией MIT. Вы можете использовать, изменять и распространять его свободно.</p>
</body>
</html>
