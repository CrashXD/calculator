# **Домашнее задание**:
- написать js скрипт "калькулятор" и подключить его к любой html страничке
- страничку со скриптом загрузить на github и включить github pages

## Примерный алгоритм скрипта:
1. просим пользователя ввести какое-нибудь число
2. просим пользователя ввести один из математических операторов (`+`, `-`, `*`, `/`)
3. просим пользователя ввести еще одно число
4. выводим результат вычисления
5. предлагаем пользователю выбор: продолжить и завершить
6. если пользователь отказался, то завершаем вычисление
7. если пользователь выбрал продолжение, то возвращаемся к пункту 2, т.е. снова спрашиваем оператор, число, выводим результат
Результат должен быть накопительным

### Пример работы:
1. вводим число `2`
2. вводим оператор `+`
3. вводим число `5`
4. выводится число `7`
5. выбираем `продолжить`
6. вводим оператор `-`
7. вводим число `1`
8. выводится число `6`
9. выбираем `закончить`
10. скрипт остановился

### Советы:  
\# *используйте бесконечные циклы - `while(true)` или `for(;;)`*  
\# *для выхода из цикла используйте `break`*  
\# *выбор оператора можно реализовать как через `if`, так и через `switch`*  

### Рекомендации:
- явно преобразовывайте типы
- пишите комментарии к своему коду
- придумывайте осознанные названия переменным
- если запутались, начните с начала
- выступайте в роли интерпретатора
(читайте код в слух, что он делает, что сейчас хранится в переменной и т.п.)
- на первых порах не старайтесь оптимизировать код или уменьшить количество строк

*Будет плюсом если продумаете дополнительные проверки на случай ввода некорректных данных и проверки на бесконечное зацикливание.*

## Задача со звездочкой:
добавьте в код сохранение всех введенных чисел и операторов в массив, а после завершения работы пользователем, выведите в консоль эту "историю" вводимых данных с промежуточными результатами.  
Примерно так:  
`2 + 3 = 5`  
`5 - 1 = 4`  
`4 * 2 = 8`  
`8 - 5 = 3`  
