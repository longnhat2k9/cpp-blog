# Lesson 1

## I. Code C++ Syntax
```cpp
#include<iostream>
using namespace std;

int main()
{
    cout << "Hello World" << endl;

    return 0;
}
```

## II. Data types - Variable - Declaring Variable - Base Math Arithmetic - Comparision Arithmetic

### 1. Data Types

- **int**: integer number smaller than $10^9$

- **long long**: integer number smaller than $10^{18}$

- **float**: Stores fractional numbers, containing one or more decimals. Sufficient for storing 6-7 decimal digits

- **double, long double**: Stores fractional numbers, containing one or more decimals. Sufficient for storing 15 decimal digits or more

- **char**: Stores a single character/letter/number, or ASCII values

- **string**: store a sequence of characters 

- **bool**: Store ```true``` or ```false```
### 2. Variable - Declaring Variable

#### Declaring Variable Syntax

```cpp
<datatype> <variable_name>; // Base Declare
<datatype> <variable_name> = <value>; // Declare with value
```

**Note:**
Variable name rules:
- **Only** start with a text character [a-z] or [A-Z]
- **Not** contain any special character (like @, #, $, %, &,....) or space exept the dash (-)
- Choose variable **fit or bigger** than the value you want to save or declare with
- A bool variable can save a value from answer of comparision statement or condition

#### Example

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
### 3. Base Math Arithmetic

**Plus:** ```+```

**Minus:** ```-```

**Multiple:** ```*```

**Divide:** ```\```

**Modulo:** ```%```

**Note:** 
- Modulo **only** use for **integer** number
- Divide will return the **integer** number if the number you use is integer (**even if** you use two numbers have **modulo not equal to 0**)

### 4. Comparision Arithmetic

**Better:** ```>```

**Smaller:** ```<```

**Better or Equal:** ```>=```

**Smaller or Equal:** ```<=```

**Equal:** ```==```

## III. If-else statement

### 1. Syntax

#### 1 condition
```cpp
if(/*condition*/)
{
    /*code*/
}
```

#### 1 condition + another case
```cpp
if(/*conditon*/)
{
    /*code*/
}
else
{
    /*code 2*/
}
```

#### 2 (or more) conditon + another case 
```cpp
if(/*condition_1*/)
{   
    /*code 1*/
}
else if(/*condition_2*/)
{
    /*code 2*/
}
....
else
{
    /*code 3*/
}
```

### 2. Example

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

## IV. For Loop - Base for loop:

### 1. Syntax
```cpp

for(/*start*/; /*stop*/; /*value change*/)
{
    /*code*/ 
}

```

**Note:**
- **Start:** Init a variable with value 
- **Stop:** Write a condition for variable (if condition true -> code in the loop will continue running, else code in the loop will stop)
- **Value Change:** Use any math equation to change your variable, the value after change will determine whether or not the code will run with the condition in the stop statement

### 2. Example

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
