# day 1

#include<iostream>

using namespace std;

namespace firest

{ //this place we use namespace for same identifire like :-show

  void show()
  
  {
        cout<<"dhiru\n";
  }
  
}

namespace second

{//this place we use namespace for same identifire like :-show

  void show()
  
  {
        cout<<"kalu"<<endl;
   }
   
// int a=200;//global a

}

int main()

 {   firest::show();//call firest show
 
  second::show();//cll second show
  
  //int a = 100;
  
//     cout<<"enter your number"<<endl;//output 

//     cin>>a;//after output you will get option to enter

//     cout<<::a<<endl;//:: for global output (200)

//     cout<<a;// print normally (100) for function a 
   
}

# day 2

 #include<iostream>
 
using namespace std;

int main()

{
  int a=10;// int is compulsery in this place because  C++ is statically language 
    
  cout<<a;
  
}

## in dynimacally language 

a = 10 // in this place we dont need to write the datatype because it a dynamically language

print(a)

# day 3

#include <iostream>

using namespace std;

int main()

{
    int a=10;
    
  string b="ddddd";
    
  bool c=20;
  
  double d =10.22;
  
  char e='d';
  
  cout<<a<<endl<<b<<endl<<c<<endl<<d<<endl<<e<<endl;
  
  cout<<sizeof(int)<< " bytes"<<endl;
  
   cout<<sizeof(string)<< " bytes"<<endl;
   
   cout<<sizeof(bool)<< " bytes"<<endl;
   
  cout<<sizeof(double)<< " bytes"<<endl;
  
  cout<<sizeof(char)<< " bytes"<<endl;
    }

# day 5

#include <iostream>

using namespace std;

#include <typeinfo>

int main()

{
    int a=10;
    
   bool b= a;
   
   cout<<sizeof(b)<<endl;
   
   cout<<sizeof(a)<<endl;
   
   cout<<typeid(a).name()<<endl<<typeid(b).name();

    }

# day 6

#include <iostream>

using namespace std;


void myfam(){  //myfam is identifier in this function

  cout<<"dhiru\n";
}

int main(){  

  string a="ok";  //a is idntifier 
  
  myfam();        //we call myfam function here
  
  cout<<a<<endl;
  
  myfam();
  
  myfam();
  
}

# day 7

#include <iostream>

using namespace std;


int main(){

  int a;
    
   cout<<"enter the number"<<endl;
    
  cin>>a;


  if(a>=10){
  
  cout<<"dhiru";

  }
    else{
    
  cout<<"kalu";
  
   }
}

# day 8

#include <iostream>

using namespace std;


int main(){

  for(int a=1;a<=100;++a)
  
   {    cout<<a<<endl;
   
  }
  
  int a=10;
  
  
  //this both code genrate same output one by for method and another is by while methode
 
  while(>0){
  
  cout<<a;

  ++a;

  }
    
}

# day 9

#include <iostream>

using namespace std;





int main(){

  int a=4,b=15;
  
   cout<<a+b<<endl;
   
   cout<<a-b<<endl;
   
   cout<<a*b<<endl;
   
   cout<<a/b<<endl;
   
   cout<<a%b<<endl;
   
   cout<<(a>b)<<endl; //IT GIVES OUTPUT IN 0 OR 1 BECAUSE CONDITION IS TRUE THEN 1 ELASE 0
   
   cout<<(a<b)<<endl;//IT GIVES OUTPUT IN 0 OR 1 BECAUSE CONDITION IS TRUE THEN 1 ELASE 0
   
   cout<<(a>=b)<<endl;//IT GIVES OUTPUT IN 0 OR 1 BECAUSE CONDITION IS TRUE THEN 1 ELASE 0
   
   cout<<(a<=b)<<endl;//IT GIVES OUTPUT IN 0 OR 1 BECAUSE CONDITION IS TRUE THEN 1 ELASE 0
   
   cout<<(a!=b)<<endl;//IT GIVES OUTPUT IN 0 OR 1 BECAUSE CONDITION IS TRUE THEN 1 ELASE 0
   
   cout<<(a==b)<<endl;//IT GIVES OUTPUT IN 0 OR 1 BECAUSE CONDITION IS TRUE THEN 1 ELASE 0
   
   cout<<(a<b && a>b)<<endl;
   
   cout<<(a<b || a>b)<<endl;
   
   cout<<!(a<b)<<endl;
   
   cout<<++a<<endl; //it added 1 in a=6
   
   cout<<a++<<endl; //it added 1 in a mean previous a so it take value of a is 6 but it printed 6  firest but in computer it mens 7
   
   cout<<--a<<endl; // as i say previous a is 7 it subtracte 1 from a =7-1=6
   
   cout<<a--<<endl; // this is same like a++ it sub but is printed previous number that 6 but in computer it is 5
   
   cout<<a<<endl; // for check computer value then i print a so it gives 5 as previous no
   
   cout<<(a>b?a:b); // in this place it show a>b or not if yea then it printed the grater number if not then it printed opposite number
   
   cout<<(a&b)<<endl; // if both are true by breaking the number in bits 
   
   cout<<(a|b)<<endl; // if one of these true by breaking the number in bits 
   
   cout<<(a^b)<<endl; //if both are false by breaking the number in bits 
   
<img width="707" alt="Screenshot 2024-06-25 at 3 26 39 PM" src="https://github.com/dhirukumar/C-/assets/146316525/d766999f-735f-48c5-b206-9687ff793137">

  }

# day 10

#include <iostream>

using namespace std;

int main(){

   for (int i=1;i<=2;++i)
    
  {
    
   cout<<"dhiru"<<endl;

  }
    
  int  i=10;  
  while(i>=10){ // it runs infinite 
  
  cout<<i<<endl;
        
  i++;
        
  }
  do{  //if condition is true then it runs untill condition id done
    
  cout<<i<<endl;
        
 i++;
        

  }
  while(i>11); // if condition is false then it runs only one time

   }

# day 11

#include <iostream>

using namespace std;

int main(){

   int pwd=1111;
   
   int mypwd;
   
   cout<<"enter your password";
   
   cin>>mypwd;
   
   while (mypwd>0){
   
  if(pwd==mypwd){
  
  cout<<"unlock\n";
  
  cout<<"welcome";   
  
  return 0; //also we can use break;
  
   }
    
   else{
    
   cout<<"your password is wrong plese enter again\n";
   
  cout<<"enter your password";
  
   cin>>mypwd;
   
   

}
    
   }
   
 }

# day 12

#include <iostream>

using namespace std;

int main(){
    
 string name;   
 
 cout<<"enter your name=";
 
   cin>>name;

  do{
  
  cout<<name;
  

  }  
  
  while(name=="dhiru");
   
  }


# day 13

#include <iostream>

using namespace std;

int main(){
    
   int num;
   
   cout<<"enter the number ";
   
   cin>>num;
   
   cout<<"multiplication of "<<num<<endl;

   for(int i=1;i<=10;++i)
   
   {
   
   cout<<num<<"x"<<i<<"="<<num*i<<endl;
   
   }
   
  }

# day 14

#include <iostream>

using namespace std;

int main(){
    
  string name;
  
  cout<<"enter your name=";
  
  cin>>name;

  if(name=="kalu"){
  
  cout<<"you are black mava";
  
  }
 if(name=="dhiru"){

  cout<<"you are very good";
  
  }
   
  
  else{
  
  cout<<"you are good";
    
  }


 }

#   day 15

#include <iostream>

using namespace std;

int main(){

int a;
    
  cout<<"enter your amount\n";
    
  cin>>a;
    
        
  if (a<=100000){
    
   cout<<"you not need to pay any tax\n";
        
  }
    
  else if (a>100000 && a<=500000){
    
   cout<<"you pay 5% tax="<<"tax amount="<<a*5/100;
   
   }
    
  else{
    
 cout<<"you pay 10% tax="<<"tax amount="<<a*10/100;
        
  }
 
 }

 # day 16
 
#include <iostream>

using namespace std;

int main(){

  int age;
  
  cout<<"enter your age\n";
  
  cin>>age;
  
  if(age>=18){
  
 if(age>=18 && age<=59){
    
  cout<<"you can do work\n";
    
  }
    
 else{
    
  cout<<"you are too old to do work\n";
        
  }

  }
  
  else{
  
  cout<<"you are minor\n";
    
  }
 
 }

# day 17

#include <iostream>

using namespace std;

int main(){
 
 int fv,sv;
 
 char sin;
 
 cout<<"enter your firest number=";
 
 cin>>fv;
 
 cout<<"what you want";
 
 cin>>sin;
 
 cout<<"your second number";
 
 cin>>sv;
 
 switch(sin){
 
  case '+':cout<<"sum of your number="<<fv+sv;
  
   break;
   
  case '-':cout<<"subtraction of your number="<<fv-sv;
  
  break; 
  
  case '*':cout<<"multiplay of your number="<<fv*sv;

  
  break; 
  
  case '/':cout<<"divide of your number="<<fv/sv;
  
  break; 
  
  case '%':cout<<"remander of your number="<<fv%sv;
  
   break;
   
 default;cout<<"invalid choice";
 }
 
 }






  



