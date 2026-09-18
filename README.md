# Python_Programming

Python 3.14.7 (tags/v3.14.7:823f032, Aug  5 2026, 10:51:32) [MSC v.1944 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello Word")
Hello Word
>>> #Taking input from the user.
>>> name=input("Enter you name:")
Enter you name:Satish kumar
>>> print("Hello :"+name)
Hello :Satish kumar
>>> print(type(name))
...
...
<class 'str'>
>>> #Taking input from the user as integer.
>>> num=input("Enter the Number");
Enter the Number
>>> num=input("Enter the Number:");
Enter the Number:3
>>> print(num)
3
>>> print(type(num))
<class 'str'>
>>> #Use The type Casting Method to Change by default data type to write data type
>>> #Use The type Casting Method to Change by default data type ('str') :- Enter the any data type to write data type
>>> num=int(input("Enter The Value:);
  File "<python-input-12>", line 1
    num=int(input("Enter The Value:);
                  ^
SyntaxError: unterminated string literal (detected at line 1)
>>> num=int(input("Enter The Value:"));
Enter The Value:5
>>> print(num)
5
>>> print(type(num))
<class 'int'>
>>> num=float(input("Enter The Value:"));
Enter The Value:7
>>> print(type(num))
<class 'float'>
>>> print(num)
7.0
>>> num=bool(input("Enter The Value:"));
Enter The Value:8
>>> print(num)
True
>>> print(type(num))
<class 'bool'>
>>> num=bool(input("Enter The Value:"));
Enter The Value:
>>> print(num)
False
>>> print(type(num))
<class 'bool'>
>>>
>>>
>>>
>>> #int
>>> age=32
>>> print(age)
32
>>> print(type(age))
<class 'int'>
>>>
>>> #float
>>> weight=72.43
>>> print(weight)
72.43
>>> print(type(weight))
<class 'float'>
>>>
>>>
>>> #string
>>> name="Satish"
>>> print(namre)
Traceback (most recent call last):
  File "<python-input-41>", line 1, in <module>
    print(namre)
          ^^^^^
NameError: name 'namre' is not defined. Did you mean: 'name'?
>>> print(name)
Satish
>>> print(type(name))
<class 'str'>
>>>
>>>
>>> #boolean
>>>
>>> is_boy=true
Traceback (most recent call last):
  File "<python-input-48>", line 1, in <module>
    is_boy=true
           ^^^^
NameError: name 'true' is not defined. Did you mean: 'True'?
>>> is_boy=true;
Traceback (most recent call last):
  File "<python-input-49>", line 1, in <module>
    is_boy=true;
           ^^^^
NameError: name 'true' is not defined. Did you mean: 'True'?
>>> is_boy=True;
>>> print(is_boy)
True
>>> print(type(is_boy))
<class 'bool'>
>>>
>>>
>>> #Dictionary
>>>
>>> dict1={"name":"varun","branch":"CS&E"}
>>> print(dict1)
{'name': 'varun', 'branch': 'CS&E'}
>>>
>>> print(dict1["branch"])
CS&E
>>>
>>> #Tuple
>>> tup=(10,20,30,40,50,60,70,80,90)
>>> print(tup)
(10, 20, 30, 40, 50, 60, 70, 80, 90)
>>> print(type(tup))
<class 'tuple'>
>>>
>>> #set
>>>
>>> set={10,20,30,40,50,60,70,80,90}
>>> print(set)
{70, 40, 10, 80, 50, 20, 90, 60, 30}
>>> print(type(set))
<class 'set'>
>>>
>>> #None
>>>
>>> house_no=NONE
Traceback (most recent call last):
  File "<python-input-75>", line 1, in <module>
    house_no=NONE
             ^^^^
NameError: name 'NONE' is not defined. Did you mean: 'None'?
>>> house_no=None
>>> print(house_no)
None
>>> print(type(house_no))
<class 'NoneType'>
>>>
>>>
>>> #complex
>>>
>>> com=1+3j;
>>> print(com)
(1+3j)
>>> print(typeof(com))
Traceback (most recent call last):
  File "<python-input-85>", line 1, in <module>
    print(typeof(com))
          ^^^^^^
NameError: name 'typeof' is not defined. Did you mean: 'type'?
>>> print(type(com))
<class 'complex'>
>>>
>>> #range
>>>
>>> num=range(1,5)
>>> print(num)
range(1, 5)
>>> print(type(num))
<class 'range'>
>>>
>>>
>>> #byte & bytearray
>>>
>>> byte=bytes([65,66,67])
>>> print(byte)
b'ABC'
>>> print(type(byte))
<class 'bytes'>

##Typecasting

Python 3.14.7 (tags/v3.14.7:823f032, Aug  5 2026, 10:51:32) [MSC v.1944 64 bit (AMD64)] on win32
>>> num1=input("Entre first Number:")
Entre first Number:54
>>> num2=input("Entre first Number:")
Entre first Number:25
>>> print(num1+num2)
5425
>>> num1=int(input("Entre first Number:"))
Entre first Number:52
>>> num2=int(input("Entre first Number:"))
Entre first Number:54
>>> print(num1+num2)
106
>>> num=20
>>> num1=20
>>> num2=50
>>> num2=50.2
>>> print(num1+num2)
70.2
>>> a=11
>>> f=float(a)
>>> print(a)
11
>>> print(f)
11.0
>>> f=hex(a)
>>> print(f)
0xb
>>> f=oct(a)
>>> print(f)
0o13
>>> f=bin(a)
>>> print(f)
0b1011
>>> char='A'
>>> e
>>> e=ord(char)
>>> print(e)
65
>>> e=65
>>> char=char(e)print

>>> print(e)
65


>>> ##Escape character:-
>>> print('I' ll call your latter)
  File "<python-input-1>", line 1
    print('I' ll call your latter)
          ^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> print('I\' ll call your latter)
  File "<python-input-2>", line 1
    print('I\' ll call your latter)
          ^
SyntaxError: unterminated string literal (detected at line 1); perhaps you escaped the end quote?
>>> print('I\' ll call your latter')
I' ll call your latter
>>> print("Prepare will for"Gate2027" exam)
  File "<python-input-4>", line 1
    print("Prepare will for"Gate2027" exam)
                                    ^
SyntaxError: unterminated string literal (detected at line 1)
>>> print("Prepare will for \"Gate2027\" exam")
Prepare will for "Gate2027" exam
>>> a="Hello \\ Smaasher|"
>>> print(a)
Hello \ Smaasher|
>>> a="Hello \ Smaasher|"
<python-input-8>:1: SyntaxWarning: "\ " is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\ "? A raw string is also an option.
>>> a="Hello \n Smaasher|"
>>> print(a)
Hello
 Smaasher|
Hell Smaasher|
>>> a="Hello \t Smaasher|"
>>> print(a)
Hello    Smaasher|
>>> a="Hello \t\t Smaasher|"
>>> print(a)
Hello            Smaasher|
>>> x="No_benfit_of_study\r Huge_benfits";
>>> print(x)
 Huge_benfitsstudy
>>>
>>> ### Logical Operator
>>> >>> a=True
>>> b=False
>>> if not a:
...     print("My name is a")
... if not b:
...     print("My name is b")
...
...
My name is b
>>> >>>
>>> a=False
>>> b=True
>>> if not a:
...     print("My name is a")
... if not b:
...     print("My name is b")
...
My name is a


>>> age=15
>>> income=20000
>>> if age >=18 or income >=15000:
...     print("eligible for the loan")
... else:
...     printf("Not eligible for thr loan")
...
eligible for the loan
>>
>>>>> age=17
>>> income=200
>>> if age >=18 or income >=15000:
...     print("eligible for the loan")
... else:
...     print("Not eligible for thr loan")
..
Not eligible for thr loan

### Identity Operator
>>> x=10
>>> y=10
>>> print(x is y)
True
>>> z=x
>>> print(z is x)
True
>>> print(id(x))
140731971134872
>>> print(id(y))
140731971134872
>>> print(id(z))
140731971134872
>>
>>>>> str2="Hii"
>>> str1="Hii"
>>> print(str1 is str2)
True


>>> list1=[10,20,30]
>>> list2=[10,20,30]
>>> print(list1 is list2)
False
>>> print(id(list1))
1909917596160
>>> print(id(list2))
1909917596032
>>>

>>> Membership Operator:-
>>> >>> list1=[1,2,3,4,5]
>>> 1 in list1
True
>>> 10 in list1
False
>>> 10 not in list1
True

>>> if name in reg_usr:
...     print("Access granted.Welcome br");
... else:
...     print("Access denied.you are not registered.");
...
KeyboardInterrupt
>>> reg_usr=["varun","ravi","amrit","nitin"]
>>> name=input("enter your name:")
enter your name:ram
>>> if name in reg_usr:
...     print("Access granted.Welcome br");
... else:
...     print("Access denied.you are not registered.");
...
Access denied.you are not registered.
>>> name=input("enter your name:")
enter your name:ravi
>>> if name in reg_usr:
...     print("Access granted.Welcome br");
... else:
...     print("Access denied.you are not registered.");
...
Access granted.Welcome br

>>> first_string='hello, World |'
>>> print(first_string)
hello, World |
>>> first_string[1]
'e'
>>> first_string[2]
'l'
>>> first_string[3]
'l'
>>> first_string[3]="o"
Traceback (most recent call last):
  File "<python-input-16>", line 1, in <module>
    first_string[3]="o"
    ~~~~~~~~~~~~^^^
TypeError: 'str' object does not support item assignment
>>> first_string[1:4]
'ell'
>>> len(first_string)
14
>>> list1=[1,2,3,4,5]
>>> list1[1]=50
>>> print(list1)
[1, 50, 3, 4, 5]
>>> string1='Hello';
>>> string2='World';
>>> string=string1+string2;
>>> print(string)
HelloWorld
>>> string=string1+''+string2;
>>> print(string)
HelloWorld
>>> string=string1+' '+string2;
>>> print(string)
Hello World
>>> string1='Hello';
>>> string2=20
>>> string=string1+' '+string2;
Traceback (most recent call last):
  File "<python-input-32>", line 1, in <module>
    string=string1+' '+string2;
           ~~~~~~~~~~~^~~~~~~~
TypeError: can only concatenate str (not "int") to str
>>> string2='20'
>>> string=string1+' '+string2;
>>> print(string)
Hello 20
>>> string2=str(20)
>>> string=string1+' '+string2;
>>> print(string)
Hello 20
>>> first='Varun';
>>> last='Singla';
>>> age=33
>>> print('My First name is first & last name is last & age is age')
My First name is frist & last name is last & age is age
>>> print(f'My First name is first & last name is last & age is age')
My First name is frist & last name is last & age is age
>>> print(f'My First name is {first} & last name is {last} & age is {age}')
My First name is Varun & last name is Singla & age is 33


## String slicing....   


>>> string="Gate Smashers".
>>> print(string)
Gate Smashers
>>> substr1=string[5:10]
>>> print(substr1)
Smash
>>> substr2=string[5:]
>>> print(substr2)
Smashers
>>> substr3=string[:10]
>>> print(substr3)
Gate Smash
>>> substr4=string[:]
>>> print(substr4)
Gate Smashers
>>> substr5=string[-8:-3]
>>> print(substr5)
Smash
>>> substr6=string[5::2]
>>> print(substr6)
Sahr
>>> substr7=string[::-1]
>>> print(substr7)
srehsamS etaG
>>> substr8=string[5:12]
>>> print(substr8)
Smasher
>>> substr9=string[5:12].upper()
>>> print(substr9)
SMASHER
>>


##List Data Types.....

>> list1=[20,55,"Hello World"]
>>> print(list1)
[20, 55, 'Hello World']
>>> list1=[20,5.5,"Hello World"]
>>> print(list1)
[20, 5.5, 'Hello World']
>>> list2=[['varun',1989],['Ravinder',1990],['Amrit',1991]]
>>> print(list2)
[['varun', 1989], ['Ravinder', 1990], ['Amrit', 1991]]
>>> list1=[20,5.5,"Hello World"]
>>> list[0]
list[0]
>>> list1[0]
20
>>> list1[2]
'Hello World'
>>> list1[5]
Traceback (most recent call last):
  File "<python-input-10>", line 1, in <module>
    list1[5]
    ~~~~~^^^
IndexError: list index out of range
>>> list1[-1]
'Hello World'
>>> list1[n-1]
Traceback (most recent call last):
  File "<python-input-12>", line 1, in <module>
    list1[n-1]
          ^
NameError: name 'n' is not defined
>>> list1[-n]
Traceback (most recent call last):
  File "<python-input-13>", line 1, in <module>
    list1[-n]
           ^
NameError: name 'n' is not defined
>>> list1[2]
'Hello World'
>>> list1[2]="Radhe Radhe"
>>> print(list1)
[20, 5.5, 'Radhe Radhe']

## Concatenation.
>>> list1=[1,3,5,7,9]
>>> list2=[2,4,6,8,10]
>>> list1+list2
[1, 3, 5, 7, 9, 2, 4, 6, 8, 10]
>>> 
>>> ## Repetion:-
>>> list1=['Hello']
>>> list1*5
['Hello', 'Hello', 'Hello', 'Hello', 'Hello']
>>> 
>>## Membership
>>> list1=['varun','ravinder','amrit']
>>> 'Amrit' in list1
False
>>> 'amrit' in list1
True
>>> 'Nitin' in list1
False


## List Function

>>> list1=[]10,20,30,40,50]
  File "<python-input-0>", line 1
    list1=[]10,20,30,40,50]
                          ^
SyntaxError: unmatched ']'
>>> list1=[10,20,30,40,50]
>>> lin(list1)
Traceback (most recent call last):
  File "<python-input-2>", line 1, in <module>
    lin(list1)
    ^^^
NameError: name 'lin' is not defined. Did you mean: 'bin'?
>>> len(list1)
5
>>> list1=list()
>>> list1
[]
>>> str1='aeiou'
>>> list1=list(str1)
>>> list1
['a', 'e', 'i', 'o', 'u']
>>> list1=[10,20,30,40,50]
>>> list1.append(50)
>>> list1
[10, 20, 30, 40, 50, 50]
>>> list1.append(60)
>>> list1
[10, 20, 30, 40, 50, 50, 60]
>>> list1.append([70,80],["RAM"])
Traceback (most recent call last):
  File "<python-input-14>", line 1, in <module>
    list1.append([70,80],["RAM"])
    ~~~~~~~~~~~~^^^^^^^^^^^^^^^^^
TypeError: list.append() takes exactly one argument (2 given)
>>> list1.append([70,80])
>>> list1
[10, 20, 30, 40, 50, 50, 60, [70, 80]]
>>> list1=[10,20,30]
>>> list2=[40,50]
>>> list1.extend(list2)
>>> list1
[10, 20, 30, 40, 50]
>>> list1.insert(2,35)
>>> list1
[10, 20, 35, 30, 40, 50]
>>> list1.insert(0,5)
>>> list1
[5, 10, 20, 35, 30, 40, 50]
>>> list1=[10,20,30,40,50,10,20,35,45,55]
>>> list1.count(10)
2
>>> list1.count(0)
0
>>> list1.count(90)
0
>>> list1.index(20)
1
>>> list1.index(90)
Traceback (most recent call last):
  File "<python-input-30>", line 1, in <module>
    list1.index(90)
    ~~~~~~~~~~~^^^^
ValueError: list.index(x): x not in list
>>> list1.index(23)
Traceback (most recent call last):
  File "<python-input-31>", line 1, in <module>
    list1.index(23)
    ~~~~~~~~~~~^^^^
ValueError: list.index(x): x not in list
>>> list1.remove(20)
>>> list1
[10, 30, 40, 50, 10, 20, 35, 45, 55]
>>> list1.remove(90)
Traceback (most recent call last):
  File "<python-input-34>", line 1, in <module>
    list1.remove(90)
    ~~~~~~~~~~~~^^^^
ValueError: list.remove(x): x not in list
>>> list1.pop(3)
50
>>> list1.pop(3)60
  File "<python-input-36>", line 1
    list1.pop(3)60
                ^^
SyntaxError: invalid syntax
>>> list1.pop()60
  File "<python-input-37>", line 1
    list1.pop()60
               ^^
SyntaxError: invalid syntax
>>> list1.pop()90
  File "<python-input-38>", line 1
    list1.pop()90
               ^^
SyntaxError: invalid syntax
>>> list1.pop()45
  File "<python-input-39>", line 1
    list1.pop()45
               ^^
SyntaxError: invalid syntax
>>> list1
[10, 30, 40, 10, 20, 35, 45, 55]
>>> list1.pop()30
  File "<python-input-41>", line 1
    list1.pop()30
               ^^
SyntaxError: invalid syntax
>>> list1.pop() 30
  File "<python-input-42>", line 1
    list1.pop() 30
                ^^
SyntaxError: invalid syntax
>>> list1.POP() 30
  File "<python-input-43>", line 1
    list1.POP() 30
                ^^
SyntaxError: invalid syntax
>>> list1.reverse()
>>> list1
[55, 45, 35, 20, 10, 40, 30, 10]
>>> list1.reverse()
>>> list1
[10, 30, 40, 10, 20, 35, 45, 55]
>>> list1=['varun','ravinder','amrit']
>>> list1.reverse()
>>> list1
['amrit', 'ravinder', 'varun']
>>> list1.sort()
>>> list1
['amrit', 'ravinder', 'varun']
>>> list1=[10,20,30,40,50,10,20,35,45,55]
>>> list1.sort(reverse=true)
Traceback (most recent call last):
  File "<python-input-54>", line 1, in <module>
    list1.sort(reverse=true)
                       ^^^^
NameError: name 'true' is not defined. Did you mean: 'True'?
>>> list1.sorted(list1)
Traceback (most recent call last):
  File "<python-input-55>", line 1, in <module>
    list1.sorted(list1)
    ^^^^^^^^^^^^
AttributeError: 'list' object has no attribute 'sorted'. Did you mean: 'sort'?
>>> list1
[10, 20, 30, 40, 50, 10, 20, 35, 45, 55]
>>> min(list1)
10
>>> max(list1)
55
>>> sum(list1)
315

