<h1 align="center">
    Синтаксис Markdown
</h1>

![Изображение](../main/image-1.png "Изображение")
<p align="center">
<img src="https://custom-icon-badges.herokuapp.com/github/stars/AndreyKozhev/markdown-format?logo=star"/>
<img src="https://custom-icon-badges.herokuapp.com/github/issues-raw/AndreyKozhev/markdown-format?logo=issue"/>
<img src="https://custom-icon-badges.herokuapp.com/github/last-commit/AndreyKozhev/markdown-format?logo=history&logoColor=white"/>
</p>

## Ссылки
[Примеры эмодзи](../main/emoji_example.md "Примеры эмодзи")
## Оглавление
+ [Заголовки](https://github.com/AndreyKozhev/Markdown-format#заголовки "Заголовки")
+ [Выделение](https://github.com/AndreyKozhev/Markdown-format#выделение "Выделение")
+ [Списки](https://github.com/AndreyKozhev/Markdown-format#списки "Списки")
+ [Ссылки](https://github.com/AndreyKozhev/Markdown-format#ссылки "Ссылки")
+ [Изображения](https://github.com/AndreyKozhev/Markdown-format#изображения "Изображения")
+ [Блоки кода](https://github.com/AndreyKozhev/Markdown-format#блоки-кода "Блоки кода")
+ [Таблицы](https://github.com/AndreyKozhev/Markdown-format#таблицы "Таблицы")
+ [Цитаты](https://github.com/AndreyKozhev/Markdown-format#цитаты "Цитаты")
+ [Эмодзи](https://github.com/AndreyKozhev/Markdown-format#эмодзи "Эмодзи")
+ [HTML](https://github.com/AndreyKozhev/Markdown-format#html "HTML")
+ [Списки задач](https://github.com/AndreyKozhev/Markdown-format#списки-задач)
+ [Разделительная черта](https://github.com/AndreyKozhev/Markdown-format#%D1%80%D0%B0%D0%B7%D0%B4%D0%B5%D0%BB%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D1%87%D0%B5%D1%80%D1%82%D0%B0)
+ [Блоки Примечание и Предупреждение](https://github.com/AndreyKozhev/Markdown-format#%D0%B1%D0%BB%D0%BE%D0%BA%D0%B8-%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%87%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B8-%D0%BF%D1%80%D0%B5%D0%B4%D1%83%D0%BF%D1%80%D0%B5%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5 "Блоки Примечание и Предупреждение")
### Заголовки
```
# 1 уровень
## 2 уровень
### 3 уровень
#### 4 уровень
##### 5 уровень
###### 6 уровень
```
# 1 уровень
## 2 уровень
### 3 уровень
#### 4 уровень
##### 5 уровень
###### 6 уровень
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Выделение
*Курсив* - ```*Курсив*```  
**Полужирный** - ```**Полужирный**```  
***Полужирный курсив*** - ```***Полужирный курсив***```  
~~Зачёркнутый~~ - ```~~Зачёркнутый~~```  
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Списки
```
+ 1 уровень, 1 элемент
+ 1 уровень, 2 элемент
    - 2 уровень, 1 элемент
        * 3 уровень, 1 элемент
+ 1 уровень,3 элемент
    1. Нумерованный список, 2 уровень, 1 элемент
```
+ 1 уровень, 1 элемент
+ 1 уровень, 2 элемент
    - 2 уровень, 1 элемент
        * 3 уровень, 1 элемент
+ 1 уровень, 3 элемент
    1. Нумерованный список, 2 уровень, 1 элемент  

[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Ссылки
```
[Обычная ссылка в строке](https://www.google.com)
[Обычная ссылка с title](https://www.google.com "Google")
[Относительная ссылка на документ](../blob/master/LICENSE)
```
[Обычная ссылка в строке](https://www.google.com)  
[Обычная ссылка с title](https://www.google.com "Google")  
[Относительная ссылка на документ](../blob/master/LICENSE)  
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Изображения
```
![alt-текст](https://img.shields.io/badge/Platform-Windows-blue "Заголовок")
```
![alt-текст](https://img.shields.io/badge/Platform-Windows-blue "Заголовок")  
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Блоки кода
```
Код пишется между тремя обратными апострофами(`)
Если необходимо, после первых 3 апострофов можно указать язык программирования
```
```js
var s = 3;
alert(s);
```
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Таблицы
```
|  Заголовок 1  |  Заголовок 2 | Заголовок 3 |
| ------------- |:---------:| --------------:|
| строка 1      | строка1   | строка 1       |
| строка 2      | строка 2  |   строка 2     |
| строка 3      | строка 3  |   строка 3     |
```
|  Заголовок 1  |Заголовок 2|  Заголовок 3   |
| ------------- |:---------:| --------------:|
| строка 1      | строка1   | строка 1       |
| строка 2      | строка 2  |   строка 2     |
| строка 3      | строка 3  |   строка 3     |  

[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Цитаты
```
>уровень 1
>>уровень 2
```
>уровень 1
>>уровень 2  

[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Эмодзи
```
:название-эмодзи:
Пример:
:octocat:
```
:octocat:  
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### HTML
```html
<dl>
    <h1>Это заголовок</h1>
    <h2>Тоже заголовок</h2>
</dl>
```
<dl>
    <h1>Это заголовок</h1>
    <h2>Тоже заголовок</h2>
</dl>  

[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Списки задач
```markdown
- [x] Отмечено
- [ ] Не отмечено
```
- [x] Отмечено
- [ ] Неотмечено

[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Разделительная черта
```
***
```
***
[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
### Блоки Примечание и Предупреждение
Первая буква чуствительна к регистру!

На данный момент эта функция находится в стадии бета-тестирования и может быть изменена.

На данный момент заголовки будут на английском.

```
> **Note**
> Это примечание

> **Warning**
> Это предупреждение
```
> **Note**
> Это примечание

> **Warning**
> Это предупреждение

Источник: https://github.com/github-community/community/discussions/16925

[Оглавление](https://github.com/AndreyKozhev/Markdown-format#оглавление "Оглавление")
