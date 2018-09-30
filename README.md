<!--# History Of Programming-->
# История Программ
<!--## История программирования и вычислительной техники-->

Основы программирования были заложены <a href="https://ru.wikipedia.org/wiki/Тьюринг,_Алан">Аланом Тьюрингом</a> в 1938 году.
Он не был первым, кто придумал программируемую машину, но он первым понял, что программы — это всего лишь данные.

Первым кто изобрёл компьютер считается  английский математик 
<a href="https://ru.wikipedia.org/wiki/Бэббидж,_Чарлз">Ча́рлз Бэ́ббидж</a>.

Первым компьютером считается <a href="https://ru.wikipedia.org/wiki/Разностная_машина_Чарльза_Бэббиджа">Аналитическая маши́на Чарльза Бэббиджа</a> — механический аппарат, изобретённый английским математиком Чарльзом Бэббиджем, предназначенный для автоматизации вычислений путём аппроксимации функций многочленами и вычисления конечных разностей. Возможность приближённого представления в многочленах логарифмов и тригонометрических функций позволяет рассматривать эту машину как довольно универсальный вычислительный прибор.

А первым программистом считается <a href="https://ru.wikipedia.org/wiki/Лавлейс,_Ада">Ада Лавлейс</a>, которая описывает в одном из своих комментариев алгоритм вычисления чисел Бернулли на <a href="https://ru.wikipedia.org/wiki/Разностная_машина_Чарльза_Бэббиджа">аналитической машине</a>.
Было признано, что это первая программа, специально реализованная для воспроизведения на компьютере, и по этой причине Ада Лавлейс считается первым программистом, несмотря на то, что машина Бэббиджа так и не была построена при жизни Ады. Более того, в своих записях она предрекала, что, подобно тому, как Жаккардов ткацкий станок может ткать цветы и листья, аналитическая машина способна создавать алгебраические формулы, а в перспективе — писать музыку, рисовать картины — и укажет «науке такие пути, какие нам и не снились». 


-----------------------------------

К 1945 году Тьюринг уже писал настоящие программы для настоящих компьютеров, используя код, который мы смогли бы прочитать (приложив определенные усилия).

-----------------------------------

В своих программах он использовал циклы, конструкции ветвления, операторы присваивания, подпрограммы, стеки и другие знакомые нам структуры. Тьюринг использовал двоичный язык.

-----------------------------------

С тех пор в программировании произошло несколько революций. Одна из самых известных — революция языков.

------------------------------------

Во-первых, в конце 1940-х появились ассемблеры. Эти «языки» освободили программистов от тяжкого бремени трансляции их программ в двоичный код.

------------------------------------

В 1951 году Грейс Хоппер изобрела первый компилятор A0. Именно она фактически ввела термин компилятор.В 1953 году был изобретен язык Fortran, затем COBOL, PL/1, SNOBOL, C, Pascal, C++, Java и так до бесконечности..

------------------------------------

Другая, еще более важная революция произошла в парадигмах программирования. Парадигма — это способ программирования, не зависящий от конкретного языка. Парадигма определяет, какие структуры использовать и когда их использовать.

------------------------------------

В 1968 году Эдсгер Вибе Дейкстра предложил взамен использования переходов (инструкций goto ) парадигму структурного программирования (конструкции if / then / else и do / while / until). Структурное программирование накладывает ограничение на прямую передачу управления.

------------------------------------

В 1966 году Оле-Йохан Даль и Кристен Нюгор заметили, что в языке ALGOL есть возможность переместить кадр стека вызова функции в динамическую память (кучу), благодаря чему локальные переменные, объявленные внутри функции, могут сохраняться после выхода из нее.

------------------------------------

В результате функция превращалась в конструктор
класса, локальные переменные — в переменные экземпляра, а вложенные функции — в методы. Это привело к открытию полиморфизма через строгое использование указателей на функции.

------------------------------------

Это объектно - ориентированное программирование, которое накладывает ограничение на косвенную передачу управления.

------------------------------------

Третьей парадигмой, начавшей распространяться относительно недавно, является самая первая из придуманных. Фактически изобретение этой парадигмы предшествовало появлению самой идеи программирования.

-----------------------------------

Функциональное программирование является результатом работы Алонзо Чёрча, который в 1936 году изобрел лямбда-исчисление, исследуя ту же математическую задачу, которая примерно в то же время занимала Алана Тьюринга.

-----------------------------------

Его λ-исчисление легло в основу языка LISP, изобретенного в 1958 году Джоном Маккарти.Основным понятием λ-исчисления является неизменяемость — то есть невозможность изменения значений символов. Фактически это означает, что функциональный язык не имеет инструкции присваивания.

-----------------------------------

В действительности большинство функциональных языков обладает некоторыми средствами, позволяющими изменять значение переменной, но в очень ограниченных случаях.Подводя итог, можно сказать, что:Функциональное программирование накладывает ограничение на присваивание.

-----------------------------------

Все три парадигмы говорят нам не столько что делать, сколько
чего нельзя делать

Скорее всего, эти три парадигмы останутся единственными,
которые мы увидим, — по крайней мере единственными, что-то отнимающими у нас.
 Доказательством отсутствия новых парадигм может служить
тот факт, что все три известные парадигмы были открыты в течение десяти
лет, между 1958 и 1968 годами.
 За многие последующие десятилетия не появилось ни одной новой парадигмы

-----------------------------------

В итоге: полиморфизм используется как механизм преодоления архитектурных границ, функциональное программирование используется для наложения ограничений на местоположение данных и порядка доступа к ним а структурное программирование как алгоритмическая основа для наших модулей.

Имеем три главных аспекта строительства архитектуры:
Функциональность, Разделение компонентов и Управление данными.

----------------------------------


