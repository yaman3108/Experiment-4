# EXPERIMENT 4



## Aim:
To demonstrate the use of bitwise operators in C++.


## Apparatus:
Vs Code, Github


## Theory:
Bitwise operators in C++ perform operations in the binary form of integers. These operators can be useful in optimization and situations where performance and memory usage are critical. Here's an overview of common bitwise operators:

### Bitwise AND (&):
Performs a bitwise AND operation between two integers. If both the bits are 1 then the result of the operation is 1 otherwise the result bit is 0.

### Bitwise OR (|):
Performs a bitwise OR operation.If atleast one of the bits is 1 then the result of the operation is 1.

### Bitwise XOR (^):
Performs a bitwise XOR (exclusive OR) operation. If both the bits are different the result of the operation is 1 otherwise the result bit is 0.

### Bitwise NOT (~):
Performs a bitwise NOT operation, also known as bitwise complement. It inverts all the bits. The result of the bit is complimentary to itself, for example if a bit is 1 its result bit is 0.

### Left Shift (<<):
Shifts the bits of the left operand to the left by the number of positions specified by the right operand. New bits on the right are set to 0.

### Right Shift (>>):
Shifts the bits of the left operand to the right by the number of positions specified by the right operand. The behavior of the leftmost bits depends on whether the type is signed or unsigned.


## Explanation: 
This program covers the basic bitwise operators such as AND, OR, XOR, NOT, Left shift, Right shift. We give two inputs and demonstrate how these bitwise operations function and print thier result.


## Code:
```
#include<iostream>
using namespace std;

//Name: Yaman Hasan Ansari PRN:23070123155

int main()
{
    int a = 5;
    int b = 3;
    int AND = a&b;
    int OR = a|b;
    int XOR = a^b;
    int NOT = ~a;
    int LEFT_SHIFT = a<<b;
    int RIGHT_SHIFT = a>>b;
    
    cout<<"AND:"<<AND<<endl;
    cout<<"OR:"<<OR<<endl;
    cout<<"XOR:"<<XOR<<endl;
    cout<<"NOT:"<<NOT<<endl;
    cout<<"LEFT_SHIFT:"<<LEFT_SHIFT<<endl;
    cout<<"RIGHT_SHIFT:"<<RIGHT_SHIFT<<endl;

  return 0;
}
```

## Output:
![Screenshot 2024-07-30 142241](https://github.com/user-attachments/assets/63b966cf-5d42-40aa-bb87-975a901e47a3)


## Conclusion:
This program helps us understand how bitwise operators can be used in C++. These bitwise operations can be used for performance optimization as they pack multiple values in a single variable making the program more memory efficient.
