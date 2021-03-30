#include <iostream>
#include <math.h>

bool realsqrt(int n)
{
    int r = sqrt(n);
    return (pow(r,2) == n);
}
 

bool isFib(int n)
{
    
    return (realsqrt(5*n*n + 4) || realsqrt(5*n*n - 4));
}


int main()
{
  for (int i = 90; i <= 100; i++)
    if (isFib(i)){
        std::cout << i << " is a Fibonacci Number \n";
    }
    else
    {
        std::cout << i << " is a not Fibonacci Number \n" ;
    }
  return 0;
}
