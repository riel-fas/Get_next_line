<p align="center"> 
<img src="https://img.shields.io/badge/-000000?style=for-the-badge&logo=42&logoColor=white)](https://42.fr))"> 
<img src="https://img.shields.io/badge/1337-000000?style=for-the-badge&logo=1337&logoColor=white)](https://1337.ma))">  
<img src="https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c)">
</p> 
<h1 align="center">🚀 Get_next_line 🚀</h1> 

# 42/1337 School Get Next Line Project 📚

## 🎯 Project Overview
The `get_next_line()` project is a crucial assignment at 42 School that challenges students to create a function capable of reading a line from a file descriptor, demonstrating advanced file handling and dynamic memory management in C.

## 📘 Project Objectives
- Read a line from a file descriptor
- Handle multiple file descriptors simultaneously
- Implement efficient memory management
- Create a flexible and reusable function
- Comply with 42 School's coding norms (Norminette)

## 🔍 Function Prototype
```c
char *get_next_line(int fd);
```

## 🛠️ Mandatory Part Requirements
### Core Functionality
- Read line by line from a file descriptor
- Return the entire line, including the newline character
- Return `NULL` when there are no more lines to read
- Handle different file sizes and line lengths

### Key Constraints
- Use of a single static variable
- Buffer size configurable at compile time
- No memory leaks
- Efficient memory allocation and deallocation

## 🌟 Bonus Part Challenges
### Advanced Implementation Features
1. **Multiple File Descriptor Handling**
   - Manage reading from multiple file descriptors simultaneously
   - Maintain separate states for different file descriptors
   - Prevent interference between different file streams

2. **Single Static Variable Optimization**
   - Use a single static variable for all file descriptors
   - Implement a sophisticated tracking mechanism
   - Minimize memory footprint

### Bonus Implementation Strategies
- Create a linked list or dynamic array to track file descriptor states
- Implement sophisticated buffer management
- Ensure clean memory handling across multiple file reads

## 📚 Technical Challenges
### 1. Buffer Management
- Efficiently read chunks from file descriptor
- Store and manipulate partial lines
- Handle remainders between function calls

### 2. Memory Allocation
- Dynamic memory allocation for lines
- Prevent memory leaks
- Efficient memory reuse

### 3. File Descriptor Handling
- Work with different types of file descriptors
- Handle edge cases (empty files, very long lines)
- Ensure robust error handling
