# Basic 1

## Contest Introduce
- Length: 2h30m

Difficult division
- Problem 0: Learn to use judge
- Problem 1, 2, 3.1: If-else statement
- Problem 3.2, 4.1, 4.2, 5, 6: If-else statement and For/While Loops

## Problemset

|#|Name|Submit Link|
|---|---|---|
|0|A + B|Submit|
|1|BMI|Submit|
|2|Cross Country|Submit|
|3.1|Square|Submit|
|3.2|Square?|Submit|
|4.1|Sublime Sequence|Submit|
|4.2|Sublime Sequence 2|Submit|
|5|A + B Again?|Submit|
|6|To My Critics|Submit|

## Complete Problemset

# A + B
---------------------------------------------------------------

Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 0: A + B - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/0)

---------------------------------------------------------------

You are given two integers $a$ and $b$. Print $a+b$.

## Input
The only line of the input contains integers $a$ and $b$ ($-100 \le a,b \le 100$).

## Output
Print $a+b$.

## Sample Input 1
```
7 8
```

## Sample Output 1
```
15
```

## Sample Input 2
```
-100 100
```

## Sample Output 2
```
0
```

## Sample Input 3
```
-7 -99
```

## Sample Output 3
```
-106
```

## Note
In the first example, $a=7$ and $b=8$. Thus, the answer is $a+b=7+8=15$.

# BMI
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 1: BMI - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/1)

---------------------------------------------------------------

You are a developer for a hospital. You have a very important task that you need to write a code to calculate the BMI for every person who visits your hospital site. BMI means Body Mass Index, so after calculating, you need to show the body fat matching with the BMI number after it is calculated.

**To calculate the BMI, you can use the equation below**

$$BMI=\frac{w}{h^2}$$

With:
- $w$: weight $(kg)$
- $h$: height $(m)$

**Here is the BMI body fat table**

|BMI range	|Body fat|
|---|---|
|Below 18.5	|Underweight|
|18.5 – Under 25.0	|Healthy|
|25.0 – Under 30.0	|Overweight|
|30.0 - Under 40.0	|Obesity|
|40.0 or above	|Extremely Obese|

## Input
$2$ positive integers $w(g)$ and $h(cm)$ separated by a space $(1 \le h \le 200, 1 \le w \le 100000)$

## Output
Output your answer follows the format bellow:
- On the first line print the BMI number.
- On the second line print the body fat matching with the number in the first line.

## Sample Input 1
```
100 91704
```

## Sample Output 1
```
91.704
Extremely Obese
```

## Sample Input 2
```
131 36372
```

## Sample Output 2
```
21.1946
Healthy
```

## Sample Input 3
```
138 67141
```

## Sample Ouput 3
```
35.2557
Obesity
```

## Sample Input 4
```
170 4717
```

## Sample Output 4
```
1.63218
Underweight
```

# Cross Country
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 2: Cross Country - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/2)

---------------------------------------------------------------
Given a two character code, decide if the code represents either:

|Code|Output|
|---|---|
|MG|midget girls|
|MB|midget boys|
|JG|junior girls|
|JB|junior boys|
|SG|senior girls|
|SB|senior boys|

All codes are case sensitive, and will always be two characters long. Be sure to reject invalid codes by outputting "invalid code". Also, output what each code represents, as stated exactly.

## Input
Input consists of a two character code representing either one of the six categories described above.

## Output
Output the full description of the code. If the code does not exist, output "invalid code".

## Sample Input 1
```
MG
```

## Sample Output 1
```
midget girls
```

## Sample Input 2
```
SS
```

## Sample Output 2
```
invalid code
```

# Square
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 3.1: Square - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/3.1)

---------------------------------------------------------------

Give you $4$ sticks with the length of each stick $a,b,c,d$. You can't break or bend any stick; determine whether or not to make a square with these sticks.

## Input 
Four integer numbers $a,b,c,d$ separated by a space. $(-10^{18} \le a, b, c, d \le 10^{18})$

## Output
Print "YES" if you can make a square with these sticks; else print "NO".

## Sample Input 1
```
673065317815646265 306825675314169590 442332000837659394 512184845035994911
```

## Sample Output 1
```
NO
```

## Sample Input 2
```
578922072762455706 578922072762455706 578922072762455706 578922072762455706
```

## Sample Output 2
```
YES
```

# Square?
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 3.2: Square? - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/3.2)

---------------------------------------------------------------

You are given $4$ sticks of lengths $a, b, c,$ and $d$. You can not break or bend them.

Determine whether it is possible to form a square$(*)$ using the given sticks.

$(∗)$ A square is defined as a polygon consisting of 4 vertices, of which all sides have equal length and all inner angles are equal. No two edges of the polygon may intersect each other.

## Input 
The first line contains a single integer $t (1 \le t \le 10^4)$ — the number of test cases.

The only line of each test case contains four integers $a, b, c,$ and $d (1 \le a,b,c,d \le 10)$ — the lengths of the sticks.

## Output
For each test case, print "YES" if it is possible to form a square using the given sticks, and "NO" otherwise.

You may print each letter in any case (uppercase or lowercase). For example, the strings "yEs", "yes", "Yes", and "YES" will all be recognized as a positive answer.

## Sample Input 
```
7
1 2 3 4
1 1 1 1
2 2 2 2
1 2 1 2
1 1 5 5
5 5 5 5
4 10 5 9
```

## Sample Output 
```
NO
YES
YES
NO
NO
YES
NO
```

## Note
In the first test case, we can prove that we can't make a square.

In the second, third, and sixth test cases, we can make a square like this:

![](https://espresso.codeforces.com/e51fcf1a3ba1663730b9f7ce5a8427c0796be6ca.png)

# Sublime Sequence
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 4.1: Sublime Sequence - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/4.1)

---------------------------------------------------------------

Farmer John has an integer $x$. He creates a sequence of length $n$ by alternating integers $x$ and $−x$, starting with $x$.

For example, if $n=5$, the sequence looks like: $x,−x,x,−x,x$. He asks you to find the sum of all integers in the sequence.

## Input
Two numbers $x$ and $n$ separated by a space. $(1 \le x, n \le 10^{18})$

## Output
Output the sum of the sequence.


## Sample Input 1
```
673065317815646265 306825675314169590
```

## Sample Output 1
```
0
```

## Sample Input 2
```
442332000837659394 512184845035994911
```

## Sample Output 2
```
442332000837659394
```

# Sublime Sequence 2
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 4.2: Sublime Sequence 2 - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/4.2)

---------------------------------------------------------------

Farmer John has an integer $x$. He creates a sequence of length $n$ by alternating integers $x$ and $−x$, starting with $x$.

For example, if $n=5$, the sequence looks like: $x,−x,x,−x,x$. 

He asks you to find the sum of all integers in the sequence.

## Input
The first line contains an integer $t$ ($1 \le t \le 100$) ~--- the number of test cases.

The only line of input for each test case is two integers $x$ and $n$ ($1 \le x, n \le 10$).

## Output
For each test case, output the sum of all integers in the sequence.

## Sample Input 
```
4
1 4
2 5
3 6
4 7
```

## Sample Output
```
0
2
0
4
```

# A + B Again?
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 5: A + B Again? - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/5)

---------------------------------------------------------------

Given a two-digit positive integer $n$, find the sum of its digits.

## Input
The first line contains an integer $t$ ($1 \le t \le 90$) - the number of test cases.

The only line of each test case contains a single two-digit positive integer $n$ ($10 \le n \le 99$).

## Output
For each test case, output a single integer~--- the sum of the digits of $n$.

## Sample Input 
```
8
77
21
40
34
19
84
10
99
```

## Sample Output
```
14
3
4
7
10
12
1
18
```

# To My Critics
---------------------------------------------------------------
Input/ Output: stdin/ stdout

Time Limit: 1s. Memory Limit: 256MB

Judge: [Problem 6: To My Critics - Contest: Basic 1](https://codeforces.com/group/uPfoQRWoHp/contest/663652/problem/6)

---------------------------------------------------------------
Suneet has three digits $a$, $b$, and $c$. 

Since math isn't his strongest point, he asks you to determine if you can choose any two digits to make a sum greater or equal to $10$.

Output YES if there is such a pair, and NO otherwise.

## Input
The first line contains a single integer $t$ ($1 \le t \le 1000$) - the number of test cases.

The only line of each test case contains three digits $a$, $b$, $c$ ($0 \le a, b, c \le 9$).

## Output
For each test case, output YES if such a pair exists, and NO otherwise.

You can output the answer in any case (for example, the strings yEs, yes, Yes and YES will be recognized as a positive answer).

## Sample Input
```
5
8 1 2
4 4 5
9 9 9
0 0 0
8 5 3
```

## Sample Output
```
YES
NO
YES
NO
YES
```

## Note
For the first test case, by choosing the digits $8$ and $2$ we can obtain a sum of $8 + 2 = 10$ which satisfies the condition, thus the output should be YES.

For the second test case, any combination of chosen digits won't be at least $10$, thus the output should be NO (note that we can not choose the digit on the same position twice).

For the third test case, any combination of chosen digits will have a sum equal to $18$, thus the output should be YES.