# Ex 1
EX.NO : 1(A)                                      OVERVIEW AND STRUCTURE
DATE : 
PROGRAM STATEMENT:

To write a c++ program to display "Hello World" in first line and "Welcome to C++ Programming” in next line into the output device.

ALGORITHM:

1.	Start the program.
2.	Include necessary header files for input/output operations.
3.	Define the main function.
4.	Print "Hello World" with a newline.
5.	Print "Welcome to C++ Programming".
6.	End the program.

PROGRAM:  
```
#include <iostream> 
using namespace std; 
int main()
{
cout<<"Hello World"<<endl; cout<<"Welcome to C++ Programming";

}
```

OUTPUT :

![image](https://github.com/user-attachments/assets/405fef87-0baf-458b-a5a1-d51e091162b6)

RESULT :
Thus, the c++ program to display "Hello World" in first line and "Welcome to C++ Programming” in next line into the output device is implemented successfully.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

EX.NO : 1(B)                       CLASS SCOPE AND ACCESSING CLASS MEMBERS & REFERENCE VARIABLES
DATE : 

PROGRAM STATEMENT :

To write a program in C++ to calculate the volume of a cube(declare side as private member ) using class methods.

ALGORITHM :

1.	Start the program.
2.	Define a Cube class with private side variable and public methods to set the side length and calculate the volume.
3.	In main, read the side length, create a Cube object, set the side, calculate the volume, and print it.
4.	End the program.

PROGRAM :
```
#include <iostream> using namespace std; class Cube{
private:
int side;

public:
void setmember(int s)
{
side=s;
}
int calculate()
{
return side*side*side;
}
};
int main()
{
int sidee; cin>>sidee; Cube cube;
cube.setmember(sidee); int three=cube.calculate();
cout<<"The Volume of Cube is:"<<three;
}
```
OUTPUT :

![image](https://github.com/user-attachments/assets/324ea031-f19d-4d33-beaf-719bf2ad0ded)


RESULT :
Thus, the C++ Program to calculate the volume of a cube(declare side as private member ) using class methods created successfully.




![image](https://github.com/user-attachments/assets/3983f679-1680-4537-a9e0-ecda8bdce84d)


![image](https://github.com/user-attachments/assets/46bd987c-ba14-410c-b4bc-90ec5483fee6)

![image](https://github.com/user-attachments/assets/9aa1ae16-099d-4a92-a258-09ef69eb5f6c)

![image](https://github.com/user-attachments/assets/78905f49-4492-4a3f-ae18-3e9cc9f6122f)

