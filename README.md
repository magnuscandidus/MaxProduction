# MaxProduction
# cook your dish here
t=int(input())
while t:
    d,x,y,z=map(int,input().split())
    a=(x*7)
    b=((d*y)+((7-d)*z))
    if(a>b):
        print(a)
    else:
        print(b)
    t-=1
