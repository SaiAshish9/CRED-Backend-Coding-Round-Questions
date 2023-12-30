# CRED-Backend-Coding-Round-Questions

#Q1
consider two arrays a and b where each consists of n integers. In one operation 
1. Select two indices i and j (0<= i, j<n)
2. Swap integers a[i[ and b[j]

This operation can be performed at most k times.

Find maximum number of distinct elements that ca be achieved in array a after atmost k operations

For example
n = 5
a = [1, 1, 4, 5, 5]
b=[4, 4, 3, 1, 5]
k=2
output: 4
```

```

#Q2
```
User
Rohan has got homework q to combine n strings of digits and write in this notebook.  But rohan wants to complete this fast so that he can go and play cricket. So he decides to combine some digits of these strings.

Rohan picks the strings one by one concatenates them together. Suppose he is at the ith string y=s[i] and till now the concatenated string is x which was formed from first i-1 strings, he can now form a new concatenation xy or yx. Also during the concatenation , if the last character of the left string and first character of the right is the same, he deletes one of these characters. He needs your help in determining the length of the shortest concatenated string that he can write.

You will be given the order in which Rohan picks the strings.

Sample Input
1
3
54
45
05

Sample Output
4

shortest concatenated string would be 0545
```

#Q3
```
dr shalunkhe has a floor of size n*m in his chemical lab where each tite is 1*1. if a drop of chemical solution falls on a tile, then it will combine to form a bigger drop if there is some chemical solution
drop in the adjacent tile sharing the common side.

Note: if the chemical solution falls on the same side, the size remains the same

Sample input:
3 3 4
d 1  1
d 2 2
d 3 3

Sample output
3
```
