# Computer Lesson, week 1

Its necessary for middle school students to have a lesson to learn computer.

We will learn some computer related concepts, some basic operations, and some programming techniques.

This file is online: https://github.com/Bookaa/pc

Some toturial video can be download from: https://pan.baidu.com/s/12HDN-yW3r5LOQBo-4xSY4w code: 9nd2

## Python

We choose Python 3. 

Python is a programming language. It is a good choice for beginners.

I find some free online Python environment.

https://www.w3schools.com/ ,  select python, and try

https://www.learnpython.org/

https://repl.it/languages/python3

https://www.joinquant.com/ register, select "策略研究" to get a free online Jupyter Notebook.

## print and hello world

The simplest program in Python consists of a line that tells the computer a command. Traditionally, the first program of every programmer in every new language prints "Hello, World!" 

The simplest directive in Python is the "print" directive - it simply prints out a line.
```
print('hello world')
print('    *')
print('   * *')
print('  *   *')
print(' *     *')
print('*********')
print()
print(3)
print(5,6,7)
print('3 + 4 =', 3+4)
```
print without newline,
```
print('first part',end='')
print('same line')
```
Using Print _ Python for Beginners [5 of 44]-FhoASwgvZHk.mkv

Demo - Hello World _ Python for Beginners [6 of 44]-wWwr0tDSqnE.mkv

## Variable
You do not need to declare variables before using them, or declare their type.

Strings are defined either with a single quote or a double quotes.
```
a=1
b=2
c=a+b
a=a+1
b+=1
s = "hello" + ' ' + 'world'
print(s,a,b,c)
```
after you get the value of a variable, its safe to change it
```
a = 1
b = a
a = 2
print('b will remain its value.', a, b)
```
how to exchange 2 variables
```
a=3; b=5
c = a; a = b; b = c
print(a, b)
a, b = b, a
print('exchange back', a, b)
```


Tutorial1.mkv from 7:59 print, variable

## comments

Python comment with #. Python do not have multi-line / block comments. We can use multi-line string instead.


```
# this is comment
''' multi line
line1
line2
'''
print('hello')
```

## if statement

A program sometimes may have to make choices. These choices can execute different code depending on certain condition.

In Python the if statement is used for conditional execution or branching. 

```
a = 2
b = 3
if a < b:
    a = b
```

optional else,


```
a = 2
b = 3
if a < b:
    print('a is smaller')
else:
    print('a is larger')
```

optional elif


```
a = 2
if a == 1:
    print('a is one')
    print('one is great')
elif a == 2:
    print('a is two')
elif a == 3:
    print('a is three')
else:
    print('a is unknown')
```

![image](https://www.dropbox.com/s/ld3sayan37tq4uh/IfCondition.png?raw=1)

![image](https://www.dropbox.com/s/qkuligylu0gfmq5/IfelseCondition.png?raw=1)

Tutorial2.mkv 6:18 if else

Tutorial3.mkv 1:38 comments, the pound sign, the hash tag 2:21 function

Comments _ Python for Beginners [7 of 44]-kEuVvUc1Zec.mkv

Demo - Comments _ Python for Beginners [8 of 44]-fbek7n6ecWM.mkv

## Indentation and Blocks

Python uses indentation for blocks, instead of curly braces. Both tabs and spaces are supported, but the standard indentation requires standard Python code to use four spaces. 

```
x = 1
if x == 1:
    print('a block should')
    print('ident with same')
    print('spaces and tabs')
```

用缩进定义块，是Python特色。有人酷爱，有人不喜。

## while statement

## 上机

open these free online Python environment,

https://www.w3schools.com/ ,  select python, and try

https://www.learnpython.org/

https://repl.it/languages/python3

https://www.joinquant.com/ ，need user register, select "策略研究" to get a free online Jupyter Notebook.

try 'hello world', try print something, try 'if', 'else', 'elif', familiar with indentation.

try the 'while' statement, try 'break', 'continue'.

learn 'for' loop online.


try to get
```math
1 + 2 + 3 + ... + 100\\[2ex]
1 + 2^2 + 3^2 + 4^2 + \cdots + 9^2
```
and etc. try to get Pi
```math
\frac{\pi}{4}=1-\frac{1}{3}+\frac{1}{5}-\frac{1}{7}+\cdots\\[2ex]
\frac{\pi}{4}=4 \arctan(\frac{1}{5})-\arctan(\frac{1}{239})\\[2ex]
\arctan(x)=1-\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}+\cdots\\
```
