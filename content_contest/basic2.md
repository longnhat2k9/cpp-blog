# Basic 2

## Contest Introduce
- Length: 2h30m

Difficult division
- Problem 1: Basic Math Operation
- Problem 2: If-else statement
- Problem 3: Basic Math Operation + If - else statement
- Problem 4, 5: Basic Math Operation + If - else statement + For/ While Loop
- Problem 6, 7, 8: Basic Math Operation + If - else statement + For/ While Loop + Array

## Problemset

|#|Name|Source|
|---|---|---|
|1|Calculate 1||
|2|Adherence to the Oath|The 2025 ICPC Vietnam National Contest. HCMC University of Technology – 09 November 2025|
|3|Calculate 2||
|4|Prime Number||
|5|Perfect Square||
|6|Biggest Number||
|7|Smallest Number||
|8|Even Odd Number|Bài 4: Tổng chẵn lẻ - Tin học trẻ Huyện Hương Sơn 2022 - 2023|

# Calculate 1

-----------------------------------
Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 1s/ 256MB

Judge: [Problem A - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/A)

-----------------------------------

Give you $2$ number $a$ and $b$. Output the number of $4$ operation (plus, minus, multiple, division). Each answer in $1$ line.

Division answer only output the number rounded to $4^{th}$ number decimal place.

## Input
$2$ integer number $a$ and $b$ $(1 \le a, b \le 10^6)$ separated by a space

## Output
Each lines output an answer for each operation. (Line 1: Plus, Line 2: Minus, Line 3: Multiple, Line 4: Division).

## Sample Input 1
```
10 5
```

## Sample Output 1
```
15
5
50
2.0000
```

## Sample Input 2
```
4 3
```

## Sample Output 2
```
7
1
12
1.3333
```

# Adherence to the Oath

------------------------------------

Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 1s/ 256MB

Judge: [Problem B - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/B)

Source: The 2025 ICPC Vietnam National Contest. HCMC University of Technology – 09 November 2025.

------------------------------------

As a contestant of The 2025 ICPC Vietnam National Contest, you are required to take the ICPC
contestant’s oath:

**ICPC contestant’s oath**

I, as a contestant of the International Collegiate Programming Contest, and on behalf of my team, do hereby pledge:

1. Uphold integrity and ethics throughout the contest.
2. Do not seek or receive external help from people, platforms, tools or AI.
3. Follow all ICPC rules and guidelines, accept decisions made by organizers and judges as final.
4. Show good sportmanship and treat competitors, volunteers, staff and judges with respect.
5. Compete with creativity and teamwork, honor the contest spirit and pursue excellence.

We make this pledge to honor our university, our team, and the global community of competitive programmers.

In this problem, you get a single integer p, you need to state the p-th item in the ICPC contestant’s oath.

## Input
The input consists of a single integer $p$ $(1 \le p \le 5)$.
## Output
Print out the p-th item in the ICPC contestant’s oath.

## Sample Input
```
1
```

## Sample Output
```
Uphold integrity and ethics throughout the contest.
```

# Calculate 2

-----------------------------------
Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 1s/ 256MB

Judge: [Problem C - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/C)

-----------------------------------

Give you $2$ number $a$ and $b$. Output the number of an operation given in the $o$ variable number in the input. 

|Operation|Number|
|---|---|
|Plus|1|
|Minus|2|
|Multiple|3|
|Division|4|

## Input
$3$ integer number $o$ $(1 \le o \le 4)$, $a$ and $b$ $(1 \le a, b \le 10^6)$ separated by a space

## Output
Answer of the problem.

## Sample Input 1
```
1 3 2
```
## Sample Output 1
```
5
```
## Sample Input 2
```
2 3 2
```
## Sample Output 2
```
1
```
## Sample Input 3
```
3 3 2
```
## Sample Output 3
```
6
```
## Sample Input 4
```
4 3 2
```
## Sample Output 4
```
1.5000
```

# Prime Number

-----------------------------------
Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 1s/ 256MB

Judge: [Problem D - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/D)

-----------------------------------

A prime number is a number only have $2$ divisor are $1$ and itself. Give you an integer number $n$ $(1 < n \le 10^6)$. Determine whether or not number $n$ is a prime number.

## Input
An integer number $n$ $(1 < n \le 10^6)$

## Output
Output "YES" if $n$ is a prime number, else output "NO"

## Sample Input 1
```
3
```
## Sample Output 1
```
YES
```
## Sample Input 2
```
1
```
## Sample Output 2
```
NO
```
## Sample Input 3
```
4
```
## Sample Output 3
```
NO
```

# Perfect Square

-----------------------------------
Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 1s/ 256MB

Judge: [Problem E - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/E)

-----------------------------------

A perfect square number is a number that after square root is an integer. Give you an integer $n$ $(1 < n \le 10^9)$. Determine whether or not $n$ is a perfect square number.

## Input
An integer number $n$ $(1 < n \le 10^9)$

## Output
Output "YES" if $n$ is a prime number, else output "NO"

## Sample Input 1
```
2
```
## Sample Output 1
```
NO
```
## Sample Input 2
```
4
```
## Sample Output 2
```
YES
```

# Biggest Number

----------------------------------------

Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 15s/ 256MB

Judge: [Problem F - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/F)

----------------------------------------

Give you an array $a$ of the length $n$. Output the biggest number.

## Input

- The $1^{st}$ line contains an integer number $n$ $(1 \le n \le 10^6)$ is the length of the array.
- The $2^{nd}$ line contains $n$ integer numbers $a_1, a_2,..., a_n$ $(1 \le |a_i| \le 10^6)$ separated by a space - element of the array $a$ 

## Output

The biggest number in the array

## Sample Input
```
6
15 20 11 24 59 32
```

## Sample Output
```
59
```

# Smallest Number

----------------------------------------

Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 15s/ 256MB

Judge: [Problem G - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/G)

----------------------------------------

Give you an array $a$ of the length $n$. Output the smallest number.

## Input

- The $1^{st}$ line contains an integer number $n$ $(1 \le n \le 10^6)$ is the length of the array.
- The $2^{nd}$ line contains $n$ integer numbers $a_1, a_2,..., a_n$ $(1 \le |a_i| \le 10^6)$ separated by a space - element of the array $a$

## Output

The smallest number in the array

## Sample Input
```
6
15 20 11 24 59 32
```

## Sample Output
```
11
```

# Even Odd Sum

---------------------------------

Input/ Output: stdin/ stdout

Time Limit/ Memory Limit: 15s/ 256MB

Judge: [Problem H - Contest: Basic 2](https://cppbasic.contest.codeforces.com/group/uPfoQRWoHp/contest/670558/submit/H)

Source: Bài 4: Tổng chẵn lẻ - Tin học trẻ Huyện Hương Sơn 2022 - 2023

---------------------------------

Give you an array $a$ of length $n$. Output the sum of the even number add the odd location.

## Input

- The $1^{st}$ line contains an integer number $n$ $(1 \le n \le 10^6)$ is the length of the array.
- The $2^{nd}$ line contains $n$ integer numbers $a_1, a_2,..., a_n$ $(1 \le |a_i| \le 10^6)$ separated by a space - element of the array $a$

## Output

Output the sum of the even number add the odd location.

## Sample Input
```
6
15 20 11 24 59 32
```

## Sample Output
```
0
```