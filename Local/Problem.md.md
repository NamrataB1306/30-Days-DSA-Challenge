# Equal Stacks

You have three stacks of cylinders where each cylinder has the same diameter, but they may vary in height. You can change the height of a stack by removing and discarding its topmost cylinder any number of times.

Find the maximum possible height of the stacks such that all of the stacks are exactly the same height. This means you must remove zero or more cylinders from the top of zero or more of the three stacks until they are all the same height, then return the height.


# Sample Input

```
STDIN       Function
-----       --------
5 3 4       h1[] size n1 = 5, h2[] size n2 = 3, h3[] size n3 = 4  
3 2 1 1 1   h1 = [3, 2, 1, 1, 1]
4 3 2       h2 = [4, 3, 2]
1 1 4 1     h3 = [1, 1, 4, 1]

```

# Sample Output

```
5


```
# Explanation

**Explanation**

To equalize there heights, remove the first cylinder from stacks  and  , and then remove the top two cylinders from stack  

The stack heights are reduced as follows:
1. 8-3=5
2. 9-4=5
3. 7-1-1=5
All three stacks now have hight=5 , the value to return



