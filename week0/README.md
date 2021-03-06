# Седмица 0 - началото

Това, което ще правим през първата седмица е:

* Да си разкажем малко неща свързани с курсовете, програмирането и ученето.
* Да настроим Python и средата, която ще ползваме през първия месец.
* Да направим първите стъпки в програмирането, запознавайки се с променливи и няколко оператора.

## Задача 0 - Направете си папка, където ще държите всичко.

1. Някъде във вашия компютър си направете папка, която може да се нарече `code`.
2. В нея направете папка, която може да се нарече `Programming0`
3. Всички файлове, свързани с този курс, може да ги пазите в тази папка.

Така ще ви е по-лесно да си организирате всичко.

**Добра идея е тази папка да я сложите в нещо като Dropbox (или пък да я качите в GitHub)**

## Задача 1 - Инсталирайте си Python и пуснете една Hello World програма.

Първата задача е следната:

1. Инсталирайте си Python 3.4.2 - https://www.python.org/downloads/windows/
2. Когато сте готови, трябва да видите иконката на Python, инсталирана в стартовото меню.
3. Намерете програмата, която се казва **Python IDLE**
4. Отваря ви се един прозорец. В него, заредете `hello.py` файла, който се намира в тази седмица.
5. За да го заредите, първо трябва да го изтеглите някъде на компютъра ви.
6. След като го заредите, натиснете `F5`, което ще стартира Python файла.
7. Трябва да видите текст, отпечатан на екрана. [Kачете Screenshot–а като коментар във Facebook групата](https://www.facebook.com/groups/958433530860592/)
 
## Задача 2 - Прочетете философията на Python.

Python има много специфична философия, която е добре описана като модул в езика.

1. За целта, ще ни трябва да пуснем **Python Command Line** програмата, от стартовото меню.
2. Когато ви се отвори един грозен, черен екран.
3. В него напишете следното нещо: `import this` и натиснете Enter.
4. Трябва да ви се отпечата 1 дълъг текст, в който е описана философията на Python.
5. Прочетете я.
6. Направете Screenshot с нея и я качете също в [**темата във форума.**](https://hackbulgaria.com/forum/topic/44/)

## Задача 3 - Пуснете програма от 1 файл и програма от 2 файла

В папката има следните Python файлове:

* `single.py`
* `first.py`
* `second.py`

Вашата задача е да направите следните неща:

1. Изтеглете `single.py` при вас. (Или го копирайте)
2. Заредете `single.py` в IDLE и го пуснете (С `F5`) - вижте резултата.
3. Променете името на `single.py` на нещо друго - стига да няма празни разстояния в него.
4. Пуснете пак файла и вижте как се промени резултата. Може ли да предположите защо става така?

След това:

1. Изтеглете `first.py` и `second.py` (Или ги копирайте)
2. Заредете `second.py` в IDLE и го пуснете.
3. Разгледайте файловете - може ли да предположите защо резултатът е такъв?

## Задача 4 - Пресмятане на изрази

В Python REPL по ваш избор (IDLE / Python Command Line), вижте каква е стойността на следните изрази:

* `2 + 123`
* `2 * 2 + 213`
* `10 * 9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1`
* `1 + 1 + 2 + 3 + 5 + 8 + 13`
* `((13.0 / 8) + (8.0 / 5) + (5.0 / 3) + (3.0 / 2)) / 4`
* `"Python" * 2` - какъв е резултата? Как действа оператора `*`, когато има ляв операнд текст, и десен операнд число?
* `7 / 2`
* `7 // 2`
* Каква е разликата между операторите `/` и `//`?

В Python REPL по ваш избор (IDLE / Python Command Line), напишете **израз**, който да отговаря на следните неща:

* Сумата на числата `1234` и `5678`.
* Произведението на `88` и `99`.
* Числото `2`, повдигнато на степен `32`.
* Числото `2`, повдигнато на степен `32`, разделенето на числото `2`, повдигнато на степен `16`.
* Числото `2`, повдигнато на степен `16` - колко резултата?
* Конкатенацията на низовете `"omg"` и `"wtf"`
* Конкатенацията на низовете `"Spam"`, `" and "` и `"eggs!"`
* Резултатът от умножението на числата от 1 до 10, разделени върху умножението на числата 6, 7, 8, 9 и 10.
* Колко са 20% от 100?
* Колко са 35% от 1235?

## Задача 5 - Изрази с променливи

В Python REPL по ваш избор (IDLE / Python Command Line), дефинирайте следните променливи:

* `first_name = "ТВОЕТО ИМЕ ТУК"`
* `second_name = "ТВОЕТО ИМЕ ТУК"`
* `sum = 500`
* `discount = 0.25`
* `base = 2`
* `exponent = 10`


Използвайки променливите, напишете изрази, които отговарят на следните неща:

* Цялото име на човек, с интервал между първото и второто.
* Колко е сумата `sum`, след приложеното намаление `discount`
* Какво става, когато умножим цялото име на човек (с интервал по средата), с резултатa от `base ** exponent` ?
* Как може да превърнем `sum` в отрицателно число?
* Как може да превърнем превърнатото отрицателно число отгоре, отново в положително?

## Задача 6 - Колко сила ще ни трябва, за да бутнем даден обект?

Имаме следната ситуация:

Трябва да бутнем огромна топка, която тежи `500 kg`. Знаем, че може да я бутнем с ускорение, равно на `1m/s^2`.

**Каква сила ще ни е нужна, за да я бутнем?**

Изразете отговора, използвайки променливи. Това, което може да ви помoгне е втория закон на Нютон: `F = m * a` - силата е равна на масата по ускорението.

Резултатът ще бъде в `kN` - килонютони.

## Задача 7 - Книги и цени.

Във файл с име `books.py` имате следния код:

```python
book1_name = "Pragmatic Thinking and Learning"
book1_price = 30
```

В файла, чрез създаване на нови променливи, с последователна номерация, добавете следните книги:

* Ако цената е Free, то тя се равнява на 0.

| Книга                 | Цена |
|-----------------------|------|
| Learn You a Haskell   | Free |
| The Healthy Programmer| 50   |
| Code Complete         | 60   |
| The Pragmatic Programmer | 20 |
| Pro Git | Free |
| Introduction to Algorithms | 80 |
| Concrete Mathematics | 100 |

След като създаде променливите за съответните книги, в същия файл, използвайки `print()` функцията, отпечатайте следните неща:

* Изпринтете всяка книга, която е налична, заедно с нейната цена.
* Колко е сумата на всички книги?
* Колко е общия брой на всички книги?
* Ако човек вземе **Introduction to Algoritims** и **Concrete Mathematics**, получава 25% намаление. Колко ще е цената тогава?
* Ако човек има бюджет от 150, колко книги най-много може да вземе? Кои са тези книги?

