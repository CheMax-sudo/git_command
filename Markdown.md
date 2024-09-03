# Заголовок первого уровня
## Заголовок второго уровня ##
### Заголовок третьего уровня
#### Заголовок четвёртого уровня #
##### Заголовок пятого уровня ############
###### Заголовок шестого уровня
##
*Текст курсивом*

_Текст курсивом_
##
**Жирный текст**

__Жирный текст__
##
***Текст жирным курсивом***

___Текст жирным курсивом___
##
Кор*рек*тно, кор**рек**тно, кор***рек***тно

Некор_рек_тно, некор__рек__тно, некор___рек___тно
##
~~Зачёркнутый текст~~
##
<u>Подчёркнутый текст</u>
##
Разделители (horizontal rules)
***
---
___
*	*  **
##
> Оформление цитатой
последовательных строк
внутри одного параграфа
> > Вложенная цитата
> > > Цитата третьего уровня
##
* Первый пункт
- Второй пункт
+ Третий пункт
##
- [x] Отмеченный пункт
- [ ] Неотмеченный пункт
##
1. Пункт
	1. Подпункт
		1. Подподпункт

- Пункт
	- Подпункт
		- Подподпункт


1. Пункт
	- Подпункт
		* Подподпункт

+ Пункт
	1. Подпункт

- Пункт
  - [x] Отмеченный подпункт
  - [ ] Неотмеченный подпункт
    1. Подподпункт
    ##
    1. Первый пункт
	> Цитата внутри первого пункта
1. Второй пункт
 	
    Параграф внутри второго пункта
1. Третий пункт
##
<https://geekbrains.ru/media/code/>

<https://yandex.ru/media/code/>

[Geek Brains](https://geekbrains.ru/media/) без подсказки

[Yandex](https://yandex.ru/media/ "Всплывающая подсказка") с подсказкой

[Geek Brains][1]

[Раздел «Код»][code]


[1]: https://skillbox.ru/media "Всплывающая подсказка"
[code]: https://skillbox.ru/media/code/
##
![Изображение](m.png "Логотип Markdown")
##
```python
if x > 0:
	print (x)
else:
	print ('Hello, World!')
```

```c
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

```javascript
let x = 12;
let y = 6;
console.log(x + y);
```
##
|Столбец 1|Столбец 2|Столбец 3|
|:-|:-:|-:|
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|
|Запись|Запись|Запись|
##