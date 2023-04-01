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
another attempt to solve a merge with a conflict





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

## 





##