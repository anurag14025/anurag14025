n=int(input("Enter the number:"))
m=n
sum=0
x=len(str(n))
for i in range(1,x+1):
    digit=n%10
    sum=sum+digit
    n//=10
if m%sum==0:
    print("This is harshad number")
else:
    print("Not Harshad Number")h
