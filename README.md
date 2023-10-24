# Armstrong-number-identifier
An Armstrong number identifier code
code --
print("input a number")
num1 =int(input())

temp=num1
sum=0
while(temp>0):

    a1=temp%10
    sum=sum+(a1**3)
    temp = temp//10

if sum==num1:
    print("armstrong")
else:
    print(" different number ")
