# goit-algo2-hw-02

## Завдання 1. Оптимізація черги 3D-принтера в університетській лабораторії

Розробіть програму для оптимізації черги завдань 3D-друку з урахуванням пріоритетів та технічних обмежень принтера, використовуючи жадібний алгоритм.

Програма групує моделі для одночасного друку, не перевищуючи обмеження (10 б).
Завдання з вищим пріоритетом виконуються раніше (10 б).
Час друку групи моделей розраховується як максимальний час серед моделей у групі (10 б).
Програма обробляє всі тестові сценарії (10 б):
завдання однакового пріоритету,
завдання різних пріоритетів,
перевищення обмежень принтера.
Код використовує dataclass для структур даних (10 б).


## Завдання 2. Оптимальне розрізання стрижня для максимального прибутку (Rod Cutting Problem)

Розробіть програму для знаходження оптимального способу розрізання стрижня, щоб отримати максимальний прибуток. Необхідно реалізувати два підходи: через рекурсію з мемоізацією та через табуляцію.

1. На вхід подається довжина стрижня та масив цін, де price[i] — це ціна стрижня довжини i+1 .
2. Потрібно визначити, як розрізати стрижень, щоб отримати максимальний прибуток.
3. Реалізувати обидва підходи динамічного програмування.
4. Вивести оптимальний спосіб розрізання та максимальний прибуток.