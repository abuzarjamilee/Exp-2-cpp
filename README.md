AIM: -
To study and implement C++ Program Structure (Data Types)

Theory: -
In C++, variables are declared using data type to restrict storage type. 
The compiler allocates memory based on the data type, which requires different memory allocations. 
C++ supports various data types, including Character (char), Integer (int), Boolean (bool), Floating point (float),
Double Floating point (double), Void (), and Wide Character sizeof() operator. These data types can have modifiers, such as Short Long 
Signed Unsigned, which can increase or decrease the variable's size. For example, Long can extend an integer to 4 bytes. The storage representation
and machine instructions for each data type differ from machine to machine.

code //Abuzar 
//23070123158
#include<iostream>
using namespace std;
int main(){
    int a,b,c,add,sub;
    int div,prod,mod;

    cout<<"Enter the value for A"<<endl;
    cin>>a;
    cout<<"Enter the value for B"<<endl;
    cin>>b;

    if(b>0 && b<200  && a>0 && a<250){
     //COMPARISON OPERATOR & LOGICAL OPERATORS

         add=a+b;   //ARITHMETIC OPERATORS 
         sub=a-b;   
         div=a/b;    
         prod=a*b;  
         mod=a%b;   

       
         ++a;       //INCREMENT OPERATOR
         --b;       //DECREMENT OPERATOR
         

    

    cout<<"Sum of the entered value is "<<add<<endl<<endl;        
    cout<<"Difference of the entered value is "<<sub<<endl<<endl;
    cout<<"Division of the entered value is "<<div<<endl<<endl;
    cout<<"Product of the entered value is "<<prod<<endl<<endl;
    cout<<"Modulus of the entered value is "<<mod<<endl<<endl;
   
    cout<<"Incremented A is "<<a<<endl<<endl;
    cout<<"Decremented B is "<<b<<endl<<endl;
    }
  
    else{
        cout<<endl<<"CHECK THE VALUES OF A AND B, IT SHOULD BE LESS THAN 250(for A) AND 200(for B)"<<endl;
        cout<<"                                    or"<<endl;
        cout<<"               ENTER NON-ZERO NUMBER FOR THE VALUE OF A and B"<<endl<<endl<<endl<<endl;
    }; //COMPARISON OPERATOR

    return 0;
}

outpute of code :-![image](https://github.com/user-attachments/assets/b3820b37-5f32-4cec-a5f7-8bdcc25fed3b)
