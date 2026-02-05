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