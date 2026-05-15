# Python Codes 🐍

A comprehensive collection of small but important Python scripts and code snippets designed to strengthen fundamental programming logic and prepare for technical interviews and coding rounds.

## 📋 About

**Python Codes** is a curated repository of essential Python programs covering basic to intermediate concepts. These concise yet powerful scripts are perfect for:
- 🎓 Learning fundamental programming concepts
- 💼 Preparing for technical interviews
- 🏆 Practicing problem-solving skills
- 📚 Understanding core algorithms and data structures
- 🔍 Quick reference for common coding patterns

Whether you're a beginner learning Python or preparing for your next coding interview, this repository provides bite-sized solutions that demonstrate important programming principles.

## 📂 What's Inside

This repository contains Python scripts organized by topics:

### Core Concepts
- **Variables & Data Types** - Working with strings, numbers, lists, dictionaries, tuples, sets
- **Control Flow** - Conditional statements (if/else), loops (for, while)
- **Functions** - Function definition, parameters, return values, scope
- **String Manipulation** - String methods, formatting, pattern matching

### Data Structures
- **Lists** - Creation, manipulation, sorting, searching
- **Dictionaries** - Key-value pairs, iteration, operations
- **Tuples & Sets** - Immutable sequences, unique elements
- **Stacks & Queues** - LIFO, FIFO implementations
- **Linked Lists** - Node-based data structures

### Algorithms
- **Sorting** - Bubble sort, insertion sort, merge sort, quick sort
- **Searching** - Linear search, binary search
- **Recursion** - Recursive functions, problem decomposition
- **Pattern Matching** - String pattern finding algorithms
- **Mathematical Algorithms** - Prime numbers, GCD, Fibonacci, factorials

### Problem Solving
- **String Problems** - Palindromes, anagrams, rotation
- **Array/List Problems** - Two sum, reverse, duplicate finding
- **Math Problems** - Number manipulation, series, sequences
- **Logic Puzzles** - Brain teasers and logical problems

### Object-Oriented Programming
- **Classes & Objects** - Class definition, inheritance, polymorphism
- **Encapsulation** - Private/public methods, properties
- **Abstraction** - Abstract classes, interfaces
- **Design Patterns** - Common OOP patterns

## 🎯 Why These Codes Matter

✅ **Interview Preparation** - Cover frequently asked problems in technical rounds  
✅ **Logic Building** - Strengthen your understanding of fundamental concepts  
✅ **Code Efficiency** - Learn optimal approaches to solve problems  
✅ **Quick Learning** - Small, focused examples for quick comprehension  
✅ **Reference Guide** - Quick lookup for common patterns and solutions  

## 🚀 Getting Started

### Prerequisites
- Python 3.6 or higher
- Any text editor or IDE (VS Code, PyCharm, etc.)
- Terminal or command prompt

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Varunmattur/Python_Codes.git
   cd Python_Codes
   ```

2. **Run any Python script**
   ```bash
   python script_name.py
   ```

3. **View the code**
   ```bash
   cat script_name.py
   # or open in your editor
   code script_name.py
   ```

## 📁 File Organization

```
Python_Codes/
├── strings/                    # String manipulation problems
│   ├── palindrome.py
│   ├── anagram.py
│   ├── reverse_string.py
│   └── pattern_matching.py
├── arrays_lists/              # List and array operations
│   ├── two_sum.py
│   ├── find_duplicates.py
│   ├── rotate_array.py
│   └── binary_search.py
├── math_logic/                # Mathematical problems
│   ├── fibonacci.py
│   ├── prime_numbers.py
│   ├── factorial.py
│   └── gcd_lcm.py
├── data_structures/           # Data structure implementations
│   ├── linked_list.py
│   ├── stack.py
│   ├── queue.py
│   └── binary_tree.py
├── sorting_searching/         # Sorting and searching algorithms
│   ├── bubble_sort.py
│   ├── merge_sort.py
│   ├── quick_sort.py
│   └── binary_search.py
├── recursion/                 # Recursive solutions
│   ├── fibonacci_recursive.py
│   ├── factorial_recursive.py
│   └── tower_of_hanoi.py
├── oops/                      # Object-oriented programming
│   ├── class_basics.py
│   ├── inheritance.py
│   └── polymorphism.py
└── README.md                  # This file
```

## 💡 How to Use

1. **Browse through the files** - Look for topics that interest you
2. **Read the code** - Study the implementation and logic
3. **Run the script** - Execute it to see the output
4. **Modify & Experiment** - Change values and test your understanding
5. **Use as reference** - Copy patterns for your own projects

## 📚 Example Programs

### Finding if a Number is Prime
```python
def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n**0.5) + 1):
        if n % i == 0:
            return False
    return True

print(is_prime(17))  # Output: True
```

### Checking if a String is Palindrome
```python
def is_palindrome(s):
    clean_s = s.lower().replace(" ", "")
    return clean_s == clean_s[::-1]

print(is_palindrome("A man a plan a canal Panama"))  # Output: True
```

### Binary Search Implementation
```python
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1

arr = [1, 3, 5, 7, 9, 11]
print(binary_search(arr, 7))  # Output: 3
```

## 🎓 Learning Path

**Beginner Level:**
- Start with basic syntax and variables
- Move to control flow (if/else, loops)
- Practice string and list operations

**Intermediate Level:**
- Explore functions and recursion
- Learn about data structures
- Understand sorting and searching

**Advanced Level:**
- Master algorithms and optimization
- Study OOP concepts
- Practice complex problem-solving

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-code`)
3. Add your Python script with clear comments
4. Include a brief description of what the code does
5. Commit your changes (`git commit -m 'Add new Python code'`)
6. Push to the branch (`git push origin feature/new-code`)
7. Open a Pull Request

## 📝 Code Quality Guidelines

- ✅ Write clear, readable code
- ✅ Add comments explaining the logic
- ✅ Follow PEP 8 style guide
- ✅ Include example usage or test cases
- ✅ Optimize for clarity over complexity

## 🔗 Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [PEP 8 Style Guide](https://pep8.org/)
- [Real Python Tutorials](https://realpython.com/)
- [GeeksforGeeks Python](https://www.geeksforgeeks.org/python-programming-language/)
- [LeetCode - Practice Problems](https://leetcode.com/)
- [HackerRank - Coding Challenges](https://www.hackerrank.com/)

## 💪 Tips for Interview Preparation

1. **Practice Regularly** - Code everyday to build muscle memory
2. **Understand the Logic** - Don't just memorize solutions
3. **Optimize Your Code** - Think about time and space complexity
4. **Test Edge Cases** - Consider boundary conditions
5. **Communicate** - Explain your approach while coding
6. **Study Patterns** - Recognize common problem patterns

## 📊 Complexity Analysis

Each script should demonstrate understanding of:
- **Time Complexity** - How runtime scales with input size
- **Space Complexity** - How memory usage scales with input size
- **Trade-offs** - Speed vs. memory, readability vs. optimization

## 🎯 Practice Problems by Difficulty

**Easy:**
- Reverse a string
- Check palindrome
- Find maximum in array
- Count vowels

**Medium:**
- Two sum problem
- Merge sorted arrays
- Rotate array
- Find duplicates

**Hard:**
- Merge k sorted lists
- Longest substring without repeating
- Word ladder
- Median of sorted arrays

## 📞 Support & Questions

Have questions or need clarification?
- 📧 Open an [Issue](https://github.com/Varunmattur/Python_Codes/issues)
- 💬 Start a [Discussion](https://github.com/Varunmattur/Python_Codes/discussions)

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Inspired by common interview questions
- Solutions based on best practices
- Community contributions and feedback
- All learners preparing for technical interviews

---

**Made with ❤️ by [Varunmattur](https://github.com/Varunmattur)**

**Repository**: 🐍 Python Codes for Learning & Interviews  
**Language**: 100% Python  
**Last Updated**: November 2024  

**Happy Coding! 🚀**