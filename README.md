#include <stdio.h>
int sod(int x);
int main()
{
int n ;
scanf("%d", &n);
printf("%d", sod(n));
}
int sod(int x)
{
if(x == 0)
return 0 ;
else
return (x%10) + sod(x/10);
}
