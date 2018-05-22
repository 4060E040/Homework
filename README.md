# Homework

###### exercise1

```
ex.array_1:(2018.4.17)

#include <iostream>
#include <iomanip>
using namespace std;
int fun(int array[3][3])
{
	int i,j,t;
	for(i=0;i<3;i++)
		for(j=0;j<i;j++)
		{
			t=array[i][j];
			array[i][j]=array[j][i];
			array[j][i]=t;
		}
		return 0;
}
int main()
{
	int i,j;
	int array[3][3]={{1,2,3},{4,5,6},{7,8,9}};
	cout << "Converted Front" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
	fun(array);
	cout << "Converted result" <<endl;
	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
			cout << setw(7) << array[i][j] ;
		cout<< endl;
	}
    return 0;
}

![image](https://github.com/4060E040/Homework/blob/master/PIC/work.png)



```
###### exercise1

```
4/22

定義:Circle.h

class Circle
{
public:
  // The radius of this circle
  double radius;

  // Construct a default circle object
  Circle();

  // Construct a circle object
  Circle(double);

  // Return the area of this circle
  double getArea();
};


實作:Circle.cpp

#include "Circle.h"

// Construct a default circle object
Circle::Circle()
{
  radius = 1;
}

// Construct a circle object
Circle::Circle(double newRadius)
{
  radius = newRadius;
}

// Return the area of this circle
double Circle::getArea()
{
  return radius * radius * 3.1415;
}

主執行程式:

#include <iostream>
#include "Circle.h"
using namespace std;

int main()
{
  Circle circle1;
  Circle circle2(5.0);

  cout << "The area of the circle of radius "
    << circle1.radius << " is " << circle1.getArea() << endl;
  cout << "The area of the circle of radius "
    << circle2.radius << " is " << circle2.getArea() << endl;

  // Modify circle radius
  circle2.radius = 100;
  cout << "The area of the circle of radius "
    << circle2.radius << " is " << circle2.getArea() << endl;

  return 0;
}

```
###### exercise1

```

5/8

#include <iostream>
using namespace std;

int main()
{
  string s1("Welcome");
  s1.append(" to CPP"); 
  cout << s1 << endl; 
  
  string s2("Welcome");
  s2.append(" to C and C++", 0, 5); // appends " to C" to s2
  cout << s2 << endl; // s2 now becomes Welcome to C

  string s3("Welcome");
  s3.append(" to C and C++", 5); // appends " to C" to s3
  cout << s3 << endl; // s3 now becomes Welcome to C

  string s4("Welcome"); 
  s4.append(4, 'G'); // appends "GGGG" to s4
  cout << s4 << endl; // s4 now becomes WelcomeGGGG

  return 0;
}

```
###### exercise1

```

5/22

#ifndef STACK_H
#define STACK_H

template<typename T>
class Stack
{
public:
  Stack();
  bool empty() const;
  T peek() const;
  void push(T value);
  T pop();
  int getSize() const;

private:
  T elements[200];
  int size;
};

template<typename T>
Stack<T>::Stack()
{
  size = 0;
}

template<typename T>
bool Stack<T>::empty() const
{
  return (size == 0);
}

template<typename T>
T Stack<T>::peek() const
{
  return elements[size - 1];
}

template<typename T>
void Stack<T>::push(T value)
{
  elements[size++] = value;
}

template<typename T>
T Stack<T>::pop()
{
  return elements[--size];
}

template<typename T>
int Stack<T>::getSize() const
{
  return size;
}

```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
###### exercise1

```


```
