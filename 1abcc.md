## EX.NO : 1(A)                                      
## OVERVIEW AND STRUCTURE
## DATE : 
### PROGRAM STATEMENT:
To write a c++ program to display "Hello World" in first line and "Welcome to C++ Programming” in next line into the output device.

### ALGORITHM:

1.	Start the program.
2.	Include necessary header files for input/output operations.
3.	Define the main function.
4.	Print "Hello World" with a newline.
5.	Print "Welcome to C++ Programming".
6.	End the program.

### PROGRAM:  
```
#include <iostream> 
using namespace std; 
int main()
{
cout<<"Hello World"<<endl; cout<<"Welcome to C++ Programming";

}
```

### OUTPUT :

![image](https://github.com/user-attachments/assets/ccd7770b-53b5-44b0-979d-c8a412a9e96a)


### RESULT :
Thus, the c++ program to display "Hello World" in first line and "Welcome to C++ Programming” in next line into the output device is implemented successfully.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## EX.NO : 1(B)                       
## CLASS SCOPE AND ACCESSING CLASS MEMBERS & REFERENCE VARIABLES
## DATE : 

### PROGRAM STATEMENT :

To write a program in C++ to calculate the volume of a cube(declare side as private member ) using class methods.

### ALGORITHM :

1.	Start the program.
2.	Define a Cube class with private side variable and public methods to set the side length and calculate the volume.
3.	In main, read the side length, create a Cube object, set the side, calculate the volume, and print it.
4.	End the program.

### PROGRAM :
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
### OUTPUT :

![image](https://github.com/user-attachments/assets/39912b5b-ce24-437d-9751-ca4ecf22969b)

### RESULT :
Thus, the C++ Program to calculate the volume of a cube(declare side as private member ) using class methods created successfully.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## EX.NO : 1(C)                                  
## C++ CONSTRUCTORS AND DESTRUCTORS
## DATE 

### PROGRAM STATEMENT :
To write a C++ program to display "Im a default constructor" using a default constructor

### ALGORITHM:

1.	Start the program.
2.	Define a class Cont with a default constructor that prints "I'm a default constructor".
3.	In the main function, create an object c of class Cont, which calls the default constructor and displays the message.
4.	End the program.

### PROGRAM :
```
#include<iostream> 
using namespace std; 
class Cont
{
public:
Cont ()
{
cout<<"Im a default constructor";
}
};
int main()
{
Cont c; return 0;
}
```
### OUTPUT :

![image](https://github.com/user-attachments/assets/4c93eb6a-6b3e-4524-a1ae-3ef98dd63f4c)

### RESULT :
Thus, the C++ program to display "Im a default constructor" using a default constructor is created successfully.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## EX.NO : 1(D)                                                 
## C++ MEMBER FUNCTION
## DATE :

### PROGRAM STATEMENT :
To write a C++ program to convert Celsius into Fahrenheit using inline function

### ALGORITHM :

1.	Start the program.
2.	Define an inline function convertToFahrenheit that takes a float celsius as input and returns the Fahrenheit equivalent using the formula (celsius * 9.0 / 5.0) + 32.
3.	In the main function, declare a float variable celsius to store the temperature.
4.	Read the Celsius temperature from the user and store it in celsius.
5.	Call the convertToFahrenheit function with celsius as the argument and store the result in the fahrenheit variable.
6.	Print the converted temperature in Fahrenheit.
7.	End the program.

### PROGRAM :
```
#include <iostream> 
using namespace std;

// Inline function to convert Celsius to Fahrenheit 
inline float convertToFahrenheit(float celsius) {
return (celsius * 9.0 / 5.0) + 32;
}

int main() 
{ 
float celsius;

// Get the Celsius temperature from the user
//cout << "Enter temperature in Celsius: "; cin >> celsius;

// Convert the temperature to Fahrenheit
float fahrenheit = convertToFahrenheit(celsius);
// Display the result
cout << "temperature in Fahrenheit:" << fahrenheit << endl;
 return 0;
}
```
### OUTPUT :

![image](https://github.com/user-attachments/assets/4880e144-e2e1-42c7-81a7-1bf3ab39d01d)

### RESULT :
Thus, the C++ program to convert Celsius into Fahrenheit using inline function is implemented successfully.
