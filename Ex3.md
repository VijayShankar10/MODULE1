# Ex.No3
## Ex.Name: Write a program in C++ to compute quotient and remainder using class methods.
## Date:

## Aim:
To compute quotient and remainder using class methods defined outside the class.

## Algorithm:
1. Start the program.
2. Define class with two integers as input.
3. Create methods for quotient and remainder.
4. Define methods outside the class.
5. Display the result.
6. Display results.

## Program:
```cpp
#include <iostream>
using namespace std;

class Division {
    int a, b;
public:
    Division(int x, int y) { a = x; b = y; }
    int getQuotient();
    int getRemainder();
};

int Division::getQuotient() { return a / b; }
int Division::getRemainder() { return a % b; }

int main() {
    int x, y;
    cin >> x >> y;
    Division d(x, y);
    cout << "The quotient of the division is:" << d.getQuotient() << endl;
    cout << "The remainder of the division is:" << d.getRemainder();
    return 0;
}
```

## Output:
<img width="1175" height="427" alt="image" src="https://github.com/user-attachments/assets/5331e859-ee88-418a-8fe9-118b5f4c5770" />

## Result:
```
Input: 50 4
The quotient of the division is:12
The remainder of the division is:2
```
