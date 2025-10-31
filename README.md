\t\t\t\tCoumpound-Assignmet
<br><br>
This my first attempt in github.
<br><br>
#include <stdio.h>
<br>
int main() {
<br>
int a = 10;      // Assignment operator (=)
<br>
    printf("Initial value of a = %d\n", a);
<br>
    a += 5;          // Compound addition
<br>
    printf("After a += 5, a = %d\n", a);
<br>
    a -= 3;          // Compound subtraction
<br>
    printf("After a -= 3, a = %d\n", a);
<br>
    a *= 2;          // Compound multiplication
<br>
    printf("After a *= 2, a = %d\n", a);
<br>
    a /= 4;          // Compound division
<br>
    printf("After a /= 4, a = %d\n", a);
<br>
    a %= 3;          // Compound modulus
<br>
    printf("After a %%= 3, a = %d\n", a);
<br>
    return 0;
}
