# Ex8 Deque
## DATE:
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1. Initialize a counter to 0.
2. Check if the deque is empty.
3. Traverse the deque from front to rear (for array) or from head node till the end (for linked list).
4.  Increment the counter for each element encountered.
5.  Increment the counter for each element encountered. 

## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: Nandhana R
RegisterNumber:212223040124
*/
/*#include <stdio.h> #define MAX 10
void addFront(int *, int, int *, int *); void addRear(int *, int, int *, int *); int delFront(int *, int *, int *); intdelRear(int *, int *, int*);
void display(int *); int count(int *);
*/
int count(int *arr) { int c = 0, i; for(i=0;i<MAX;i++)
{
if(arr[i]!=0)
{
c=c+1;
}
}
return c;
}

/*
Program to count the number of elements present in the deque
Developed by: 
RegisterNumber:  
*/
```

## Output:
![image](https://github.com/user-attachments/assets/696163ea-4321-4c8c-b1cd-f89e83d90ea8)




## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
