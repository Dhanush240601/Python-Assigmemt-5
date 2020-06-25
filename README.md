# Python-Assigmemt-5 

1)Convert binary number into decimal
a)binary_string=input('enter a binary number')
try:
decimal=int(binary_string,2)
print('the decimal value is',decimal)
except ValueError:
print('invalid binary number')
Output:
enter a binary number 10
the decimal value is 2
2)Generate first N number of fibonacci numbers.Take N value from user
a)
def FibRecursion(n):
if n<=1:
return n
else:
return(FibRecursion(n-1)+FibRecursion(n-2))
nterms=int(input('enter the terms'))
if nterms<=0:
print('Please enter a positive integer')
else:
print('fibonacci sequence')
for i in range(nterms):
print(FibRecursion(i))
Output:
enter the terms 5
fibonacci sequence
0
1
1
2
3
3)Display multiplication table of K.Take K value from user
a)n=int(input('enter n value'))
for i in range(1,11):
print(n,'x',i,'=',n*i)
Output:
enter n value 2
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
4)Take 10 integers from keyboard using loop and print their
Average value on the screen.
a) print('input 10 integers')
count=0
sum=0.0
number=1
while number!=0:
number=int(input(""))
sum=sum+number
count+=1
if count==0:
print('input some numbers ')
else:
print('average',sum/(count-1))
Output:
input 10 integers
10
10
10
10
10
10
10
10
10
10
10
0
average 10.0
Print the value following patterns using loop:
*
**
