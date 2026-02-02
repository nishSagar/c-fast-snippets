# C Fast Snippets
This is my first VS Code extension.

It provides fast and practical C language snippets to help write code quicker,
especially for beginners and students.

## Features
- C main function
- printf and scanf snippets
- Data type variable declarations
- Conditional statements
- Loop templates

## How to use
Type a snippet prefix and press `Tab`.

Example:

Main Functions
| Prefix | Description               |
| ------ | ------------------------- |
| `c`    | `int main(void)` template |
| `voi`  | `void` function template  |

Header / Preprocessor
| Prefix | Description          |
| ------ | -------------------- |
| `head` | `#include <...>`     |
| `std`  | `#include <stdio.h>` |

printf Snippets
| Prefix   | Example                |
| -------- | ---------------------- |
| `out`    | `printf("text\n");`    |
| `outd`   | `printf("%d\n", x);`   |
| `outf`   | `printf("%f\n", x);`   |
| `outc`   | `printf("%c\n", ch);`  |
| `outs`   | `printf("%s\n", str);` |
| `outu`   | `printf("%u\n", x);`   |
| `outi`   | `printf("%i\n", x);`   |
| `outx`   | `printf("%x\n", x);`   |
| `outX`   | `printf("%X\n", x);`   |
| `outf1`  | `printf("%.1f\n", x);` |
| `outf2`  | `printf("%.2f\n", x);` |
| `outlf`  | `printf("%lf\n", x);`  |
| `outLf`  | `printf("%Lf\n", x);`  |
| `oute`   | `printf("%e\n", x);`   |
| `outg`   | `printf("%g\n", x);`   |
| `outhd`  | `printf("%hd\n", x);`  |
| `outld`  | `printf("%ld\n", x);`  |
| `outlld` | `printf("%lld\n", x);` |
| `outhu`  | `printf("%hu\n", x);`  |
| `outlu`  | `printf("%lu\n", x);`  |
| `outllu` | `printf("%llu\n", x);` |
| `outp`   | `printf("%p\n", ptr);` |
| `outn`   | `printf("%n\n", x);`   |
| `out%`   | `printf("%%\n");`      |

scanf Snippets
| Prefix  | Example               |
| ------- | --------------------- |
| `in`    | `scanf("...", &var);` |
| `ind`   | `scanf("%d", &x);`    |
| `inf`   | `scanf("%f", &x);`    |
| `inc`   | `scanf("%c", &ch);`   |
| `ins`   | `scanf("%s", str);`   |
| `inu`   | `scanf("%u", &x);`    |
| `ini`   | `scanf("%i", &x);`    |
| `inx`   | `scanf("%x", &x);`    |
| `inX`   | `scanf("%X", &x);`    |
| `inf1`  | `scanf("%.1f", &x);`  |
| `inf2`  | `scanf("%.2f", &x);`  |
| `inlf`  | `scanf("%lf", &x);`   |
| `inLf`  | `scanf("%Lf", &x);`   |
| `ine`   | `scanf("%e", &x);`    |
| `ing`   | `scanf("%g", &x);`    |
| `inhd`  | `scanf("%hd", &x);`   |
| `inld`  | `scanf("%ld", &x);`   |
| `inlld` | `scanf("%lld", &x);`  |
| `inhu`  | `scanf("%hu", &x);`   |
| `inlu`  | `scanf("%lu", &x);`   |
| `inllu` | `scanf("%llu", &x);`  |
| `inp`   | `scanf("%p", &ptr);`  |
| `inn`   | `scanf("%n", &x);`    |
| `in%`   | `scanf("%%");`        |

Data Type Declarations
| Prefix  | Expansion                    |
| ------- | ---------------------------- |
| `n`     | `int num = 1;`               |
| `sn`    | `signed int num = 1;`        |
| `un`    | `unsigned int num = 1;`      |
| `ssn`   | `short int num = 1;`         |
| `ln`    | `long int num = 1;`          |
| `lln`   | `long long int num = 1;`     |
| `ch`    | `char a = 'a';`              |
| `f`     | `float pi = 3.14f;`          |
| `d`     | `double pi = 3.14159265359;` |
| `true`  | `bool true = 1;`             |
| `false` | `bool false = 0;`            |

Storage Class Specifiers
| Prefix | Expansion               |
| ------ | ----------------------- |
| `aut`  | `auto int num = 1;`     |
| `reg`  | `register int num = 1;` |
| `sta`  | `static int num = 1;`   |
| `ext`  | `extern int num = 1;`   |

Conditional Statements
| Prefix   | Description      |
| -------- | ---------------- |
| `if`     | Basic `if` block |
| `ife`    | `if–else` block  |
| `ifgre`  | `if (a > b)`     |
| `ifgreq` | `if (a >= b)`    |
| `ifles`  | `if (a < b)`     |
| `iflesq` | `if (a <= b)`    |

Loops
| Prefix | Description         |
| ------ | ------------------- |
| `fo`   | `for` loop template |


## Who is this for
- Beginners learning C
- Students writing C programs
- Anyone who wants faster boilerplate

## Notes
- This extension is a learning project.
- Prefixes and snippets may change in future versions.

## Open Source & Free
This extension is completely **free and open source**.

Anyone can edit, remove, or add snippets and customize it for personal use.
The project is open for learning and future improvements.

## Versioning
Current version: **0.1.0**
This is the first public release.
More features and updates may be added in future versions.



Feedback and suggestions are welcome.