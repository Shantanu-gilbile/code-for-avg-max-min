score=[]
num=int(input('Enter number of Subjects? '))
total_sum=0
for n in range (num):
    numbers=float(input('Enter Marks: '))
    score.append(numbers)
            total_sum+=numbers
        
avg=total_sum/num
print(score)



max=0
for n in score:
    if n>max:
        max=n
        
      

min=max
for n in score :
    if n<min:
        min=n
    

print('Menu')
print('1.Sum of the Marks')
print('2.Average of the Marks') 
print('3.Maximum mark scored')
print('4.Minimum mark')
print('5.Exit')
l=1
while(l==1):
    ch=int(input('What you want to perform :'))
    if(ch==1):
        print('Sum of the marks is ',total_sum)
        
    elif(ch==2):
        print('Average of the marks is',avg)
        
    elif(ch==3):
        print('Highest mark scored is',max)
        
    elif(ch==4):
        print('lowest marks scored is',min)
    elif(ch==5):
        print('Successfully Exited.')
        break;
    else:
        print('You have entered wrong choice please check again')






