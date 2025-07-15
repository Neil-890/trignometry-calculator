# trignometry-calculator
#include <stdio.h>
#include <math.h>  // Required for trig functions

#define PI 3.14159265  // Define the value of pi

int main() {
    double angle, radian;

    printf("Enter angle in degrees: ");
    scanf("%lf", &angle);

    // Convert degree to radian
    radian = angle * (PI / 180);

    // Calculate trigonometric values
    printf("\n--- Trigonometric Values ---\n");
    printf("sin(%.2lf) = %.4lf\n", angle, sin(radian));
    printf("cos(%.2lf) = %.4lf\n", angle, cos(radian));
    printf("tan(%.2lf) = %.4lf\n", angle, tan(radian));

    return 0;
}
