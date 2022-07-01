# creativity
C3.38 Show that ∑ni=1 i2 is O(n3).

1+4+9+16+... n2
```
def compute_square(n):
    return n*n   #c

sum=0 #c
for i in range(n): 
    sum=sum+compute_square(i) #c+c=2c

print(sum)
```
 
