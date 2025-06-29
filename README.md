# cpp-code-generator
This will generate cpp code taking json or text file as input

# C++ Code Generator

A simple C++ program that generates C++ class code based on user input.

## Features

- Input class name and fields with types  
- Supports optional default values for fields  
- Automatically generates constructor, getters, and setters  
- Generates a `main()` function to test the class  
- Supports basic types: `int`, `string`, `bool`, `float`, `double`  
- Saves generated code as a `.cpp` file ready to compile  

## How to Use

1. Compile the generator:

   ```bash
   g++ generator.cpp -o generator -std=c++17
./generator
Class to generate: User
Enter fields (type name [= default]), type 'done' to finish:
Field: int id = 42
Field: string name = Rounak
Field: string email = example@example.com
Field: bool isActive = true
Field: done
g++ User.cpp -o User
./User

Requirements
C++ compiler supporting C++17 (e.g., g++ 7+)

License
MIT License (or your preferred license)


---

If you want, I can help you generate a ready-to-copy README file or add more details!

