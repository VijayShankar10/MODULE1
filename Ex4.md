# Ex.No4
## Ex.Name: Write a C++ program to generate even numbers from 1 to n using class.
## Date:

## Aim:
To generate even numbers from 1 to n using class.

## Algorithm:
1. Start the program.  
2. Define a class with a member function `generateEven()`.  
3. Read the input value `n`.  
4. Loop from 1 to n and print numbers divisible by 2.  
5. Display the result.  
6. End the program.  

## Program:
```cpp
#include <iostream>
using namespace std;

class EvenNumbers {
public:
    void generateEven(int n) {
        cout << "Even Numbers are:";
        for (int i = 2; i <= n; i += 2) {
            cout << " " << i;
        }
    }
};

int main() {
    int n;
    cin >> n;
    EvenNumbers obj;
    obj.generateEven(n);
    return 0;
}
```
## Output:
```
Input: 8
Even Numbers are: 2 4 6 8
```
## Result:
<img width="1192" height="374" alt="image" src="https://github.com/user-attachments/assets/736bc154-3176-480e-b57a-9561434d413d" />
