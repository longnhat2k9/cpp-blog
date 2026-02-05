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