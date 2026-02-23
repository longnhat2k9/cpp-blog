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

## II. While Loop

### 1. Syntax
```cpp
while(/*condition*/)
{
    /*code*/
}
```

### 2. Example: Count the length of number $n$

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

## III. Array

### 1. Syntax

#### Declare

```cpp
<data_types> <array_name> [<size>];
```

**Note:** Array name rules are the same as variable name rules

#### Access Element

```cpp
<array_name> [<index>];
```

**Note:**
- ```<index>```: index in array start from $0$ to ```<index> - 1```

#### Declare with data

```cpp
<data_types> <array_name> [<size>] = {<val1>, <val2>,....};
```

**Note:** Number of value in the last breaket is smaller or equal to the size

#### Input value from stdin

```cpp
long long n; // n is the size of the array
long long a[n]; // array name: a. array size: n.
for(long long i = 0; i < n; i = i + 1)
{
    cin >> a[i]
}
```

### 2. Example

```cpp
#include <iostream>
using namespace std;

int main() {

  int numbers[5];

  cout << "Enter 5 numbers: " << endl;

  //  store input from user to array
  for (int i = 0; i < 5; ++i) {
    cin >> numbers[i];
  }

  cout << "The numbers are: ";

  //  print array elements
  for (int n = 0; n < 5; ++n) {
    cout << numbers[n] << "  ";
  }

  return 0;
}
```