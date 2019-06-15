# Computer Science Questions

# Table of Contents

1. [Big O Notations](#Big-O-Notation)
2. [Data Structures](#Data-Structures)
   - [RAM](#RAM)
   - [Binary numbers](#Binary-numbers)
3. [Fixed-width Integers](#Fixed-width-Integers)
4. [Third Example](#third-example)

## Big O Notation

<details>
<summary>What represents big O notation?</summary>
Big O notation represents wow long an algorithms takes to run. It describes how quickly it grows relative to the input, as the input gets arbitrarily large.
</details>
<br>

<details>
<summary>Give example of Big O notation for various input sizes</summary>
<p>

```
O(1): constant complexity
O(N): linear complexity
O(N^2): n-squared, quadratic complexity
O(2^N): exponential complexity
```
</p>
</details>
<br>

<details>
<summary>Why we remove constants from big O notation calculation?</summary>
Big O notation we're looking at what happens as nn gets arbitrarily large. As n gets really big, adding e.g 50 or dividing by 2 has a decreasingly significant effect.
</details>
<br>

**References:**

- [Big O notationfor beginner tech interview candidate](http://www.zsoltnagy.eu/big-o-notation-for-beginner-tech-interview-candidates/)

- [Big 0 notation time and space complexity](https://www.interviewcake.com/article/java/big-o-notation-time-and-space-complexity)

- [Big-O Complexity Chart](http://bigocheatsheet.com/)

## Data Structures

#### RAM

<details>
<summary>What is RAM?</summary>
Random Access Memory.
</details>
<br>

<details>
<summary>What is usual size of RAM?</summary>
8-16GB
</details>
<br>

<details>
<summary>What does memory controler do?</summary>
The memory controller does the actual reading and writing to and from RAM. It has a direct connection to each shelf of RAM.

[Memory Controler - Wikipedia](https://en.wikipedia.org/wiki/Memory_controller)

</details>
<br>

<details>
<summary>What happens when processor asks for the contents of given memory address?</summary>
When the processor asks for the contents of a given memory address, the memory controller also sends the contents of a handful of nearby memory addresses. And the processor puts all of it in the cache.
</details>
<br>

<details>
<summary>How shelves in RAM are called?</summary>
Addresses.
</details>
<br>

<details>
<summary>How many bits each shelve holds?</summary>
8 bits = 1 byte
</details>
<br>

<details>
<summary>What happens to the data stored in RAM when the computer is turned of?</summary>
Data stored in RAM is volatile which means if the computer is turned off then data is lost.
</details>
<br>

### Binary numbers

<details>
<summary>What are places n binary numbers??</summary>
The places in binary (base 2) are sequential powers of 2.
</details>
<br>

<details>
<summary>What is value of 0001 and 1001?</summary>
0001 => 1
1001 => 9 (8+0+0+1)
</details>
<br>

<details>
<summary>What are unsigned integers??</summary>
Non-negative values.
</details>
<br>

<details>
<summary>How negative numbers are stored in binary?</summary>
We reserve the leftmost bit for expressing the sign of the number. 0 for positive and 1 for negative.
</details>
<br>

### Fixed-width Integers

### Array

### Strings

### Pointers

### Dynamic Arrays

### Linked Lists
