# Description
**get_next_line** is a programming project designed to help you master memory management and dynamic memory allocation in C. The goal of the project is to implement a function that reads a line from a file descriptor, typically a file or the standard input, and returns the line as a string. The function must work efficiently, handling dynamic memory allocation for each line, ensuring the program works even with large files and a limited buffer size.

Throughout this project, I developed a deeper understanding of how memory management works in C, specifically focusing on dynamic memory allocation, reallocation, and the importance of handling memory leaks.

# Features
Reads one line from a given file descriptor at a time.
Dynamically allocates memory to store each line of text, resizing it as needed.
Handles multiple lines without losing memory or overwriting previously read data.

# What I learned

During the development of get_next_line, I gained significant experience in handling dynamic memory allocation with `malloc`, `realloc` and `free`, which is a fundamental skill in C programming. During the development of the get_next_line project, I also gained practical experience using `Valgrind` and debuggers—essential tools for C programming and memory management.
