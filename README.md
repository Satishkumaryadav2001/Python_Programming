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
