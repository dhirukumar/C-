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




