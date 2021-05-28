```python
print("Hello world")
```

    Hello world
    


```python
student = "sam"
```


```python
student
```




    'sam'




```python
student="matt"
```


```python
student
```




    'matt'




```python
student="bob"
```


```python
student
```




    'bob'




```python
a1=10
a1
```




    10




```python
type(a1)
```




    int




```python
a1=3.14
a1
```




    3.14




```python
type(a1)
```




    float




```python
a1=true
a1
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-12-394d06ff008e> in <module>
    ----> 1 a1=true
          2 a1
    

    NameError: name 'true' is not defined



```python
a1=True
a1
```




    True




```python
type(a1)
```




    bool




```python
a1="hello world"
a1
```




    'hello world'




```python
type(a1)
```




    str




```python
a1= 3+4j
a1
```




    (3+4j)




```python
type(a1)
```




    complex




```python
#arithematic operators
```


```python
# +,-,/,*
```


```python
a=10
b=20
```


```python
a,b
```




    (10, 20)




```python
a+b
```




    30




```python
a-b
```




    -10




```python
a/b
```




    0.5




```python
#Relational operators
```


```python
#<,>,==,!=
```


```python
a=50
b=100
```


```python
a>b
```




    False




```python
a<b
```




    True




```python
a==b
```




    False




```python
a!=B
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-33-44572c93ec5a> in <module>
    ----> 1 a!=B
    

    NameError: name 'B' is not defined



```python
a!=b
```




    True




```python
#Logical operators
```


```python
# & |
```


```python
a=True
b=False
```


```python
a&a
```




    True




```python
a&b
```




    False




```python
b&a
```




    False




```python
b&b
```




    False




```python
a|b
```




    True




```python
b|a
```




    True




```python
a|a
```




    True




```python
b|b
```




    False




```python
True=a
```


      File "<ipython-input-46-4de7d1364c34>", line 1
        True=a
        ^
    SyntaxError: cannot assign to True
    



```python
student="martha"
```


```python
Student="julie"
```


```python
student
```




    'martha'




```python
Student
```




    'julie'




```python
str1='this is my first string'
```


```python
str1
```




    'this is my first string'




```python
str2 ="This is my second string"
```


```python
str2
```




    'This is my second string'




```python
str3 ='''
this string has 
lot 
of lines
in it'''
```


```python
str3
```




    '\nthis string has \nlot \nof lines\nin it'




```python
#Extracting individual characters from string
```


```python
my_string="My name is John"
```


```python
my_string[0]
```




    'M'




```python
my_string="My name is John"
```


```python
my_string[-1]
```




    'n'




```python
my_string='This is sparta'
```


```python
my_string
```




    'This is sparta'




```python
my_string[0]
```




    'T'




```python
my_string[-1]
```




    'a'




```python
my_string[5:11]
```




    'is spa'




```python
#if you want from i(5) to a(10) you have to write 5:11 as last number is not included in python 
```


```python
#string Fuctions
```


```python
#(1.)Finding length of string
```


```python
my_string='This is sparta'
my_string
```




    'This is sparta'




```python
len(my_string)
```




    14




```python
#(2.)Converting string to lower case
```


```python
my_string.lower()
```




    'this is sparta'




```python
#(3.)Converting string to upper case
```


```python
my_string.upper()
```




    'THIS IS SPARTA'




```python
#(4.)Replacing a substring
```


```python
my_string.replace('is','are')
```




    'Thare are sparta'




```python
#(5.)Number of occurence of substring
```


```python
str_new ='sparta sparta 300 300 300 300 s'
str_new
```




    'sparta sparta 300 300 300 300 s'




```python
str_new.count("sparta")
```




    2




```python
str_new.count("300")
```




    4




```python
str_new.count("s")
```




    3




```python
#(6.)Finding index of substring
```


```python
my_string='Hello world is awesome'
```


```python
my_string.find('i')
```




    12




```python
#(7.)Splitting a string
```


```python
str_final ='President Obama is best president of United States'
```


```python
str_final
```




    'President Obama is best president of United States'




```python
str_final.split('e')
```




    ['Pr', 'sid', 'nt Obama is b', 'st pr', 'sid', 'nt of Unit', 'd Stat', 's']




```python
#tuples in python
```


```python
tupl1 =(1,True,3.14,5-7j)
```


```python
tupl1
```




    (1, True, 3.14, (5-7j))




```python
type(tupl1)
```




    tuple




```python
#extracting individual elements
```


```python
tup1 =(1,"a",True,2,"b",False)
```


```python
tup1[0]
```




    1




```python
tup1 =(1,"a",True,2,"b",False)
```


```python
tup1[-1]
```




    False




```python
tupl =(1,"a",True,2,"b",False)
```


```python
tup1[1:4]
```




    ('a', True, 2)




```python
tup1 =(1,True,3.14,5-7j)
```


```python
tup1[0]
```




    1




```python
tup1[-1]
```




    (5-7j)




```python
tup1[0:2]
```




    (1, True)




```python
#modifying a tuple
```


```python
tup1[2]="hello"
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-114-2fc16622751e> in <module>
    ----> 1 tup1[2]="hello"
    

    TypeError: 'tuple' object does not support item assignment



```python
#You cannot modify a tuple beacuse it is immutable
```


```python
#TUPLE BASIC OPERATIONS
```


```python
#(1.)Finding Length of Tuples
```


```python
tup1 =(1,"a",True,2,"b",False)
```


```python
len(tup1)
```




    6




```python
#(2.)Concatenating Tuples
```


```python
tup1 =(1,2,3)
tup2 =(4,5,6)
tup1+tup2
```




    (1, 2, 3, 4, 5, 6)




```python
#(3.)Repeating Tuple Elements
```


```python
tup1 =('sparta',300)
tup1*3
```




    ('sparta', 300, 'sparta', 300, 'sparta', 300)




```python
#(4.)Repeating and Concatenating
```


```python
tup1 =('Sparta',300)
tup2 =(4,5,6)
tup1*3 + tup2
```




    ('Sparta', 300, 'Sparta', 300, 'Sparta', 300, 4, 5, 6)




```python
tup1=(1,2,3)
tup1*5
```




    (1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3)




```python
tup2=(4,5,6)
tup1*5+tup2
```




    (1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 1, 2, 3, 4, 5, 6)




```python
#(5.)Minimum Value
```


```python
tup1=(1,2,3,4,5)
min(tup1)
```




    1




```python
max(tup1)
```




    5




```python
tup1=(10,20,30,40,50,60)
min(tup1)
```




    10




```python
max(tup1)
```




    60




```python

```
