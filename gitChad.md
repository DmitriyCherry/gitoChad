# Система контроля версий GIT

Система контроля версий – это такая система, необходимая для работы с файлами их версиями, образующимися в ходе редактирования файла либо в процессе его разработки, представленная рядом специально разработанных для этого программ.

Git – программа, предназначенная для гибкого ведения работы с файлами в различных их временных версиях разработки или редактирования.

Репозиторий – папка, предназначенная для работ Git, где хранится информация о версиях файлов, используемых в программе, и отслеживаются все изменения.

Markdown — это облегченный язык разметки с синтаксисом форматирования обычного текста. Его функционал представлен:
- Ссылками
- Списками
- Работой с таблицами
- Работой с изображениями
- Выделением текста и др.

Чтобы добавить ненумерованные списки вставьте знак (*) перед пунктом. Чтобы добавить нумерованные – просто пользуйтесь цифрами.
Чтобы нужный текст был показан курсивом, используйте обрамление текста с помощью знака (*) либо знака (_).
Чтобы выделить текст полужирным используйте обрамление нужного текста с помощью знака (**) или (__).

Для работы с изображениями существует команда ![текст](путь к файлу в репозитории либо ссылка на него).

![текст](https://github.com/DmitriyCherry/gitoChad/blob/main/highway.jpg)

В Git существует ряд команд, необходимых для работы с файлами и их версиями:
- _git init_ – инициализация репозитория в Git;
- _git status_ – информация о статусе выбранного файла;
- _git add_ – создание файла в среде Git;
- _git commit – m “”_ – фиксация созданного файла с некоторым комментарием;
- _git log_ – обращение к списку всех версий файла в соответствии с их коммитами;
- _git checkout __x___ – обращение к некоторому коммиту __x__ в списке;
- _git checkout __master___ – переход в ветку __master__ из списка коммитов.
- _git branch_ – просмотр всех существующих веток;
- _git branch __nameBranch___ – создание новой ветки __nameBranch__;
- _git branch –d __nameBranch___ – удаление ветки __nameBranch__;
- __git merge __nameBranch___ – слияние ветки __nameBranch__ с текущей.
## Игнорирование файлов
Для того, чтобы исключить из отслеживания в репозитории определенные файлы или папки необходимо создать  файл __.gitignore__ и записать в него их названия или шаблоны, соответствующие таким файлам или папкам.
## Работа с сервисом Github
Освоить работу с удаленными репозиториями, которые находятся не на локальной, а на удаленной машине, например, на сервере. Копировать внешний репозиторий на свой ПК можно командой __git clone__.
- _git clone_ ссылка на удаленный репозиторий, который копируем на свой ПК. Команда __git clone__ составная: она не только загружает все изменения, но и пытается слить все ветки на локальном компьютере и в удаленном репозитории;
- _git pull_ – эта команда позволяет отправить нашу версию репозитория на внешний репозиторий (требует авторизации на внешнем репозитории);
- _git push_ – отправить свою версию репозитория в удаленный репозиторий (при первом её использовании нужна __git pull__ авторизация).
- _fork_ – с помощью этой функции можно клонировать чужой репозиторий к себе в библиотеку на Github;
- _pull reguest_ – данная функция предоставляет возможность внесения изменений в файл владельцу репозитория, который был форкнут.
