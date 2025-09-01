# Ex.No2
## Ex.Name: Write a C++ program to find the sum of GP series using friend function.
## Date:

## Aim:
To compute the the sum of AP series using friend function.

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
using namespace std;
class student
{
    public:
    int apseries(int a,int n,int d)
    {
        return a+(n-1)*d;
    }

};
int main()
{
    int a,n,d;
    cin>>a>>n>>d;
    student g;
    cout<<"the sum is "<<g.apseries(a,n,d);
}
```

## Output:
<img width="1176" height="541" alt="image" src="https://github.com/user-attachments/assets/45cd806f-a09a-4787-84b1-d51ec9368259" />


## Result:
```
Input: 2 2 6
The sum of GP series is 126
```
