# Python
<h1>Python Data Types – Complete Guide</h1>

<h2>📌 Learning Outcomes</h2>
<ul>
  <li>Understand Python data types</li>
  <li>Identify mutable and immutable data types</li>
  <li>Work confidently with Strings and Lists</li>
  <li>Apply concepts using clear examples</li>
  <li>Build a strong Python foundation</li>
</ul>

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

<h2>✅ Summary</h2>
<ul>
  <li>Python supports multiple data types</li>
  <li>Strings are immutable</li>
  <li>Lists are mutable</li>
  <li>Data types are the foundation of Python</li>
</ul>

<p><b>✔️ This HTML content is ready to paste directly into GitHub README.</b></p>

