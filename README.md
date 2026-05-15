# Python Codes 🐍

A collection of essential Python programs demonstrating fundamental programming concepts, perfect for understanding basic logic and preparing for technical interviews.

## 📋 About

**Python Codes** is a repository containing 10 beginner to intermediate level Python scripts that cover core programming concepts. Each script is concise, well-commented, and focuses on important logical thinking required for:
- 🎓 Building fundamental programming skills
- 💼 Preparing for technical interviews and coding rounds
- 🏆 Understanding core Python concepts
- 📚 Quick reference for common problems
- 🔍 Learning problem-solving approaches

## 📂 Code Structure

This repository contains individual Python files organized by problem:

```
Python_Codes/
├── q1.py                 # Print numbers from 1 to 5
├── q2.py                 # Calculate squares from 1 to 5
├── q3.py                 # Find even numbers between 1 to 10
├── q4.py                 # Calculate sum from 1 to 10
├── q5.py                 # Reverse a string
├── q6.py                 # Count vowels in a string
├── q7.py                 # Generate first 10 Fibonacci numbers
├── q8.py                 # Calculate factorial of a number
├── q9.py                 # Check if a number is prime
├── q10.py                # Count character frequency
└── README.md             # This file
```

## 🎯 Programs Overview

### Q1: Print Numbers from 1 to 5
```python
#no from 1 to 5
for i in range(1,6):
    if i<5:
        print(i,end=" ")
    else:
        print(i,end="")
```
**Concept**: Loops, conditional statements, string formatting

---

### Q2: Calculate Squares from 1 to 5
```python
#square from 1 to 5
for i in range(1,6):
    print(i**2,end=" ")
```
**Output**: `1 4 9 16 25`  
**Concept**: Loop iteration, exponentiation operator

---

### Q3: Find Even Numbers from 1 to 10
```python
#even no b/w 1 to 10
for i in range(1,11,1):
    if(i%2==0):
        print(i,end=" ")
```
**Output**: `2 4 6 8 10`  
**Concept**: Loops, modulo operator, conditional logic

---

### Q4: Sum of Numbers from 1 to 10
```python
#sum of no from 1 to 10
sum = 0
for i in range(1,11):
    sum+=i
print("sum =",sum)
print(f"sum = {sum}")
```
**Output**: `55`  
**Concept**: Accumulation, f-strings, variable operations

---

### Q5: Reverse a String
```python
#reverse the given string
word="Python"
for i in range(len(word)-1,-1,-1):
    print(word[i].upper(),end="")
```
**Output**: `NOHTYP`  
**Concept**: String manipulation, negative indexing, string methods

---

### Q6: Count Vowels in a String
```python
word=input("Enter the word")
vowel='aeiouAEIOU'
count=0
v=''
for i in word:
    if i in vowel:
        v=v+" "+i
        count+=1
print(count)
print(v)
```
**Concept**: String iteration, membership testing, input handling

---

### Q7: Fibonacci Series (First 10 Numbers)
```python
#first 10 fibbonacci series
f0=0
f1=1
print(f0,end=" ")
print(f1,end=" ")
for i in range(1,9):
    f2=f0+f1
    print(f2,end=" ")
    f0=f1
    f1=f2
```
**Output**: `0 1 1 2 3 5 8 13 21 34`  
**Concept**: Series generation, variable assignment, loop logic

---

### Q8: Calculate Factorial
```python
#factorial of the no
pro=1
n=int(input())
for i in range(1,n+1):
    pro=pro*i
print(pro)
```
**Concept**: Mathematical operations, input conversion, loop accumulation

---

### Q9: Check if Number is Prime
```python
#no is a prime or not
prime=True
n = int(input())
for i in range(2,n):
    if(n%i==0):
        prime=False
        break
if prime==False:
    print(f"{n} is not a prime no.")
else:
    print(f"{n} is a prime no.")
```
**Concept**: Conditional logic, loop control (break), boolean values

---

### Q10: Character Frequency Counter
```python
#frequency of each character
word = "programming"
frequency={}

for char in word:
    if char in frequency:
        frequency[char]+=1
    else:
        frequency[char]=1

for char,count in frequency.items():
    print(f"'{char}' : {count}")
```
**Output**: 
```
'p' : 1
'r' : 2
'o' : 1
'g' : 2
'a' : 1
'm' : 2
'i' : 1
'n' : 1
```
**Concept**: Dictionaries, key-value pairs, iteration, conditional dictionary operations

---

## 💡 Core Concepts Covered

✅ **Loop Control**
- for loops with range()
- while loops
- Loop control statements (break, continue)
- Step values and negative indexing

✅ **Conditional Statements**
- if/else/elif
- Comparison operators
- Boolean logic

✅ **Data Types**
- Strings and string methods
- Integers and arithmetic operations
- Dictionaries and key-value pairs
- Lists (implicit through iteration)

✅ **String Operations**
- Indexing and slicing
- String methods (upper(), lower())
- String concatenation
- f-strings for formatting

✅ **Mathematical Concepts**
- Fibonacci series
- Factorial calculation
- Prime number checking
- Sum and product calculations
- Modulo operator (%)
- Exponentiation operator (**)

✅ **Input/Output**
- input() function
- print() with formatting
- End parameter for print statements
- Variable output

✅ **Dictionary Operations**
- Creating dictionaries
- Checking key existence
- Adding key-value pairs
- Iterating with items()

## 🚀 Getting Started

### Prerequisites
- Python 3.6 or higher
- Any text editor or IDE (VS Code, PyCharm, Thonny, etc.)
- Terminal/Command Prompt

### How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Varunmattur/Python_Codes.git
   cd Python_Codes
   ```

2. **Run any Python file**
   ```bash
   python q1.py
   python q2.py
   python q3.py
   # and so on...
   ```

3. **View the code**
   ```bash
   cat q1.py
   # or open in your editor
   code q1.py
   ```

## 🎓 Learning Path

### Beginner Level
Start with these programs to understand basics:
- **Q1-Q4**: Loop basics, range(), basic arithmetic
- **Q2**: Understanding operators
- **Q3**: Conditional statements with loops

### Intermediate Level
Move to string and data manipulation:
- **Q5-Q6**: String operations and iteration
- **Q7**: Series generation logic
- **Q10**: Dictionary usage and data structures

### Problem Solving
Understanding algorithms:
- **Q8**: Factorial (mathematical logic)
- **Q9**: Prime checking (algorithm optimization)
- **Q7**: Fibonacci (sequence generation)

## 💪 Why These Programs?

✅ **Easy to Understand** - Small, focused programs with clear logic  
✅ **Commonly Asked** - Frequently appear in technical interviews  
✅ **Multiple Concepts** - Each program teaches multiple concepts  
✅ **Beginner Friendly** - No complex frameworks or libraries  
✅ **Fast Learning** - Quick to run and see results  

## 🎯 How to Use These Programs

1. **Read the code** - Understand what each line does
2. **Run the program** - See the output
3. **Modify it** - Change values and test
4. **Solve variations** - Try solving similar problems
5. **Analyze logic** - Understand the approach and algorithm

## 📝 Interview Preparation Tips

**For each program, understand:**
- What is the input and output?
- What algorithm is being used?
- What is the time complexity?
- What is the space complexity?
- Can it be optimized further?
- What edge cases should be handled?

**Example - Prime Number Check (Q9):**
- Input: A number n
- Output: Whether n is prime or not
- Algorithm: Trial division
- Time Complexity: O(n)
- Space Complexity: O(1)
- Optimization: Check only up to √n

## 🤝 How to Contribute

Have additional Python codes or improvements?

1. Fork the repository
2. Add your Python script with clear comments
3. Include a brief description of what it does
4. Test it thoroughly
5. Commit and push your changes
6. Open a Pull Request

## 📚 Resources for Further Learning

- [Python Official Documentation](https://docs.python.org/3/)
- [Python Tutorial - W3Schools](https://www.w3schools.com/python/)
- [GeeksforGeeks - Python](https://www.geeksforgeeks.org/python-programming-language/)
- [Real Python](https://realpython.com/)
- [HackerRank - Python](https://www.hackerrank.com/domains/python)
- [LeetCode - Easy Problems](https://leetcode.com/problemset/all/?difficulty=EASY&topicSlugs=string)

## 🔗 Related Topics to Explore

- **Algorithms**: Sorting, searching, graph algorithms
- **Data Structures**: Lists, stacks, queues, trees, graphs
- **Problem Solving**: Logic building, optimization techniques
- **Advanced Python**: Classes, OOP, decorators, generators
- **Competitive Programming**: Coding contests, problem patterns

## 💬 Discussion & Support

- 📧 Have questions? Open an [Issue](https://github.com/Varunmattur/Python_Codes/issues)
- 💡 Want to suggest a program? Start a [Discussion](https://github.com/Varunmattur/Python_Codes/discussions)

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Designed for beginners and interview preparation
- Common interview questions and solutions
- Community feedback and contributions

---

**Made with ❤️ by [Varunmattur](https://github.com/Varunmattur)**

**Repository**: 🐍 Python Codes for Learning & Interviews  
**Total Programs**: 10  
**Language**: 100% Python  
**Difficulty**: Beginner to Intermediate  
**Last Updated**: November 2024  

**Happy Learning! 🚀**