# Python
<h1>Python Data Types 
<hr>

<h2>1️⃣ Python Data Types</h2>
<p>A <b>data type</b> defines the type of value a variable can store.</p>

<ul>
  <li>Numeric</li>
  <li>Boolean</li>
  <li>Sequence</li>
  <li>Set</li>
  <li>Dictionary</li>
  <li>NoneType</li>
</ul>

<hr>

<h2>2️⃣ Numeric Data Types</h2>

<h3>🔹 int (Integer)</h3>
<p>Stores whole numbers.</p>
<pre>
a = 10
b = -5
</pre>

<h3>🔹 float</h3>
<p>Stores decimal numbers.</p>
<pre>
x = 3.14
y = -2.5
</pre>

<h3>🔹 complex</h3>
<p>Stores real and imaginary values.</p>
<pre>
c = 2 + 3j
</pre>

<hr>

<h2>3️⃣ Boolean Data Type</h2>
<p>Used for logical operations.</p>
<pre>
is_active = True
is_done = False
</pre>

<hr>

<h2>4️⃣ Sequence Data Types</h2>

<h3>🔹 String</h3>
<p>A collection of characters enclosed in quotes.</p>
<pre>
name = "Python"
</pre>

<h3>🔹 List</h3>
<p>A collection of items enclosed in square brackets.</p>
<pre>
numbers = [1, 2, 3, 4]
</pre>

<h3>🔹 Tuple</h3>
<p>Similar to a list but immutable.</p>
<pre>
data = (10, 20, 30)
</pre>

<hr>

<h2>5️⃣ String (Detailed Concept)</h2>

<p><b>Definition:</b> A string is an immutable sequence of characters.</p>

<ul>
  <li>Immutable</li>
  <li>Indexed</li>
  <li>Stored in quotes</li>
</ul>

<pre>
text = "Hello"
print(text[0])
</pre>

<h3>String Operations</h3>
<pre>
s = "Python"
print(len(s))
print(s.upper())
print(s.lower())
print(s[::-1])
</pre>

<hr>

<h2>6️⃣ List (Detailed Concept)</h2>

<p><b>Definition:</b> A list is a mutable collection that can store different data types.</p>

<ul>
  <li>Mutable</li>
  <li>Indexed</li>
  <li>Allows duplicate values</li>
</ul>

<pre>
my_list = [1, "Python", 3.5, True]
</pre>

<h3>List Operations</h3>
<pre>
lst = [10, 20, 30]
lst.append(40)
lst.insert(1, 15)
lst.remove(20)
lst.pop()
</pre>

<hr>

<h2>7️⃣ String vs List</h2>

<table border="1" cellpadding="5">
  <tr>
    <th>Feature</th>
    <th>String</th>
    <th>List</th>
  </tr>
  <tr>
    <td>Mutable</td>
    <td>No</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Stores</td>
    <td>Characters</td>
    <td>Any Data Type</td>
  </tr>
  <tr>
    <td>Brackets</td>
    <td>Quotes</td>
    <td>Square Brackets</td>
  </tr>
</table>

<hr>

<h2>8️⃣ Set Data Type</h2>
<p>Stores unique values.</p>
<pre>
s = {1, 2, 3, 3}
print(s)
</pre>

<hr>

<h2>9️⃣ Dictionary Data Type</h2>
<p>Stores data in key-value pairs.</p>
<pre>
student = {
  "name": "Sunil",
  "age": 22
}
</pre>

<hr>

<h2>🔟 None Data Type</h2>
<p>Represents no value.</p>
<pre>
x = None
</pre>

<hr>

<h1>Python List 

<hr>

<h2>1️⃣ What is a List?</h2>
<p>
A <b>list</b> is a collection of items stored in a single variable.
</p>

<p><b>Definition:</b> A list is a <b>mutable</b>, <b>ordered</b> collection that can store multiple data types.</p>

<pre>
my_list = [10, 20, 30]
</pre>

<hr>

<h2>2️⃣ Characteristics of List</h2>
<ul>
  <li>Mutable (values can be changed)</li>
  <li>Ordered</li>
  <li>Indexed</li>
  <li>Allows duplicate values</li>
  <li>Stores different data types</li>
</ul>

<hr>

<h2>3️⃣ Creating a List</h2>

<pre>
numbers = [1, 2, 3, 4]
data = ["Python", 10, 2.5, True]
empty_list = []
</pre>

<hr>

<h2>4️⃣ Accessing List Elements</h2>

<pre>
lst = [10, 20, 30, 40]
print(lst[0])
print(lst[-1])
</pre>

<hr>

<h2>5️⃣ Modifying List Elements</h2>

<pre>
lst = [10, 20, 30]
lst[1] = 25
print(lst)
</pre>

<hr>

<h2>6️⃣ List Methods</h2>

<h3>🔹 append()</h3>
<pre>
lst = [1, 2]
lst.append(3)
</pre>

<h3>🔹 insert()</h3>
<pre>
lst = [1, 3]
lst.insert(1, 2)
</pre>

<h3>🔹 remove()</h3>
<pre>
lst = [1, 2, 3]
lst.remove(2)
</pre>

<h3>🔹 pop()</h3>
<pre>
lst = [1, 2, 3]
lst.pop()
</pre>

<hr>

<h2>7️⃣ List Slicing</h2>

<pre>
lst = [10, 20, 30, 40, 50]
print(lst[1:4])
print(lst[:3])
print(lst[::2])
</pre>

<hr>

<h2>8️⃣ Looping Through a List</h2>

<pre>
lst = [10, 20, 30]
for x in lst:
    print(x)
</pre>

<hr>

<h2>9️⃣ Common List Functions</h2>

<pre>
lst = [5, 2, 9, 1]

print(len(lst))
print(max(lst))
print(min(lst))
print(sum(lst))
</pre>

<hr>

<h2>🔟 List vs Tuple</h2>

<table border="1" cellpadding="5">
  <tr>
    <th>Feature</th>
    <th>List</th>
    <th>Tuple</th>
  </tr>
  <tr>
    <td>Mutable</td>
    <td>Yes</td>
    <td>No</td>
  </tr>
  <tr>
    <td>Brackets</td>
    <td>[ ]</td>
    <td>( )</td>
  </tr>
  <tr>
    <td>Performance</td>
    <td>Slower</td>
    <td>Faster</td>
  </tr>
</table>

<hr>

<h1>Python Control Flow & Loop Concepts</h1>

<hr>

<h2>Loop</h2>
<p>
A <b>loop</b> is used to execute a block of code repeatedly until a condition is satisfied.
</p>

<hr>

<h2>for Loop</h2>
<p>
A <b>for loop</b> is used to iterate over a sequence such as a list, string, or range.
</p>

<hr>

<h2>while Loop</h2>
<p>
A <b>while loop</b> executes a block of code as long as a given condition is true.
</p>

<hr>

<h2>if Statement</h2>
<p>
An <b>if statement</b> executes a block of code only when a condition is true.
</p>

<hr>

<h2>else Statement</h2>
<p>
An <b>else statement</b> executes a block of code when the if condition is false.
</p>

<hr>

<h2>elif Statement</h2>
<p>
An <b>elif statement</b> is used to check multiple conditions after an if statement.
</p>

<hr>

<h2>break Statement</h2>
<p>
The <b>break</b> statement is used to terminate a loop immediately.
</p>

<hr>

<h2>continue Statement</h2>
<p>
The <b>continue</b> statement skips the current iteration of a loop and moves to the next iteration.
</p>

<hr>

<h2>pass Statement</h2>
<p>
The <b>pass</b> statement is a null operation used when a statement is syntactically required but no action is needed.
</p>

<hr>

<h1>Python Loops – for & while 

<hr>

<h2>1️⃣ What is a Loop?</h2>
<p>
A <b>loop</b> is used to execute a block of code repeatedly until a condition is satisfied.
</p>

<hr>

<h2>2️⃣ Types of Loops in Python</h2>
<ul>
  <li>for loop</li>
  <li>while loop</li>
</ul>

<hr>

<h2>3️⃣ for Loop</h2>
<p>
A <b>for loop</b> is used to iterate over a sequence like range, list, string.
</p>

<pre>
for i in range(5):
    print(i)
</pre>

<hr>

<h2>4️⃣ Perfect Number Program</h2>
<p>
A <b>perfect number</b> is a number whose sum of factors (excluding itself) is equal to the number.
</p>

<pre>
a = 9
b = 0
for i in range(1, a):
    if a % i == 0:
        b = b + i

if b == a:
    print("given number is perfect")
else:
    print("given number is not perfect number")
</pre>

<hr>

<h2>5️⃣ Reverse a Number (for loop)</h2>

<pre>
a = str(1234)
b = ""
for i in a:
    b = i + b
print(b)
</pre>

<hr>

<h2>6️⃣ Reverse a Number (while loop)</h2>

<pre>
a = 1234
b = 0
while a > 0:
    c = a % 10
    b = (b * 10) + c
    a = a // 10
print(b)
</pre>

<hr>

<h2>7️⃣ Sum of Digits using while loop</h2>

<pre>
a = 1234
c = 0
while a > 0:
    d = a % 10
    c = c + d
    a = a // 10
print(c)
</pre>

<hr>

<h2>8️⃣ Prime Number Check</h2>

<pre>
a = 4
c = 0
for i in range(1, a + 1):
    if a % i == 0:
        c = c + 1

if c == 2:
    print("it is a prime")
else:
    print("it is not a prime")
</pre>

<hr>

<h2>9️⃣ Prime Numbers from 1 to 100</h2>

<pre>
for i in range(2, 100):
    c = 0
    for j in range(1, i + 1):
        if i % j == 0:
            c = c + 1
    if c == 2:
        print(i, end=" ")
</pre>

<hr>

<h2>🔟 Pattern Printing using Nested Loops</h2>

<h3>Star Pattern</h3>
<pre>
for i in range(1, 6):
    print("*" * i)
</pre>

<h3>Number Pattern</h3>
<pre>
for i in range(1, 6):
    for j in range(1, i + 1):
        print(j, end="")
    print()
</pre>

<hr>

<h2>1️⃣1️⃣ Table Program (for loop)</h2>

<pre>
n = 5
for i in range(1, 11):
    print(f"{n} x {i} = {n*i}")
</pre>

<hr>

<h2>1️⃣2️⃣ Table Program (while loop)</h2>

<pre>
n = 1
while n < 11:
    print(f"5 x {n} = {5*n}")
    n = n + 1
</pre>

<hr>

<h2>1️⃣3️⃣ Extract Odd Numbers from Nested List</h2>

<pre>
L = [[12, 34, 25], [1, 45, 0]]
a = []

for i in L:
    for j in i:
        if j % 2 != 0:
            a.append(j)

print(a)
</pre>

<hr>

<h2>1️⃣4️⃣ Current and Previous Number Sum</h2>

<pre>
pn = 0
for i in range(10):
    s = i + pn
    print(f"current number:{i} previous number:{pn} sum:{s}")
    pn = i
</pre>

<hr>

<h2>1️⃣5️⃣ Merge Two Dictionaries using Loop</h2>

<pre>
d1 = {"a": 1, "b": 2}
d2 = {"b": 3, "c": 4}
d = {}

for k in d1:
    d[k] = d1[k]

for k in d2:
    d[k] = d2[k]

print(d)
</pre>

<hr>

<h1>Python Functions</h1>

<h2>Definition</h2>
<p>A function is a reusable block of code that performs a specific task.</p>

<h2>Syntax</h2>
<pre>
def function_name(parameters):
    statements
    return value
</pre>

<h2>Example 1: Simple Function</h2>
<pre>
def greet():
    print("Hello World")

greet()
</pre>

<h2>Function with Parameters</h2>
<p>A function that accepts input values.</p>
<pre>
def add(a, b):
    return a + b

print(add(5, 3))
</pre>

<h2>Function with Return Value</h2>
<p>A function that sends a result back to the caller.</p>
<pre>
def square(n):
    return n * n

print(square(4))
</pre>

<h2>Default Arguments</h2>
<p>Parameters with default values.</p>
<pre>
def greet(name="User"):
    print("Hello", name)

greet()
greet("Sunil")
</pre>

<h2>Keyword Arguments</h2>
<pre>
def student(name, age):
    print(name, age)

student(age=20, name="Ravi")
</pre>

<h2>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Python Modularization & Functional Programming</title>
</head>
<body>

<h1>Python Modularization Using Functions</h1>

<h2>1. Function (Modularization)</h2>
<p><b>Definition:</b> A function is a reusable block of code that performs a specific task.</p>
<pre>
def add(a, b):
    return a + b
</pre>

<h2>2. Single * ( *args )</h2>
<p><b>Definition:</b> <code>*args</code> allows a function to accept multiple arguments as a tuple.</p>
<pre>
def show(*args):
    return args

show(1, 2, 3)
</pre>

<h2>3. Double ** ( **kwargs )</h2>
<p><b>Definition:</b> <code>**kwargs</code> allows a function to accept multiple keyword arguments as a dictionary.</p>
<pre>
def show_kw(**kwargs):
    return kwargs

show_kw(a=10, b=20)
</pre>

<h2>4. Lambda Function</h2>
<p><b>Definition:</b> A lambda function is a small anonymous function written in one line.</p>
<pre>
square = lambda x: x * x
square(5)
</pre>

<h2>5. map()</h2>
<p><b>Definition:</b> <code>map()</code> applies a function to each element of an iterable.</p>
<pre>
nums = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, nums))
</pre>

<h2>6. filter()</h2>
<p><b>Definition:</b> <code>filter()</code> selects elements from an iterable based on a condition.</p>
<pre>
nums = [1, 2, 3, 4]
result = list(filter(lambda x: x % 2 == 0, nums))
</pre>

<h2>7. reduce()</h2>
<p><b>Definition:</b> <code>reduce()</code> reduces an iterable to a single value by applying a function repeatedly.</p>
<pre>
from functools import reduce
nums = [1, 2, 3, 4]
result = reduce(lambda a, b: a + b, nums)
</pre>

<h2>8. map() with filter()</h2>
<p><b>Definition:</b> First filters elements, then applies a function using <code>map()</code>.</p>
<pre>
nums = [1, 2, 3, 4]
result = list(
    map(lambda x: x * 2,
        filter(lambda x: x % 2 == 0, nums))
)
</pre>

<h2>9. filter() with map()</h2>
<p><b>Definition:</b> First transforms elements using <code>map()</code>, then filters them.</p>
<pre>
nums = [1, 2, 3, 4]
result = list(
    filter(lambda x: x > 4,
           map(lambda x: x * 2, nums))
)
</pre>

<h2>10. reduce() with map() and filter()</h2>
<p><b>Definition:</b> Combines <code>filter()</
