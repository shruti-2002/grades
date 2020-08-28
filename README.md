#include <stdio.h>

int main()
{
    float marks;
    char grade;

    printf("Enter marks: ");
    scanf("%f", &marks);

    if(marks >= 90)
    {
        grade = 'A';
    }
    else if(marks >=85 && marks < 100)
    {
        grade = 'B';
    }
    else if(marks >= 70 && marks < 85)
    {
        grade = 'C';
    }
    else if(marks >= 55 && marks < 70)
    {
        grade = 'D';
    }
    else if(marks >= 40 && marks < 55)
     {
        grade = 'F';
    }
    else if (marks >40);

    printf("Your grade is %c", grade);

    return 0;
}


