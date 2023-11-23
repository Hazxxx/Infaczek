#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <math.h>
#include "winbgi2.h"
#include <time.h>
#include <stdlib.h>

/*int main()
{
    int a;
    int b;
    int c;
    int d;
    int e;
    int f;
    double g;
    double h;

    printf("-----------------------------\n");
    printf("\t\tMy Calculator");
    printf("\n-----------------------------");

    printf("\n\n-------Addition---------\n");

        printf("\n\nEnter your first number:");
        scanf("%d", &a);

        printf("Enter your second number:");
        scanf("%d", &b);

        printf("Your result is: %d", a + b);

        printf("\n\n-----Substraction-------\n");

        printf("\n\nEnter your first number:");
        scanf("%d", &c);

        printf("Enter your second number:");
        scanf("%d", &d);

        printf("Your result is: %d", c - d);

        printf("\n\n-----Multiplication-------\n");

        printf("\n\nEnter your first number:");
        scanf("%d", &e);

        printf("Enter your second number:");
        scanf("%d", &f);

        printf("Your result is: %d", e * f);

        printf("\n\n-----Division-------\n");

        printf("\n\nEnter your first number:");
        scanf("%d", &g);

        printf("Enter your second number:");
        scanf("%d", &h);

        if (h == 0);
        printf("You cannot divide by zero!");

        printf("\nYour result is: %lf", g / h);
      
    return 0;
}*/

/*int main() {

    char grade = 'A';

    switch (grade) {
    case 'A':
        printf("You did great!");
        break;
    case 'B':
        printf("You did good");
    }

}*/

/*int main() {

    graphics(200, 200);
    line(10, 10, 100, 10);
    line(10, 10, 10, 100);
    line(10, 100, 100, 100);
    line(100, 10, 100, 100);
    wait();

} */

/*int main() {

    graphics(200, 200);
    circle(100, 100, 50);
    line(100, 150, 100, 300);
    line(50, 190, 150, 190);
    line(100, 300, 50, 350);
    line(100, 300, 150, 350);
    wait();

}*/

/*int main() {

    graphics(200, 200);
    circle(60, 100, 50);
    circle(150, 100, 50);
    circle(240, 100, 50);
    circle(330, 100, 50);
    wait();

}*/

/*int main() {

    int x, y, r;
    x = 50;
    y = 50;
    r = 50;

    graphics(x, y);
    circle(x, y, r);
    wait();
}*/

/*int main() {

    int d;
    d = 100;
    graphics(200, 200);
    circle(100, 100, 2 * d);
    circle(200, 100, 2 * d);
    circle(300, 100, 2 * d);
    circle(400, 100, 2 * d);

    wait();
}*/

/*int main() {
    int y;
    y = 100;
    graphics(200, 200);
    circle(100, y, 50);
    circle(200, y, 50);
    circle(300, y, 50);
    circle(400, y, 50);

    wait();
}*/

/*int main() {
    int x, y, r;
    x = 0;
    y = 0;
    r = 10;

    graphics(200, 200);
    setlinestyle(1, 0, 2); //Nie udane zadanie! Powtórzyć
    setcolor(GREEN);

    while (x < 280) {
        circle(x, 0, r);
        x = y + 10;
    }

    wait();
}*/



/*void obrazek(int a, int b, int c, int d) {
    line(a, b, c+a, d);
    line(a, b+d, c, d);
    line(a, b+d, c+a, d+b);
    line(a+c, b, c+a, d+b);
}*/

/*void obrazek(int x, int y, int r) {
    line(r, y, 2*r, y);
    line(x, r, x, 2*r);    //DUPA
    line(r, y, 2*r, y); 
    line(2*r, r , 2*r, 2*r);
}*/

/*void obrazek(int x, int y) {
    circle(x/2+100, y, 100);
    circle(x/2+200, y, 100);
    circle(x/2+300, y, 100);
    circle(x/2+400, y, 100);
}*/

/*void obrazek(int x, int y, int h) {
    line(x-50, y+50, x+50, y+50);
    line(x, y+20, x, h);
    line(x-50, h+50, x, h);
    line(x, h, x+50, h+50);
    circle(x, y, 20);
}*/

/*void obrazek(int a) {
    line(a, a, a+100, a);
    line(a, a, a, a+100);
    line(a, a+100, a+100, a+100);
    line(a+100, a, a+100, a+100);
}*/

/*void obrazek(double a) {
    a = -20;

    while (a < 20) {
        circle(-a+100, -a*a+100, 1);
        a = a + 0.001;
    }

}*/


/*void obrazek(double a) {
    a = 0;

    while (a < 2 * 3.14) {
        circle(100*sin(a) + 100, 100*cos(a) + 100, 3);
        a = a + 0.01;
    }

}
*/

/*void obrazek(double a) {
    a = 0;

    while (a < 2 * 3.14) {
        circle(100*sin(a)*cos(4*a)+100, 100*cos(a)*cos(4*a) + 100, 3);
        a = a + 0.01;
    }

}*/

/*void obrazek(double a, double r) {
    a = 0;
    r = (cos(a) + 2) / 3;
    while (a < 2 * 3.14) {
        circle(100 * r * sin(a) + 100, 100 * r * cos(a) + 100, 3);
        a = a + 0.1;
    }
}
*/

/*void main() {
    graphics(500, 500);
    obrazek(100, 100);
    wait();
}*/

/*int main(int a, int b, int c, double pierwszyx, double drugix, double Delta) {
   
    printf("Program obliczajacy x z wzoru funkcji kwadratowej.\n");
    printf("Wpisz wspolczynniki a, b, i c:");
    scanf("%d%d%d", &a, &b, &c);

    Delta = (b * b) - 4 * (a * c);

    if (Delta < 0) {
        printf("x nie nalezy do zbioru liczb rzeczywistych");
    }
    
    if (Delta >= 0) {
        pierwszyx = (-b + sqrt(Delta)) / (2 * a);
        drugix = (-b - sqrt(Delta)) / (2 * a);
        printf("%lf\n", pierwszyx);
        printf("%lf", drugix);
    }
    
}*/

/*int main() {
    int num, fact, count = 1, silnia = 1;

    printf("Enter any number to find factorial\n");
    scanf("%d", &num);

    while (count <= num) {
        fact = fact * count;
        count++;
    }
    printf("Factorial of %d is %d", num, fact);
    return 0;
}*/

/*int main()
{
    int n_0 = 0;
    int n_1 = 1;
    int n_c = 0;
    int n;
    scanf("%d", &n);
    for (int i = 0; i < n; i++) {
        n_c = n_0 + n_1;
        n_0 = n_1;
        n_1 = n_c;
    }
    printf("%d", n_c);
}*/

/*int main() {
    int sn;
    int an;
    int n;
    int a;
    int r;
    printf("Wpisz pierwszy wyraz ciagu arytmetycznego:\t\n");
    scanf("%d", &a);
    printf("Wpisz roznice ciagu arytmetycznego:\t\n");
    scanf("%d", &r);
    printf("Wpisz ilosc wyrazow ciagu:\t\n");
    scanf("%d", &n);
    
    for (int i = 0; i < n; i++) {
        an = a + r * (n - 1);
        sn = n * (a + an) / 2;
    }

    printf("Suma ciagu arytmetycznego jest rowna %d", sn);

}*/

/*int main() {
    int sn;
    int n;
    int a;
    int q;
    printf("Wpisz pierwszy wyraz ciagu geometrycznego:\t\n");
    scanf("%d", &a);
    printf("Wpisz roznice ciagu geometrycznego:\t\n");
    scanf("%d", &q);
    printf("Wpisz ilosc wyrazow geometrycznego:\t\n");
    scanf("%d", &n);

    for (int i = 0; i < n; i++) {
        sn = a * (1 - pow(q, n) / (1 - q));
    }

    printf("Suma ciagu geometrycznego jest rowna %d", sn);
}*/


/*int main() {
    int a, b, c;
    int p;
    double P;

    srand(time(0));
    a = rand() % 20 + 11;
    b = rand() % 20 + 11; //Znaleść sposób by rozdzielić na dwie funkcje z czego jedna jest zwracająca.
    c = rand() % 20 + 11;

    p = (a + b + c) / 2;
    P = sqrt(p * (p - a) * (p - b) * (p - c));

    printf("Pole trojkata to: %lf", P);
}*/


