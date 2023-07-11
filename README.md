# ChefAndPairingSlippers
# cook your dish here
t=int(input())
while t:
    n,l,x=map(int,input().split())
    a=n-l
    if(l>a):
        print(a*x)
    else:
        print(l*x)
    t-=1
