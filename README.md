#PROGRAM TO PRINT SUM OF FACTORIALS OF THE GIVEN RANGE
n=int(input('enter number:'))
f=1 
sum=0
for i in range(1,n+1):
    f=f*i 
    sum=sum+f 
print('fatorial of a given no is:',f)
print('sum of factorials:',sum)
