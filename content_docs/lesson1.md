# Lesson 1

## Code C++ Syntax
```cpp
#include<iostream>
using namespace std;

int main()
{
    cout << "Hello World" << endl;

    return 0;
}
```

## Data types - Variable - Declaring Variable
int: integer number smaller than $10^9$

long long: integer number smaller than $10^{18}$

float: Stores fractional numbers, containing one or more decimals. Sufficient for storing 6-7 decimal digits

double, long double: Stores fractional numbers, containing one or more decimals. Sufficient for storing 15 decimal digits

char: Stores a single character/letter/number, or ASCII values

string: store a sequence of characters 

```cpp
#include<iostream>
using namespace std;

int main()
{
    int a;
    int b;
    
    cin >> a;
    cin >> b;

    cout << a << endl;

    return 0;
}
```

## If-else statement

```cpp
#include<iostream>
using namespace std;

int main()
{
    int a;
    int b;
    int s = 5;

    cin >> a;
    cin >> b;
    s = a + b;
    if(s > 10)
    {
        cout << "Better than 10";
    }
    else
    {
        cout << "Smaller than 10";
    }

    return 0;
}
```

## For Loop
Base for loop:
```cpp
#include<iostream>
using namespace std;

int main()
{
    int t;

    for(int i = 1; i <= t; i = i + 1)
    {
        // code
    }

    return 0;
}
```
