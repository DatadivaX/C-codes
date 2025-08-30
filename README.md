Single inheritance

#include<iostream>
using namespace std;
class Vehicle
{
    public:
     void start()
     {
         cout<<"Vehicle started"<<endl;
     }
};
class Car:public Vehicle
{
    public:
    void drive()
    {
        cout<<"Car is driving"<<endl;
    }
};
int main()
{
    Car mycar;
    mycar.start();
    mycar.drive();
    return 0;
}

OUTPUT:
Vehicle started
Car is driving


=== Code Execution Successful ===

Multi level inheritance

#include <iostream>
using namespace std;
class Animal
{
    public:
    void speak()
    {
        cout<<"Animal speaks";
    }
};
class Dog:public Animal
{
    public:
    void bark()
    {
        cout<<"Dog barks";
    }
};
class Puppy:public Dog
{
    public: 
    void weep()
    {
        cout<<"Puppy weeps";
    }
};
int main()
{
    Puppy p1;
    p1.weep();
}
Output
Puppy weeps

=== Code Execution Successful ===


Multiple level inheritance

#include <iostream>
using namespace std;

class Animal
 {
     public:
     void eat()
     {
         cout<<"Eating food...."<<endl;
     }
 };
 class bird
 {
     public:
     void fly()
     {
         cout<<"Bird is flying"<<endl;
     }
 };
 class Bat: public nimal,public bird
 {
     public:
     void sound()
     {
         cout<<"Bird is making a sound"<<endl;
     }
 };
 int main()
 {
     Bat b;
     b.eat();
     b.fly();
     b.sound();
     return 0;
 }

Output:
Eating food....
Bird is flying
Bird is making a sound


=== Code Execution Successful ===

