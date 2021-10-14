# prime-or-not

N=int(input())
if n==1:
   print("not prime and not composite")
for i in range(2,n):
    if n%i==0:
        print("not prime")
        break
    else:
        print("prime")
        break

