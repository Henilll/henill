# henill
#ArmStrong Number Between 1 To 1000 In python easy Solutin...!
#For any Inquiry mail at:henilbhavsar164@gmail.com


for i in range(1,1001):
    num=i
    sum1=0
    n=len(str(i))
    while(i!=0):
        digit=i%10
        sum1=sum1+digit**n
        i=i//10
    if sum1==num:
        print(num)
                                                                                
