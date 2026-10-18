
#include <stdio.h>

int main()
{
    float km;
    printf("Enter distance in kilometres: ");
    scanf("%f", &km);

    printf("Metres = %.2f\n", km * 1000);
    return 0;
}
