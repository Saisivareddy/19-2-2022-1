# 19-2-2022-1
def myprime(n):

    x=n//2

    for i in range(2,x+1):

        if n%i==0:

            return False

    return True

t=int(input('enter:'))

for i in range(t):

    x=input().split(' ')

    start=int(x[0])

    end=int(x[1])

    c=0

    for i in range(start+i,end):

        if myprime(i):

            c=c+i

            print(c)
