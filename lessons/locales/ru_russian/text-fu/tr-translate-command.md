# tr (Translate)

## Lesson Content

Команда tr (translate / перевод) позволяет вам переводить набор символов в другой набор символов. Давайте попробуем пример перевода всех символов в нижнем регистре в символы верхнего регистра.

<pre>$ tr a-z A-Z
hello
HELLO</pre>

Как вы можете видеть, мы определили промежутки a-z в A-Z, и весь текст, который мы ввели в нижнем регистре, появился в верхнем регистре.

## Exercise

Попробуйте следующую команду, что происходит?

<pre>$ tr -d ello
hello</pre>

## Quiz Question

Какая команда используется для перевода символов?

## Quiz Answer

tr