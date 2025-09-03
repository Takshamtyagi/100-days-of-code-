//day2 q1 - Write a program to calculate the area and perimeter of a rectangle given its length and breadth

#include <stdio.h>

int main() {
    float length,breadth;
    printf("enter length: ");
    scanf("%f",&length);
    printf("enter breadth: ");
    scanf("%f",&breadth);
    float Area = length * breadth;
    float perimeter = 2 * (length + breadth);
    printf("AREA: %f",Area );
   printf("\nPERIMETER : %f",perimeter);

    return 0;
}
