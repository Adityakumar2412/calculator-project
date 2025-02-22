#include<iostream>
using namespace std;

int main (){
int num1 , num2 ; char symbol ;

cout<<"enter a symbol (+,*,/,-) = ";
cin>>symbol;

cout<<"enter a first number = "; 
cin>>num1;

cout <<"enter a second number = "; 
cin>>num2;

switch(symbol){
case '+' : cout<<"sum is = "<<num1 + num2 ; 
break;
case '-' : cout<<"sub is = " << num1 - num2 ; 
break;
case '*' : cout<<"munitply is = "<<num1 * num2 ; 
break;
case '/' : cout<<"divied is = "<<num1 / num2 ; 
break;
default : cout<<"";

}
return 0 ;
}
