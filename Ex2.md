# Ex.No2
## Ex.Name: Write a C++ program to find the sum of GP series using friend function.
## Date:

## Aim:
To compute the sum of a Geometric Progression series using a friend function.

## Algorithm:
1. Start the program.
2. Read first term a, common ratio r, and number of terms n.
3. Use the formula Sn = a * (pow(r, n) - 1) / (r - 1).
4. Define a class and declare a friend function to compute sum.
5. Display the result.
6. End program.

## Program:
```cpp
#include <iostream>
#include <cmath>
using namespace std;

class GP {
    int a, r, n;
public:
    GP(int x, int y, int z) {
        a = x; r = y; n = z;
    }
    friend void sumGP(GP g);
};

void sumGP(GP g) {
    long long sum;
    sum = g.a * (pow(g.r, g.n) - 1) / (g.r - 1);
    cout << "The sum of GP series is " << sum;
}

int main() {
    int a, r, n;
    cin >> a >> r >> n;
    GP g(a, r, n);
    sumGP(g);
    return 0;
}
```


## Output:
```
Input: 2 2 6
The sum of GP series is 126
```

## Result:
<img width="1176" height="541" alt="image" src="https://github.com/user-attachments/assets/45cd806f-a09a-4787-84b1-d51ec9368259" />
