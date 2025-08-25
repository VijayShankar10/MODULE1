## Ex.No: 1  
Write a C++ Program to display the following pattern using inline function.  

**Date:**  

### Aim:  
To write a program that displays a right-angled triangle star pattern using an inline function.

### Algorithm:  
1. Start the program.  
2. Initialize `n` as the number of rows.  
3. Define an inline function to print the pattern.  
4. Use nested loops:  
   - Outer loop controls the number of rows.  
   - Inner loop prints stars decreasing each row.  
5. End the program.  

### Program:
```cpp
#include <iostream>
using namespace std;

inline void pattern(int n) {
    for (int i = n; i >= 1; i--) {
        for (int j = 1; j <= i; j++) {
            cout << "*";
        }
        cout << endl;
    }
}

int main() {
    int n;
    cin >> n;
    pattern(n);
    return 0;
}
```

### Output:
```cpp
Input: 4
****
***
**
*

```

### Result:

<img width="1167" height="330" alt="image" src="https://github.com/user-attachments/assets/a25b109e-b495-406b-a260-9376fd222d03" />




