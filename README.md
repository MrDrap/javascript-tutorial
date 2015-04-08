
# Учебник JavaScript

Этот репозитарий содержит [учебник JavaScript](https://learn.javascript.ru/tutorial): разделы, статьи, задачи.

Движок, написанный на io.js, находится в отдельном репозитарии https://github.com/iliakan/javascript-nodejs, а здесь &mdash; текст.

Делать исправления и предлагать PR можно здесь.

## Структура

Каждому разделу, статье или задаче соответствует директория.

Эта директория имеет вид `N-url`, где `N` - это номер для сортировки статей и разделов (они упорядочены), а `url` &mdash; URL-имя, по которому материал будет доступен.

В директории находится один из файлов:

  - `index.md` для раздела
  - `article.md` для статьи
  - `task.md` для условия задачи (+там же `solution.md` с решением)

Каждый из этих файлов начинается с `# Заголовка материала`.

Абсолютный URL для разделов и статей -- это URL-имя без номера и родителей, для задачи -- с префиксом `/task/`.

Например:

  - директория `2-ui/3-event-details` с файлом `index.md` - это раздел сайта "События в деталях", он будет доступен по URL `/event-details`.
  - директория `2-ui/3-event-details/6-drag-and-drop` с файлом `article.md` содержит статью "Мышь: Drag'n'Drop`, доступную по URL `/drag-and-drop`.
  - директория `2-ui/3-event-details/6-drag-and-drop/slider` с файлом `task.md` содержит задачу с названием "Слайдер", доступную по адресу `/task/slider`.

Ресурсы и примеры, необходимые для статьи, раздела или задачи, находятся в её директории. На них можно ссылаться из материала.

Все исправления и замечания посмотрю и учту.

Thank you for editing :)