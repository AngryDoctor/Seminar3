# Справка (туториал) по основам системы контроля версий GIT

## Как инициализировать GIT 
**Чтобы инициализировать репозиторий необходимо прописать в терминале следующую команду:**

```
git init
```
## Как узнать статус о папке
**Чтобы узнать статус о папке:**
```
git status
```
## Как включить фиксацию
**Чтобы включить в фиксацию файл:**
```
git add
```


# Туториал (справка) для работы с языком разметки MarkDown 







## Горизонтальная черта

Горизонтальная черта создается тремя звездочками или тремя дефисами. Например, 

***
или

---



## Ссылки
Это встроенная [ссылка с title элементом](http://example.com/link "Я ссылка"). Это — [без title](http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с разметкой как у сносок. Прокатит и [короткая запись][] без указания id.

[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short


## Зачеркивание
В GFM добавлено зачеркивание текста: две тильды `~` до и после текста.

~~Зачеркнуто~~



## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Можно управлять выравниванием столбцов при помощи двоеточия.

| Left-Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |     **$1600** |
| col 2 is      | centered        |         $12   |
| zebra stripes | are neat        |        ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст

Для всего остального есть обычный HTML

| Table 1 | Table 2| 
|:--------|--------|
|Получилось!       |
|и тут текст       |
|                  |




