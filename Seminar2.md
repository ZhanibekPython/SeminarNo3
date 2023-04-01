## Добавление репозитория в проект

** Чтобы добавить версионность в проект, необходимо установить Гит на комп и прописать след команду инициализации в терминале:**
```
git init
```

## Как проверить состояние проекта

** Чтобы проверить состояние проекта, необходимо ввести в теримнал следующую команду:**
```fix
git status
```
## Как проверить состояние проекта


# Туториал по исполз разметки Маркдаун

## Добавление заголовков

# Заголовок первого уровня #

## Заголовок h2

### Заголовок h3

#### Заголовок h4

##### Заголовок h5
###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с
обратной стороны.

## Добавление картинок

## Картинки
Картинка без `alt` текста
![](//placehold.it/150x100)

Картинка с альтом и тайтлом:
![Alt text](//placehold.it/150x100 "Можно задать title")

Запомнить просто: синтаксис как у ссылок, только перед
открывающей квадратной скобкой ставится восклицательный
знак.

Картинки «сноски»:
![Картинка][image1]
![Картинка][image2]
![Картинка][image3]
[image1]: //placehold.it/250x100
[image2]: //placehold.it/200x100
[image3]: //placehold.it/150x100
Картинки-ссылки:
[![Alt text](//placehold.it/150x100)]
(http://example.com/)


## Добавление исходного кода

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
<ul>
<li class="tab-conversation active">
<a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
<span class="comment-count">0
комментариев</span>
<span class="comment-countplaceholder">
Комментарии</span>
</a>
</li>
<li class="dropdown user-menu" data-role="logout">
<a href="#" class="dropdown-toggle" datatoggle="
dropdown">
<span class="dropdown-toggle-wrapper">
<span>
Войти
</span>
</span>
<span class="caret"></span>
</a>
</li>
</ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.

## Добавление таблиц
В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.

## _*Citations*_

### Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:
> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:

> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.

> > Вложенная цитата.
>
> Here's some example code:
>
> return shell_exec("echo $input |
$markdown_script");