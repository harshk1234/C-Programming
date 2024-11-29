# C-Programming
This repository is dedicated to C++ programming and includes a collection of programs that demonstrate various concepts of Object-Oriented Programming (OOP). It is designed for learners and developers to explore and understand the implementation of OOP principles.

## 1. Hello World 

```
#include <iostream> // Include the input-output stream library

int main() {
    // Output "Hello, World!" to the console
    std::cout << "Hello, World!" << std::endl;
    return 0; // Return 0 to indicate successful program termination
}
```

<img width="475" alt="image" src="https://github.com/user-attachments/assets/2d0ec116-d697-44d6-b656-fe0c05b5a1fc">

<img width="401" alt="image" src="https://github.com/user-attachments/assets/e191864e-b7dd-48c4-9d20-004dea8cad4e">

## 1. Global and local variable

```
#include <iostream>
using namespace std;

// Global variable
int globalVar = 10;


int main() {
    // Local variable
    int globalVar = 20;

    cout << "Global Variable: " << globalVar << endl;
    cout << "Local Variable: " << ::globalVar << endl; // it will write original globale variable value


    cout << "Global variable after modification in main: " << globalVar << endl;

    return 0;
}
```

