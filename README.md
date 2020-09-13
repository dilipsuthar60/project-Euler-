import sys
def d(x):
    return x*(x+1)


t = int(input().strip())
for a0 in range(t):
    n = int(input().strip())
    n=n-1
    a=int(n/3)
    b=int(n/5)
    c=int(n/15)
    print(int(int(3*d(a)+5*d(b)-15*d(c))>>1))
