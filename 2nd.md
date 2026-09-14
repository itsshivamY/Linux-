# 📘 INTRODUCTION TO COMPUTING & C PROGRAMMING

---

# 1. INTRODUCTION TO MCU

## MCU → Microcontroller Unit

A **Microcontroller** is a small computer system integrated into a single chip.

### Main Components of an MCU

→ CPU
→ Memory
→ Input / Output (I/O)
→ Timers
→ Communication Interfaces
→ Other Peripherals

---

# 2. CPU

## CPU → Central Processing Unit

The CPU is the **main processing unit** of a computer/system.

### Major Components of CPU

→ ALU
→ Control Unit
→ Registers

---

# 3. ALU

## ALU → Arithmetic Logic Unit

The main functions of the ALU are:

→ Arithmetic Operations
→ Logical Operations
→ Comparison Operations

---

# 4. LOGIC GATES

Logic Gates are the **basic building blocks of digital circuits**.

### Types of Logic Gates

1. AND
2. OR
3. NOT
4. NAND
5. NOR
6. XOR
7. XNOR

---

# 5. LINUX

Linux is an **open-source operating system kernel**.

### Linux-based Distributions

→ Ubuntu
→ Fedora
→ Kali Linux

---

# 6. C PROGRAMMING VERSIONS

## Evolution of C Language

```text
C89 / C90
    ↓
C99
    ↓
C11
    ↓
C17
    ↓
C23
```

### Important Correction

Original notes:

```text
C89

C99 (ANCIC)

C08

C11

C24
```

Correct C standards:

→ C89 / C90
→ C99
→ C11
→ C17
→ C23

**Note:** C08 and C24 are not standard names for C language versions.

**ANSI** → American National Standards Institute

---

# 7. DATA TYPE

A **Data Type** tells us what type of data a variable can store.

### Basic C Data Types

→ `int`
→ `float`
→ `double`
→ `char`
→ `void`

---

# 8. NUMBER / COUNT

## 8.1 Natural Number

Natural Numbers are generally:

```text
1, 2, 3, 4, 5, ... N
```

**Note:** In some mathematical conventions, `0` is also considered a Natural Number.

---

## 8.2 Zero (0)

### Original Note

**"0 is Artificial Number"**

### Correction

0 is **not** called an Artificial Number.

`0` is:

→ An Integer
→ A Whole Number

---

## 8.3 Real Number

Original concept:

```text
(-) , 0 , (+)
```

Real Numbers include:

→ Negative Numbers
→ Zero
→ Positive Numbers
→ Decimal Numbers

### Examples

```text
-5
-2.5
0
3
4.75
```

Real Numbers are represented by **ℝ**.

---

## 8.4 Rational Number

### Formula

```text
p / q
```

Where:

→ `p` = Integer
→ `q` = Non-zero Integer
→ `q ≠ 0`

### Examples

```text
1/2
3/4
-5/2
7
```

---

# 9. FUNDAMENTALS OF DATA TYPES

## 9.1 `int`

`int` is used to store integer values.

### Examples

```c
int age = 20;

int number = -10;
```

### Common 4-byte `int` Range

```text
-2,147,483,648

        to

 2,147,483,647
```

**Note:** The exact range depends on the implementation/system.

---

## 9.2 `float`

`float` is used to store floating-point numbers.

### Original Note

```text
float = (+0.e) power 6

0.000001
```

### Correction

A typical `float` provides approximately **6–7 decimal digits of precision**.

### Example

```c
float marks = 85.5;

float price = 99.99;
```

---

## 9.3 `char`

`char` is used to store a **single character**.

### Original Examples

```text
$ # % ^ * & ^
```

### Other Examples

```text
'A'
'B'
'a'
'z'
'1'
'#'
'@'
'%'
'&'
'*'
```

---

## 9.4 `void`

### Original Note

```text
void = None (Not a Number)
```

### Correction

`void` means **No Value / No Type**, depending on the context.

### Example

```c
void display()
{
    printf("Hello");
}
```

This function does not return a value.

---

# 10. TYPE MODIFIERS

Important Type Modifiers in C:

→ `signed`
→ `unsigned`
→ `short`
→ `long`

### Examples

```c
unsigned int age;

long int population;

short int number;
```

---

# 11. TYPE QUALIFIERS

### Original Note

```text
Quakufier

→ Short

→ long

→ Restrict

→ extern
```

### Correct Concept

Important Type Qualifiers in C are:

→ `const`
→ `volatile`
→ `restrict`

### Important Classification

| Keyword    | Category                |
| ---------- | ----------------------- |
| `short`    | Type Modifier           |
| `long`     | Type Modifier           |
| `extern`   | Storage-Class Specifier |
| `restrict` | Type Qualifier          |

---

## 11.1 `const`

`const` is used to prevent a variable's value from being modified.

### Example

```c
const int x = 10;
```

---

## 11.2 `volatile`

`volatile` tells the compiler that the value of a variable may change outside the normal flow of the program.

### Common Uses

→ Hardware Registers
→ Interrupt-related Variables
→ Memory-mapped I/O

---

## 11.3 `restrict`

`restrict` is a **pointer qualifier**.

It provides the compiler with information that can help with pointer-related optimization.

---

# 12. STORAGE CLASS

There are four important Storage-Class Specifiers in C:

1. `auto`
2. `extern`
3. `register`
4. `static`

---

## 12.1 `auto`

`auto` is the default storage class for local variables.

### Example

```c
auto int x = 10;
```

---

## 12.2 `extern`

`extern` indicates that the definition of a variable or function may exist in another file or location.

### Example

```c
extern int x;
```

---

## 12.3 `register`

`register` suggests that a variable may benefit from fast-access storage/register.

### Example

```c
register int i;
```

---

## 12.4 `static`

`static` affects the lifetime and/or linkage of a variable depending on where it is declared.

### Example

```c
static int count = 0;
```

---

# 13. C89 / C90 — 32 KEYWORDS

C89/C90 contains a total of **32 keywords**.

---

## 13.1 DATA TYPE KEYWORDS — 5

1. `char`
2. `int`
3. `float`
4. `double`
5. `void`

---

## 13.2 DECISION MAKING — 5

1. `if`
2. `else`
3. `switch`
4. `case`
5. `default`

---

## 13.3 LOOPING — 3

1. `for`
2. `while`
3. `do`

---

## 13.4 JUMP STATEMENTS — 4

1. `break`
2. `continue`
3. `goto`
4. `return`

---

## 13.5 STORAGE CLASS — 4

1. `auto`
2. `extern`
3. `register`
4. `static`

---

## 13.6 TYPE MODIFIERS — 4

1. `short`
2. `long`
3. `signed`
4. `unsigned`

---

## 13.7 USER-DEFINED TYPES — 4

1. `struct`
2. `union`
3. `enum`
4. `typedef`

---

## 13.8 OTHER KEYWORDS — 3

1. `const`
2. `sizeof`
3. `volatile`

---

# TOTAL = 32 KEYWORDS

```text
Data Type Keywords     → 5
Decision Making        → 5
Looping                → 3
Jump Statements        → 4
Storage Class          → 4
Type Modifiers         → 4
User-Defined Types     → 4
Other Keywords         → 3
                         ───
TOTAL                  → 32
```

### Complete 32 Keywords

```text
auto
break
case
char
const
continue
default
do
double
else
enum
extern
float
for
goto
if
int
long
register
return
short
signed
sizeof
static
struct
switch
typedef
union
unsigned
void
volatile
while
```

### Important Note

`class` is **not a C89 keyword**.

`class` is a **C++ keyword**.

---

# 14. COMPILER

A **Compiler** translates source code into object code or executable code.

### Basic Flow

```text
Source Code
     ↓
Compiler
     ↓
Object / Executable Code
     ↓
Run
```

### Examples

→ C
→ C++

---

# 15. INTERPRETER

An **Interpreter** processes/executes source code at runtime rather than producing a traditional standalone executable in the same way as a typical ahead-of-time compiler.

### Simplified Flow

```text
Source Code
     ↓
Interpreter
     ↓
Execute
```

### Example

→ Python

### Important Note

Modern language implementation
