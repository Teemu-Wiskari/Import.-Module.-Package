# Import. Module. Package

1. Разработать структуру программы «Бухгалтерия»:
 - main.py; 
 - application/salary.py;
 - application/db/people.py.
 - Main.py — основной модуль для запуска программы.
 - В модуле salary.py функция calculate_salary.
 - В модуле people.py функция get_employees.

2. Импортировать функции в модуль main.py и вызывать эти функции в конструкции.
 - if __name__ == '__main__':
 - Достаточно добавить туда какой-либо вывод.

3. Познакомиться с модулем datetime. При вызове функций модуля main.py выводить текущую дату.

4. Создать рядом с файлом main.py модуль dirty_main.py и импортировать все функции с помощью конструкции (необязательное задание).

from package.module import *