[main.c](https://github.com/user-attachments/files/29633530/main.c)
# PracticalWork
практичне завдання 1
#include <stdio.h>

int main() {
    double t1, t2, t3;

    printf("Введіть три значення:\n");
    scanf("%lf %lf %lf", &t1, &t2, &t3);

    double time = 1.0 / (1.0 / t1 + 1.0 / t2 + 1.0 / t3);

    printf("Час, необхідний для з'їдання пирога: %.2f годин\n", time);

    return 0;
}
