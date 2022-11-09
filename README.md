# c-programs
all c++ programs


function pointer 
*******************************************************************************/

#include <iostream>

using namespace std;
int add(int a,int b){
    return a+b;
}

int main()
{
    int (*fptr)(int,int);

    fptr=add;
  int sum;
  sum=fptr(5,8);
  cout<<sum;

    return 0;
}
