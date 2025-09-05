# DSA-x-Copilot
# Digital Assignment 1- Notes
## Headerfiles
* Imagine headerfiles are part of eco.
* To access the func in lib We need headfle.
```
              🌲 Root:C++ Program[filename.cpp]
                             |
        ┌────────────────────┼────────────────────┐
        |                    |                    |
   📜 Header Files       🧰 Lib Files          🧠 Namespaces
   (.h / .hpp)          (.lib / .dll / .so)     (std, custom)
        |
   ┌────┼────┐
   |    |    |
Declarations: Functions, Classes, Constants
```
## Note
* Here Lib files are hidden machine behind leaves.
```C++
   /* 📜 Header file (declares std::cout)  # x ''' - Serpen
    🧠 Namespace (lets skip std:: prefix) */
#include <iostream>
using namespace std;     
                    
int main()
{
    cout << "Rehaan's tree is growing strong!" << endl; // We use endl for cout not for cin.
    return 0;
}
```
```
                                     Header files
           1.Standard Header files                   2.User-Defined Header files
         *Built-in x Part of stndrd Lib of C++      *Name defines.
```
* Initiate header files through ``#include<headerfile1>`` or ``#include "headerfile"``
* Without ``#include`` compiler dont know whats ``cout`` and When it knows it uses ``iostream`` to understand it as ``std::cout``.
#Examples of Header files
```
| Header File      | Purpose                                      |             Key Functions / Classes                 |
|------------------|--------------------------------------------- |---------------------------------------------------- |
| `<iostream>`     | Input/output stream operations               | `std::cin`, `std::cout`, `std::cerr`, `std::endl`   |
| `<cmath>`        | Mathematical computations                    | `sqrt`, `pow`, `log`, `sin`, `cos`, `ceil`, `floor` |
| `<cstdlib>`      | General utilities and memory management      | `rand`, `exit`, `malloc`, `free`, `system`          |
| `<cstring>`      | C-style string manipulation                  | `strlen`, `strcpy`, `strcmp`, `strcat`              |
| `<string>`       | C++ string class and operations              | `std::string`, `length`, `substr`, `find`           |
| `<vector>`       | Dynamic array container                      | `std::vector`, `push_back`, `size`, `begin`, `end`  |
| `<map>`          | Key-value associative container              | `std::map`, `insert`, `find`, `erase`               |
| `<set>`          | Unique element container                     | `std::set`, `insert`, `count`, `erase`              |
| `<algorithm>`    | Common algorithms                            | `sort`, `reverse`, `max_element`, `find`            |
| `<iomanip>`      | Output formatting                            | `setw`, `setprecision`, `fixed`, `showpoint`        |
| `<fstream>`      | File input/output streams                    | `std::ifstream`, `std::ofstream`, `std::fstream`    |
| `<ctime>`        | Time and date utilities                      | `time`, `clock`, `difftime`, `localtime`            |
| `<cassert>`      | Runtime assertions                           | `assert`                                            |
| `<typeinfo>`     | Runtime type information                     | `typeid`                                            |
| `<limits>`       | Numeric limits of data types                 | `std::numeric_limits<T>::max()`                     |
```
# Modulrt
* Concept of dividing the programs into modules.
# Data Structures x Algo
```
            DS
            |
    -------------------
    |                 |
  Primtve DS      Non-Prmtve S
  |                    |
 Int               Lnr       NLnr
 char               |         |
 float             Arr        Tress
 double            Que        Graph
                   Stck
                   Likdlst
```
## Sample code for Prmtve DS
```C++
#include<iostream>  //char x String  Capital small And Number 
using namespace std;
#include<string>
int main()
{
int n,A[n];
char B[n],D;
string C[n],E;
n = 1;        // string has more functions compared to char!.
D = '1';
string E ='2';
}
```

  



