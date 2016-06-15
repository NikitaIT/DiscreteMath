# Дискретная математика
### Билет 1 
### Делимость целых чисел. НОД и его свойства. Простые числа. Решето Эратосфена. Ал-горитмы факторизации (метод пробных делителей и метод Ферма).
#### Делимость целых чисел.
#### НОД и его свойства.
#### Простые числа.
#### Решето Эратосфена.
Для нахождения всех простых чисел не больше заданного числа n, следуя методу Эратосфена, нужно выполнить следующие шаги:

- Выписать подряд все целые числа от двух до n (2, 3, 4, …, n).
- Пусть переменная p изначально равна двум — первому простому числу.
- Зачеркнуть в списке числа от 2p до n считая шагами по p (это будут числа кратные p: 2p, 3p, 4p, …).
- Найти первое незачёркнутое число в списке, большее чем p, и присвоить значению переменной p это число.
- Повторять шаги 3 и 4, пока возможно.
- Теперь все незачёркнутые числа в списке — это все простые числа от 2 до n.

На шаге № 3 числа можно зачеркивать начиная сразу с числа p^2. И останавливать алгоритм, когда p^2 станет больше, чем n.

![Решето Эратосфена](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/New_Animation_Sieve_of_Eratosthenes.gif/400px-New_Animation_Sieve_of_Eratosthenes.gif)
#### Ал-горитмы факторизации (метод пробных делителей и метод Ферма).
