# Lesson 2

## I. For Loop - Nest-Loop

### 1. Syntax
```cpp
for(/*start*/; /*stop*/; /*value change*/)
{
    for(/*start*/; /*stop*/; /*value change*/)
    {
        /*code*/ 
    }
}
```

### 2. Example
```cpp
#include<iostream>
using namespace std;

int main()
{
    int t;

    for(int i = 1; i <= t; i = i + 1)
    {
        for(int j = 1; j <= t; j = j + 1)
        {
            // code
        }
    }

    return 0;
}
```

## While Loop

Example: Count the length of number $n$

```cpp
#include<iostream>
using namespace std;

int main()
{
    int count = 0;
    int n;
    cin >> n; 

    while(n > 0)
    {
        n /= 10;
        count = count + 1;
    }

    cout << count;

    return 0;
}
```

## Array

Syntax

```cpp

```

```cpp
#include<iostream>
using namespace std;

int main()
{
    int count = 0;
    int n;
    cin >> n; 

    while(n > 0)
    {
        n /= 10;
        count = count + 1;
    }

    cout << count;

    return 0;
}
```