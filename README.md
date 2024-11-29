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

## 2. Global and local variable

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

    return 0;
}
```
<img width="284" alt="image" src="https://github.com/user-attachments/assets/0a994de5-20d4-47b7-82f7-0402e87c6126">

- The program demonstrates variable shadowing, where a local variable hides a global variable of the same name within its scope.
- The :: (scope resolution operator) is used to access the global variable when a local variable of the same name exists.

## 3. Refrance variable
```
#include <iostream>
using namespace std;

int main() {
    int original = 10;

    // Reference variable
    int& ref = original;

    cout << "Original value: " << original << endl;
    cout << "Reference value: " << ref << endl;

    // Modify the value using the reference
    ref = 20;

    cout << "Original value after modifying reference: " << original << endl;
    cout << "Reference value after modification: " << ref << endl;

    return 0;
}

```
<img width="396" alt="image" src="https://github.com/user-attachments/assets/89118bfd-e61a-4362-a911-1d57e7745e22">

- Reference variables provide an alias to an existing variable.
- Modifying a reference variable changes the original variable since both refer to the same memory location.

  ## 3. Control structure
  <img width="322" alt="image" src="https://github.com/user-attachments/assets/f376df9c-7ed4-492e-be60-7b19978f9edd">
  
  ### if Statement
- IF statment is true:
```
#include <iostream>
using namespace std;

int main() {
    int x = 10;
        if (x > 5) {
                    cout << "x is greater than 5" << endl;
                }
        return 0;
    }
```

<img width="404" alt="image" src="https://github.com/user-attachments/assets/45658ff1-04ed-4dc4-bcf5-af4fb6e56625">


```

- IF statment is False:

#include <iostream>
using namespace std;

int main() {
    int x = 1;
        if (x > 5) {
                    cout << "x is greater than 5" << endl;
                }
        return 0;
    }
```
<img width="304" alt="image" src="https://github.com/user-attachments/assets/9d49adce-f567-4fe0-a2db-f53be3dd5905">


