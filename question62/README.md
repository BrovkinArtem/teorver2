# Билет №62. Коэффициент корреляции Кендалла.

Коэффициент корреляции Кенделла — мера линейной связи между случайными величинами. Корреляция Кенделла является ранговой, то есть для оценки силы связи используются не численные значения, а соответствующие им ранги.

Коэффициент корреляции Кендалла используется в случае, когда переменные представлены двумя порядковыми шкалами при условии, что связанные ранги отсутствуют. Вычисление коэффициента Кендалла связано с подсчетом числа совпадений и инверсий.

Заданы две выборки $x$ и $y$.

Упорядочиваем индвидуально по возрастанию значений выборки $x$ (рангов). На основании ранжировки выборки $y$ поставим баллы:

+1 сколько рангов правее больше (сумма совпадений)

-1 сколько рангов правее меньше (сумма инверсии)

$\tau = \frac{сумма \ баллов}{\frac{1}{2} n(n - 1)}$

$-1 \leq \tau \leq 1$

Пример:

![image](https://user-images.githubusercontent.com/78729103/211367096-ec29cf43-2245-426d-8867-ecf4df979f67.png)

1. Переоформляем данные таким образом, чтобы один из рядов (в данном случае ряд xi) оказался ранжированным. Другими словами, мы переставляем пары x и y в нужном порядке и вносим данные в столбцы 1 и 2.
2. 2. Определяем «степень ранжированности» 2-го ряда (yi). Эта процедура проводится в следующей последовательности:

а) берем первое значение неранжированного ряда «3». Подсчитываем количество рангов ниже данного числа, которые больше сравниваемого значения. Таких значений 9 (числа 6, 7, 4, 9, 5, 11, 8, 12 и 10). Заносим число 9 в столбец «совпадения». Затем подсчитываем количество значений, которые меньше трех. Таких значений 2 (ранги 1 и 2); вносим число 2 в графу «инверсии».

б) отбрасываем число 3 (мы с ним уже поработали) и повторяем процедуру для следующего значения «6»: число совпадений равно 6 (ранги 7, 9, 11, 8, 12 и 10), число инверсий – 4 (ранги 1, 2, 4 и 5). Вносим число 6 в графу «совпадения», а число 4 – в графу «инверсии».

в) аналогичным образом процедура повторяется до конца ряда; при этом следует помнить, что каждое «отработанное» значение исключается из дальнейшего рассмотрения (подсчитываются только ранги, которые лежат ниже данного числа).

3. Подсчитывается сумма совпадений (Р) и сумма инверсий (Q); данные вносятся в одну и трех взаимозаменяемых формул коэффициента Кендалла (8.10). Проводятся соответствующие вычисления.

сумма баллов = сумма совпадений - сумма инверсий

$\tau = \frac{51 - 15}{\frac{1}{2} 12(12 - 1)} = 0,55$

Находим критическое значения коэффициента для данной выборки в таблице: $τ_{кр.} = 0,45$;

Эмпирически полученное значение сравнивается с табличным.

Вывод

$τ = 0,55 > τ_{кр.} = 0,45$

Корреляция статистически значима для 1-го уровня.

## Создатель

Автор расписанного билета: Кузнецова Елизавета

Кто проверил:


## Ресурсы
- лекции Рогова А.А. с прошлого года
- [дополнительный ресурс](https://studfile.net/preview/5855743/page:29/)
