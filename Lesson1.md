# Computer Lesson, part 1

Its necessary for middle school students to have a lesson to learn computer. Computer knowledge is essential. The first requirement in any job listing is about computer skills.

We will learn some computer related concepts, terminology, some basic operations, and some programming techniques.

This file is online: https://github.com/Bookaa/pc

Some tutorial video can be download from: https://pan.baidu.com/s/12HDN-yW3r5LOQBo-4xSY4w code: 9nd2

## Why should we learn about computers

- Smartphones, tablets are computers, and also desktop computers, laptop computers.
- Having a general understanding of computers can help you function in today's world, and it can prevent you from getting left behind. 
- Computers help you work faster
- Computers can answer almost any question
- A computer can teach you almost anything
- Understanding computer terminology helps with other technology
- Reduces the chance of being tricked or scammed
- Resolve problems and questions faster
- Computers and robots are replacing jobs. And they create new jobs concerned.
- Learning about computer can help you find a job
- Computers can make money


reference video:

Computer Science is Changing Everything-QvyTEx1wyOY.mkv


## Python

We choose Python 3. 

Python is a programming language. It is a good choice for beginners.

some free online Python environment:

https://www.w3schools.com/ ,  select python, and try

https://www.learnpython.org/

https://repl.it/languages/python3

https://www.joinquant.com/ ，user register, select "策略研究" to get a free online Jupyter Notebook.

## Python: hello world

The simplest program in Python consists of a line that tells the computer a command. Traditionally, the first program of every programmer in every new language prints "Hello, World!" 

The simplest directive in Python is the "print" directive - it simply prints out a line.

Strings are defined either with a single quote or a double quotes.

```python
print('hello world')
print('    *')
print('   * *')
print('  *   *')
print(' *     *')
print('*********')
print() # print a empty line
print(3)
print(5,6,7)
print('3 + 4 =', 3+4)
```
print without newline,
```python
print('first part',end='')
print('same line') # will print 'first partsome line' in one line
```
reference video :

Using Print _ Python for Beginners [5 of 44]-FhoASwgvZHk.mkv

Demo - Hello World _ Python for Beginners [6 of 44]-wWwr0tDSqnE.mkv

## What is Python
Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.

Guido van Rossum, author of the Python programming language. 

Life's pathetic, let's Pythonic.

interpreted, extremely flexible, functional, procedural, object oriented, web development, human readable, starter language, community, high-level, dynamic semantics, general-purpose, straightforward syntax

我的总结：

* Python是研究机器学习，神经网络，人工智能的首选语言
* 脚本语言，交互
* 初学编程首选语言，易学
* 功能强大
* 最丰富的库资源
* 开源，可移植，可部署在几乎所有平台,portable
* 语法优美，易阅读
* 不容易出错，排错容易

reference video:

Introducing Python _ Python for Beginners [2 of 44].mkv

## Python: Variable
Variables are containers for storing data values.

Unlike other programming languages, Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

```python
a=1
b=2
c=a+b
a=a+1
b+=1
s = "hello" + ' ' + 'world'
print(s,a,b,c)
```
```python
a = 3; b = 4
a, b = 5, 6
a, b = [5, 6]
a, b = (5, 6)
(a, b) = (5, 6)
(a, b, c) = [7, 8, 9]
```
```python
a = 1
b = a
a = 2
print('b will remain its value.', a, b)
```
how to exchange 2 variables
```python
a=3; b=5
c = a; a = b; b = c
print(a, b)
a, b = b, a
print('exchange back', a, b)
```
reference video:

Tutorial1.mkv from 7:59 print, variable

## Python: comments
Comments can be used to explain Python code.

Comments can be used to make the code more readable.

Comments can be used to prevent execution when testing code.

Single-line comments are created simply by beginning a line with the hash (#) character, the pound sign, the hash tag.

Python do not have multi-line / block comments. We can use multi-line string instead.


```python
# this is comment
''' multi line string as comment
line1
line2
'''
print('hello') # comments can be placed at the end of a line
```

reference video:

Tutorial3.mkv 1:38 comments, 2:21 function

Comments _ Python for Beginners [7 of 44]-kEuVvUc1Zec.mkv

Demo - Comments _ Python for Beginners [8 of 44]-fbek7n6ecWM.mkv

## Python: if statement

A program sometimes may have to make choices. These choices can execute different code depending on certain condition.

In Python the if statement is used for conditional execution or branching. 

```python
a = 2
b = 3
if a < b:
    a = b # now a is the largest
```

optional else,


```python
a = 2
b = 3
if a < b:
    print('a is smaller')
else:
    print('a is larger')
```

optional elif


```python
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

flow chart:

<img src="https://www.dropbox.com/s/ld3sayan37tq4uh/IfCondition.png?raw=1" alt="drawing" width="200"/>
'    '
<img src="https://www.dropbox.com/s/qkuligylu0gfmq5/IfelseCondition.png?raw=1" alt="drawing" width="200"/>
'    '
<img src="https://www.dropbox.com/s/c5arul4ydd0iqwg/WhileLoopPython.png?raw=1" alt="drawing" width="200"/>

reference video:

Tutorial2.mkv 6:18 if else

## Python: Indentation and Blocks
Indentation in Python is used to create a group of statements. Many popular languages such as C, and Java uses braces ({ }) to define a block of code, Python use indentation.

The statements with the same indentation belong to the same group called a suite, or block.

Both tabs and spaces are supported, usually we use four spaces. 

```python
x = input('key in a value:')
if x > 10:
    print('a block should')
    print('ident with same')
    print('spaces and tabs')
    if x == 25:
        print('x is 25')
        print('more indent level')
    print('here we back')
print('done')
```
In Python, indentation is one of the most distinctive features.

用缩进定义块，是Python特色。有人酷爱，有人不喜。

## Python: while statement
The while statement is used for repeated execution as long as an expression is true.
```python
total = 0
i = 1
while i < 10:
    total += i
    i += 1
print('total is', total)
```
With the break statement we can stop the loop anytime.

With the continue statement we can stop the current iteration, and continue with the next

```python
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1
```

```python
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
```

## IP address (Internet Protocol address)
An Internet Protocol address (IP address) is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: host or network interface identification and location addressing.

Internet Protocol version 4 (IPv4) defines an IP address as a 32-bit number. However, because of the growth of the Internet and the depletion of available IPv4 addresses, a new version of IP (IPv6), using 128 bits for the IP address, was standardized in 1998. IPv6 deployment has been ongoing since the mid-2000s.

IP addresses are written and displayed in human-readable notations, such as 172.16.254.1 in IPv4, and 2001:db8:0:1234:0:567:8:1 in IPv6. 

我的网络配置，IP是192.168.0.100 网关 192.168.0.1

My IP Address Is: IPv4: 49.75.17.186 (https://whatismyipaddress.com/)

ping apple.cn will get its IP (17.253.142.4)

localhost : 127.0.0.1

## DNS (Domain Name System)
Domain Name System (DNS) is a collection of databases that translate hostnames to IP addresses.


DNS is often referred to as the internet's phone book because it converts easy-to-remember hostnames like www.google.com, to IP addresses like 216.58.217.46. This takes place behind the scenes after you type an URL into a web browser's address bar.

Without DNS, navigating the internet wouldn't be easy since we'd have to enter the IP address of each website we want to visit.

some free DNS you can remember:
- 114.114.114.114
- 1.2.4.8
- 8.8.8.8
- 1.1.1.1

## Router 路由器
The router, at least the common home network device that is usually called a router, is the piece of network hardware that allows communication between your local home network—like your personal computers and other connected devices—and the internet.

Wireless (Wi-Fi) router 无线路由器

Wireless routers provide Wi-Fi access to smartphones, laptops, and other devices with Wi-Fi network capabilities. Also, they may provide standard Ethernet routing for a small number of wired network devices. Some Wi-Fi routers can act as a combination router and modem, converting an incoming broadband signal from your ISP(internet service provider).

modem(调制解调器): a device that connects one computer system to another using a telephone line so that data can be sent.

## Python: function
A function is a block of organized code that is used to perform a specific action. The advantages of using functions are:

- Reducing duplication of code
- Decomposing complex problems into simpler pieces
- Improving clarity of the code
- Reuse of code
- Information hiding

Function define:
- Function in Python is defined by the keyword "def"  followed by the function name and parentheses ( () ). 
- Any input parameters or arguments should be placed within these parentheses. 
- The code block within every function starts with a colon (:) and is indented.
- The statement return [expression] exits a function, optionally passing back an expression to the caller. A return statement with no arguments is the same as return None.
```python
def func1():
    print('in func1')
def func2(x,y):
    print('in func2', x+y)
def func3(x):
    return x+1
    
func1()
func2(7,8)
print(func3(5))
```
To call a function, use the function name followed by parenthesis, optional comma-separated arguments included in this parenthesis.


## von Neumann architecture

The von Neumann architecture is a computer architecture based on a 1945 description by Hungarian-American mathematician and physicist John von Neumann and others in the First Draft of a Report on the EDVAC. That document describes a design architecture for an electronic digital computer with these components:


- A processing unit that contains an arithmetic logic unit and processor registers
- A control unit that contains an instruction register and program counter
- Memory that stores data and instructions
- External mass storage
- Input and output mechanisms

冯·诺伊曼于1946年提出存储程序原理，把程序本身当作数据来对待，程序和该程序处理的数据用同样的方式储存。 冯·诺依曼体系结构的要点是：计算机的数制采用二进制；计算机应该按照程序顺序执行。人们把冯·诺伊曼的这个理论称为冯·诺伊曼体系结构。

理解要点：

- 指令与数据混合存贮
- 从古到今所有的电脑，都满足这个框架。处理单元，控制单元，寄存器，指令寄存器，存贮数据和指令的内存，外部存贮，输入输出
- 当没有电脑的时候，人们不知道电脑是什么。这个构架，让电脑成为可能。当之无愧的电脑之父。

## Python: list
The list is the most versatile datatype available in Python, which can be written as a list of comma-separated items between square brackets. Important thing about a list is that the items in a list need not be of the same type.

```python
list1 = ['physics', 'chemistry', 1997, 2000];
list2 = [1, 2, 3, 4, 5 ];
list3 = ["a", "b", "c", "d"];

a = [1,3,5]
a.index(3) # will get 1
a.index(4) # will raise exception error
4 in a # will return False
len(a) # will get 3
a[-1]  # will get 5
a[0] # will get 1
a.pop() # will get 5, and a change to [1, 3]

for n in a:
    print(n)
    
s = 0
for i in [1,3,5,7]:
    s += i;

a.append(7) # now a becomes [1,3,7]    
a.remove(3) # now a becomes [1,7]

a+=[5,9] # now a becomes [1,7,5.9]
b = a
a.pop(0) # will get 1, and a change to [7,5,9]
         # and b is [7,5.9] too, as a and b point to same value
         
list(range(5))   # will get [0, 1, 2, 3, 4]        
list(range(3,7)) # will get [3, 4, 5, 6]
list(range(7,3,-1)) # will get [7, 6, 5, 4]

a=[]      # to get a empty array
a[:] = [] # to clear a empty
a=[1]*3 # will get [1, 1, 1]
a=[1,2]*3 # will get [1, 2, 1, 2, 1, 2]

a = [1,3,5]
b = a
a.append(7)
print(a,b) # both a and b will be [1,3,5,7]
```

## Python: for statement
for loops are used when you have a block of code which you want to repeat a fixed number of times. The Python for statement iterates over the members of a sequence in order, executing the block each time.

```python
for letter in 'Python':     # traversal of a string sequence
   print ('Current Letter :', letter)
print()
fruits = ['banana', 'apple',  'mango']

for fruit in fruits:        # traversal of List sequence
   print ('Current fruit :', fruit)
   
for x in range(0, 3):
    print("We're on time", x)   
    
for x in range(1, 11):
    for y in range(1, 11):
        print('%d * %d = %d' % (x, y, x*y))
```

Like while statement, 'break' and 'continue' may include in the repeat block.

## 上机

open these free online Python environment,

https://www.w3schools.com/ ,  select python, and try

https://www.learnpython.org/

https://repl.it/languages/python3

https://www.joinquant.com/ ，need user register, select "策略研究" to get a free online Jupyter Notebook.

try 'hello world', try print something, try 'if', 'else', 'elif', familiar with indentation.

try the 'while' statement, try 'break', 'continue'.

try manipulate list, try 'for' loop.


try to get
```math
1 + 2 + 3 + ... + 100\\[2ex]
1 + 2^2 + 3^2 + 4^2 + \cdots + 9^2
```
try to get Pi from formula
```math
\frac{\pi}{4}=1-\frac{1}{3}+\frac{1}{5}-\frac{1}{7}+\cdots
```
or Machin formula
```math
\frac{\pi}{4}=4 \arctan(\frac{1}{5})-\arctan(\frac{1}{239})\\[2ex]
\arctan(x)=1-\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}+\cdots\\
```
