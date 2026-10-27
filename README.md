# Square Pattern Number in C++

## 📌 Description
This program prints a square pattern of numbers using nested `for` loops in C++.

It prints numbers from 1 to 4 in each row and repeats the pattern for 4 rows.

## 💻 Code
```cpp
#include<iostream>
using namespace std;

int main()
{
    for(int i=1; i<5; i++)
    {
        for(int j=1; j<5; j++)
        {
            cout << j << "";
        }
        cout << endl;
    }
    return 0;
}
```

## 📤 Output
```text
1234
1234
1234
1234
```

## 🧠 Concepts Used
- C++ Basics
- Nested For Loops
- Pattern Printing
- Output Statements

## ⚙️ How It Works
1. The outer loop (`i`) controls the number of rows.
2. The inner loop (`j`) prints numbers from 1 to 4 in each row.
3. `cout << endl` moves the cursor to the next line after each row.
4. The loops repeat until 4 rows are printed.

## 🎯 Learning Objective
To understand nested loops and develop basic problem-solving skills through pattern printing.

## 🛠️ Language
- C++

---
**Author:** My C++ & DSA Learning Journey 🚀
