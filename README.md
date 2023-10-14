// Print all the odd numbers from 1 to 100.
#include <iostream>
using namespace std;
int main()
{
    for(int i=1;i<=100;i++){
        cout<<i<<endl;
    }
}


// Print all numbers from 1 to 100 that are divisible by 3
#include<iostream>
using namespace std;
int main(){
    for(int i=1;i<100;i++){
        if(i%3==0) cout<<i<<endl;
    }
}


// Print the table of ‘n’. Here ‘n’ is an integer which the user will input.
#include<iostream>
using namespace std;
int main()
{
    int i,n;
    cout<<"Enter a Number For Table : ";
    cin>>n;
    for(i=1;i<=10;i++)
    {
      cout<<n*i<<endl;
    }
}


// Display this AP - 4,7,10,13,16.. upto ‘n’ terms.
#include <iostream>
using namespace std;
int main()
{
   int a=4,n;
   cout<<"Enter Number : ";
   cin>>n;
   for (int i=1;i<=n;i++)
   {
       cout<<a<<endl;
       a = a + 3;
   }
}


//Display this GP - 3,12,48,.. upto ‘n’ terms
#include <iostream>
using namespace std;
int main()
{
  int a=3,i,n;
  cout<<"Enter Number : ";
  cin>>n;
  for(i=1;i<=n;i++)
  {
      cout<<a<<endl;
      a = a * 4;
  }
}

//Write a program to print all the ASCII values and their equivalent characters of 26 alphabets using a while loop.
#include <iostream>
using namespace std;
int main()
{
    int i,n=65;
    while(n<=122)
    {
        cout<<n<<char(n)<<endl;
        n++;
    }
}
