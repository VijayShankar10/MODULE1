# Ex.No5
## Ex.Name: Write a C++ program to display the polynomial equation using constructor overloading.
## Date:

## Aim:
To display polynomial equations using constructor overloading.

## Algorithm:
1. Start the program.  
2. Define a class with constructor overloading.  
3. Constructor with 2 arguments prints linear equation.  
4. Constructor with 3 arguments prints quadratic equation.  
5. Create objects and call appropriate constructors.  
6. Display the result.  
7. End the program.  

## Program:
```cpp
#include <iostream>
using namespace std;

class Polynomial {
public:
    Polynomial(int a, int b) {
        cout << a << "x+" << b << endl;
    }
    Polynomial(int a, int b, int c) {
        cout << a << "x^2+" << b << "x+" << c << endl;
    }
};

int main() {
    Polynomial p1(95, 64);
    Polynomial p2(22, 28, 21);
    return 0;
}
```


## Output:
<img width="1175" height="290" alt="image" src="https://github.com/user-attachments/assets/a457bc5e-1de3-4347-a75a-857e234ad31d" />

## Result:
```
95x+64
22x^2+28x+21
```
