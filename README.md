<p align="center"> 
<img src="https://img.shields.io/badge/42-Network-black?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAABiElEQVQ4y2NgGFQggv//CSgoKCgqKioqKSkpKSkpffz48f///f8P0tjR0VHe3t5e29zcXNLc3FzS2NhY0tDQUNLQ0FDS1NRc0traurS1tXVpW1vb0tbW1qVtbW1L29vbl7a3ty9tb29f2tHRsbSjo2Npe3v70s7OzqWdnZ1LBwYGlw4ODi4dGhpaOjQ0tHRkZGTp6Ojo0rGxsaVjY2NLx8fHl46Pjy8dHx9fOjExsXRycnLpzMzM0llg8D8K//37R/Dv3z+Cv3//Evz//5/g+/cfBP/+/Sf4/v0nwe/fvwm+ff9F8OfPX4Kf\n P34T/Pz5i+Dnz98Ev3//Ifj9+y/Bn/2/gAr+ATX+hCr+AVWAqQAW+APU8Aeo4R9Qw19QDf+BGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBr+ATX8A2r4B9TwD6jhH1DDH6CGf0AN/4Aa/gE1/ANq+AfU8A+o4R9Qwz+ghn9ADf+AGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBoYAABhKkjR0SIEzwAAAABJRU5ErkJggg==" alt="42 Network"> 
<img src="https://img.shields.io/badge/1337-Coding-green?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAABiElEQVQ4y2NgGFQggv//CSgoKCgqKioqKSkpKSkpffz48f///f8P0tjR0VHe3t5e29zcXNLc3FzS2NhY0tDQUNLQ0FDS1NRc0traurS1tXVpW1vb0tbW1qVtbW1L29vbl7a3ty9tb29f2tHRsbSjo2Npe3v70s7OzqWdnZ1LBwYGlw4ODi4dGhpaOjQ0tHRkZGTp6Ojo0rGxsaVjY2NLx8fHl46Pjy8dHx9fOjExsXRycnLpzMzM0llg8D8K//37R/Dv3z+Cv3//Evz//5/g+/cfBP/+/Sf4/v0nwe/fvwm+ff9F8OfPX4Kf\n P34T/Pz5i+Dnz98Ev3//Ifj9+y/Bn/2/gAr+ATX+hCr+AVWAqQAW+APU8Aeo4R9Qw19QDf+BGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBr+ATX8A2r4B9TwD6jhH1DDH6CGf0AN/4Aa/gE1/ANq+AfU8A+o4R9Qwz+ghn9ADf+AGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBoYAABhKkjR0SIEzwAAAABJRU5ErkJggg==" alt="1337 Coding"> 
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
