# The-sum-of-cubes-
//Calculate the sum of cubes of the entered number
#include <stdio.h>
#include <conio.h>
int main()
{
    int sum=0,i,num;
    printf("Enter the number: ");
    scanf("%d",&num);
    for(i=1;i<=num;i++)
        sum=sum+pow(i,3);
    printf("Sonuc: %d",sum);


}
