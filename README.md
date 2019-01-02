# Механика и основы решения задач для нетехнических направлений обучения

Пособие для бакавриатов технологических нетехнических направлений обучения высшего образования созедржит ознакомительную информаицю о методике теоретических расчетов в области теоретической и практической механики. Пособие содержит задания по решению задач с подробными методиками для осуществления расчетов.

## Оглавление

### I. [Основы теоретической механики](#basic)
1. [Понятия и определения](#basic)
3. [Алгоритм решения задач](#algo1)
4. Пример решения задач
5. Задачи для самостоятельного решения

### II. Введение в сопротивление материалов
1. Понятия и определения
3. Алгоритм решения задач
4. Растяжение, сжатие
5. Геометрические характеристики плоских сечений
6. Кручение
7. Изгиб
8. Задачи для самостоятельного решения

### III. Программные комплексы для решения задач
1. GNU Octave
2. Maxima

### IV. Правила оформления отчетов

### V. Библиографический список


## I. Основы теоретической механики<a name="basic"></a>

### Понятия и определения

Наука о механическом движении и взаимодействии материальных тел назвается **механика**.
**Силой** называется мера действий материальных тел друг на друга. Сила является __векторной__ величиной. Ее действие на тело определяется __числовым значением__ (__модулем__), __направлением__, __точкой приложения__ силы. Основной единицей измерения силы в Международной системе единиц (СИ) является 1 ньютон (1 Н). Силу, как и другие векторные величины, будем обозначать буквой с чертой над нею F&#8407;

**Статикой** называется раздел механики, в котором излагается учение о силах и зучаются условия равновесия материальных тел, находящихся под действием сил. В данном пособии рассматривается задачи только в рамках этого раздела.

**Равновесие** - состояние покая тела по отношению к другим телам. В пособии рассматриваются только задачи о равновесии твердых тел.

**Абсолютно твердое тело** - такое тело, расстояние между каждыми двумя точками которого всегда остается постоянным. _В дальнейшем при решении задач статики все тела рассматриваются как абсолютно твердые, для краткости называют просто твердыми телами._

Две силы, приложенные к телу в одной точке, имеют **равнодействующую** (R&#8407;) равную геометрической (векоторной) сумме этих сил, приложенную в той же точке.

При всяком действии одного материального тела на другое имеет место такое же численно, но противоположное по направлению **противодействие** (F&#8407; = -F&#8407;).

Все то, что ограничивает перемещение тела в пространстве, называют **связью**. Направлена реакция связи в сторону, противоположную той, куда связь не дает перемещаться телу.

### Алгоритм решения задач <a name="algo1"></a>

Процесс решения сводится к следующим операциям:

1. _Выбор тела (или тел), равновесие которого должно быть рассмотрено_
2. _Изображение действующих сил_
3. _Составление условий равновесия_
4. _Определение искомых величин, проверка правильности решения и исследование полученных результатов_
