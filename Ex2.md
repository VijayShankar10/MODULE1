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
<img width="694" height="521" alt="image" src="https://github.com/user-attachments/assets/aa617712-2565-4671-a6b3-c624c303e398" />



## Result:
```
Input: 1 100 5
The sum is 496
```
