num=int(input("Enter the number of terms: "))
n1,n2=0,1
count=0
if num<=0:
    print("Enter the number: ")
elif num == 1:
    print("Fibonacci series upto",num,": ")
    print(n1)
else:
    print("Fibonacci Series: ")
    while count<num:
        print(n1)
        n=n1+n2
        n1=n2
        n2=n
        count+=1
