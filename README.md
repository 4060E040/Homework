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
###### exercise1

```


```
###### exercise1

```


```
