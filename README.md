 #include <stdio.h>
int main() {
    int a = 10;      // Assignment operator (=)
    printf("Initial value of a = %d\n", a);
    a += 5;          // Compound addition
    printf("After a += 5, a = %d\n", a);
    a -= 3;          // Compound subtraction
    printf("After a -= 3, a = %d\n", a);
    a *= 2;          // Compound multiplication
    printf("After a *= 2, a = %d\n", a);
    a /= 4;          // Compound division
    printf("After a /= 4, a = %d\n", a);
    a %= 3;          // Compound modulus
    printf("After a %%= 3, a = %d\n", a);
    return 0;
}
