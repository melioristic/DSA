# creativity

### C3.35 Assuming it is possible to sort n numbers in O(nlogn) time, show that it is possible to solve the three-way set disjointness problem in O(nlogn) time.

### Solution 

====

PSEUDOCODE
NEW_DISJOINT = Should not be in all 3 

A, B, C

AB check 

for a in A: # n2c
    for b in B: #nc
        if a==b: # c
            return -1

3n2C

O(n2)

Array <- A, B, C # 3n 

sorted(Array) O(nlogn)

for i in range(len(Array)):
    a[i] == a[i+1] c
    a[i+1] == a[i+2] c

 

BC check
CA check



### C3.38 Show that ∑ni=1 i2 is O(n3).

1+4+9+16+... n2
```
def compute_square(n):
    return n*n   #c

sum=0 #c
for i in range(n): 
    sum=sum+compute_square(i) #c+c=2c

print(sum)
```
 
