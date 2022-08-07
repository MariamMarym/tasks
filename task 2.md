```python
#Write a Python program to find those numbers which are divisible by 7 and multiple of 5, between 1500 and 2700 (both included)
for i in range(1500,2701):

    if i%7==0 and i%5==0:

        print("  ",i)

```

       1505
       1540
       1575
       1610
       1645
       1680
       1715
       1750
       1785
       1820
       1855
       1890
       1925
       1960
       1995
       2030
       2065
       2100
       2135
       2170
       2205
       2240
       2275
       2310
       2345
       2380
       2415
       2450
       2485
       2520
       2555
       2590
       2625
       2660
       2695
    


```python
# Write a Python program to convert temperatures to and from celsius,fahrenheit.[ Formula : c/5 = f-32/9 [ where c = temperature in celsius and f = temperature infahrenheit ]
celsius_1 = float(input("Temperature value in degree Celsius: " ))  
  
# For Converting the temperature to degree Fahrenheit by using the above  
# given formula  
Fahrenheit_1 = (celsius_1 * 1.8) + 32  
    
# print the result  
print('The %.2f degree Celsius is equal to: %.2f Fahrenheit'  
      %(celsius_1, Fahrenheit_1))  
  
```

    Temperature value in degree Celsius: 50
    The 50.00 degree Celsius is equal to: 122.00 Fahrenheit
    


```python
#Write a Python program to construct the following pattern, using a
#nested for loop.

n=5;
for i in range(n):
    for j in range(i):
        print ('* ', end="")
    print('')

for i in range(n,0,-1):
    for j in range(i):
        print('* ', end="")
    print('')
	

```

    
    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    * * * * 
    * * * 
    * * 
    * 
    


```python
#Write a Python program that accepts a word from the user and reverse it.
word = input("Input a word to reverse: ")
 
for char in range(len(word) - 1, -1, -1):
  print(word[char], end="")
print("\n")
```

    Input a word to reverse: hi
    ih
    
    


```python
#Write a Python function to find the Max of three numbers.
n1=int(input("Enter first number: "));

n2=int(input("Enter second number: "));

n3=int(input("Enter Third number: "));

def f():

    if(n1>=n2) and (n1>=n3):

        l=n1

    elif(n2>=n1) and (n2>=n3):

         l=n2

    else:

         l=n3

    print("Largest number among  the three is",l)

f()
```

    Enter first number: 20
    Enter second number: 30
    Enter Third number: 40
    Largest number among  the three is 40
    


```python
# sum numbers in list
num = [1, 2, 3, 4, 5]
total = 0
for x in num:
    total += x

print(total)
```

    15
    


```python
#Write a Python program that prints all the numbers from 0 to 6 except 3 and 6. Note : Use 'continue' statement.
for x in range(6):
    if (x == 3 or x==6):
        continue
    print(x,end=' ')
print("\n")
 
```

    0 1 2 4 5 
    
    


```python
#Write a Python function to calculate the factorial of a number (a nonnegative integer). The function accepts the number as an argument.
def fact(a): 
    facto=1 
    while a>=15: 
        facto=facto*a 
        a=a-1 
    return facto 
x=int(input('enter a number')) 
y=fact(x) 
print(y) 
```

    enter a number2
    1
    


```python
#Write a Python function that takes a list and returns a new list with unique elements of the first list
def unique_list(l):
  x = []
  for a in l:
    if a not in x:
      x.append(a)
  return x

print(unique_list([1,2,3,3,3,3,4,5]))
```

    [1, 2, 3, 4, 5]
    


```python
#Write a Python program to create a lambda function that adds 15 to a given number passed in as an argument, also create a lambda function that multiplies argument x with argument y and print the result. Bonus
r = lambda a : a + 15
print(r(10))
r = lambda x, y : x * y
print(r(12, 4))
```

    25
    48
    


```python

```
