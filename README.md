# Codsofttaskno2
This is a code for a calculator program that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.It allows the user to input two numbers and choose an operation to perform.
#include<iostream>
#include <cstdlib>
using namespace std;
int main()
{
 double num1;
 double num2;
 char opr;
 cout<<"Enter your first number"<<endl;
 cin >>num1;
 cout<<"Enter your second number"<<endl;
 cin>>num2;
cout <<"Select an operation"<<endl;
cout<<"+"<<endl;
cout<<"-"<<endl;
cout<<"/"<<endl;
cout<<"*"<<endl;
cin>>opr;
if (opr == '+' )
{
    double num=num1+num2;
   cout<<"Your answer is "<< num;
}
else if (opr == '-')
{
  double num=num1-num2;
  cout<<"Your answer is "<< num;
}
else if (opr == '/')
{
    double num=num1/num2;
    cout<<"Your answer is "<< num;
}
else if (opr == '*')
{
    int num=num1*num2;
    cout<<"Your answer is "<< num;
}
else
{
    cout<<"invalid operation selected";
}

return 0;
}
