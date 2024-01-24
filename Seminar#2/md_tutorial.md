# Туториал по языку разметки MarkDown

## Как добавить заголовки

Заголовки отмечаются диезом # в начале строки, от одного до шести:

```
# Заголовок
```

Например:
# Заголовок
## Заголовок
### Заголовок
#### Заголовок
##### Заголовок
###### Заголовок


## Как добавить исходный код

Чтобы добавить исходный код, необходимо использовать конструкцию следующего вида:

```html
<table><tr><td style="color:#00FF00">Текст</td></tr></table>
```
Пример рабочего кода:
<table><tr><td style="color:#00FF00">Текст</td></tr></table>

## Как добавить таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть. Для этого используются символ pipe или вертикальной черты ( | ) для разделения ячеек и дефиса ( - ) для создания строки заголовка.

```
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Cell 2   | Cell 3   |
| Row 2    | Cell 5   | Cell 6   |
| Row 3    | Cell 8   | Cell 9   |
```
Пример:

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Cell 2   | Cell 3   |
| Row 2    | Cell 5   | Cell 6   |
| Row 3    | Cell 8   | Cell 9   |

## Как добавить изображения

**Чтобы добавить изображения в разметку MarkDown, используйте следующую конструкцию:**

```
![альтернативный текст](изображение или ссылка на изображение с указанием расширения)
```
Пример:
![природа](https://mykaleidoscope.ru/x/uploads/posts/2022-10/1666365077_54-mykaleidoscope-ru-p-krasivie-peizazhi-prirodi-oboi-62.jpg)

**Чтобы добавить картинку-ссылку, необходимо модифицировать блок-схему выше следующим образом:**

```
[![текст](ссылка на изображение)](ссылка на изображение или страницу, на которую перейдем, если кликнем по изображению)
```
[![](https://sun9-38.userapi.com/c840123/v840123041/5a86d/y7p63AiaxGw.jpg)](https://rutube.ru/video/8ee7778cc70eacfffa644c585ceded5f/?r=wd)


## Как добавить цитаты

**Цитаты оформляются как в емейлах, с помощью символа > :**

```
>  This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
```
Например:

>  This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

**Вложение цитаты в цитату выглядит следующим образом:**
```
>  This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

```
Пример:

>  This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>>Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

## Как добавить списки

## Как добавить ссылки