# BASIC CALCULATOR:
a=int(input('enter 1st number:'))
b=int(input('enter 2nd number:'))
c=int(input(f'type of operation 1 is add,2 is sub,3 is multiply,4 is divide:'))
if(c==1):
  print('sum is:', (a+b))
elif(c==2):
 print('subtract is:',(a-b))
elif(c==3):
 print('multiply is:',(a*b))
elif(c==4):
 print('division is:',(a/b))
else:
 print("invalid operation")
 
 
# EXECUTION OF PRIME NUMBERS FROM 0 TO 100:
a=0
b=100
for x in range(a, b +1):
    if(x > 1):
      for y in range(2,x):
         if(x % y) == 0:
           break
     else:
          print(x)
          
# EXECUTE THE FIBONACCI SERIES OF A NUMBER:
a = 0
b = 1
n = int(input("Enter the series to be generated:"))
if n <= 0:
   print(f'Not valid')
elif n == 1:
    print(a)
elif n >= 2:
    print(a)
    print(b)
    for i in range(2, n):
        c = a+b
        a = b
        b = c
        print(c)
        
        
        
