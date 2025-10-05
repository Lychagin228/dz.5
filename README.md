Домашнее задание к работе 5

Условие задачи

Создать программу вычисления указанной величины.
Результат проверить при заданных исходных значениях.
Реализация программы

#define _USE_MATH_DEFINES

#include <stdio.h>

#include <math.h>

#include <stdlib.h>

#include <locale.h>

int main() {

    setlocale(LC_CTYPE, "RUS");

    double x = 12.3 * pow(10, -1);

    double y = 15.4;

    double z = 0.252 * pow(10, 3);

    double g = pow(y, x + 1) / (pow(fabs(y - 2), 1./3) + 3) + (x + y/2) / (2 * fabs(x + y)) * pow(x + 1, -1 / sin(z));

    printf("x = %lf\n", x);

    printf("y = %lf\n", y);

    printf("z = %lf\n", z);

    printf("g = %lf\n", g);

    return 0;
}

Результаты работы программы

x = 1.230000

y = 15.400000

z = 252.000000

g = 82.825623

Информация о разработчике

Лычагин Антон бИЦ-252
