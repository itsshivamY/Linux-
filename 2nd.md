# 📘 INTRODUCTION TO COMPUTING & C PROGRAMMING

---

## 1. INTRODUCTION TO MCU

### MCU → Microcontroller Unit

A **Microcontroller** is a small computer system integrated into a single chip.

### MCU ke Main Components

→ CPU
→ Memory
→ Input / Output (I/O)
→ Timers
→ Communication Interfaces
→ Other Peripherals

---

## 2. CPU

### CPU → Central Processing Unit

CPU computer/system ka **main processing unit** hota hai.

### CPU ke Major Components

→ ALU
→ Control Unit
→ Registers

---

## 3. ALU

### ALU → Arithmetic Logic Unit

ALU ka main work:

→ Arithmetic Operations
→ Logical Operations
→ Comparison Operations

---

# 4. LOGIC GATES

Logic Gates digital circuits ke **basic building blocks** hote hain.

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

Linux ek **open-source operating system kernel** hai.

### Linux-based Distributions

→ Ubuntu
→ Fedora
→ Kali Linux

---

# 6. C PROGRAMMING VERSION

### C Language ka Evolution / Sankraman

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

Original notes mein:

```text
C89
C99 (ANCIC)
C08
C11
C24
```

Correct versions:

→ C89 / C90
→ C99
→ C11
→ C17
→ C23

**Note:** C08 aur C24 standard C versions nahi hain.

---

# 7. DATA TYPE

**Data Type** batata hai ki variable mein kis type ka data store hoga.

### Basic C Data Types

→ int
→ float
→ double
→ char
→ void

---

# 8. NUMBER / COUNT

## 8.1 Natural Number

Natural Numbers generally:

```text
1, 2, 3, 4, 5, ... N
```

**Note:** Kuch mathematical conventions mein `0` ko bhi Natural Number maana jata hai.

---

## 8.2 Zero (0)

### Original Note:

**"0 is Artificial Number"**

### Correction:

0 ko Artificial Number nahi kaha jata.

`0`:

→ Integer hai
→ Whole Number hai

---

## 8.3 Real Number

Original concept:

```text
(-) , 0 , (+)
```

Real Numbers mein include hote hain:

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

Real Numbers ko `ℝ` se represent kiya jata hai.

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

## 9.1 int

`int` integer values store karta hai.

### Examples

```c
int age = 20;
int number = -10;
```

### Common 4-byte int Range

```text
-2,147,483,648
        to
 2,147,483,647
```

**Note:** Exact range implementation/system par depend karti hai.

---

## 9.2 float

`float` floating-point numbers store karta hai.

Original note:

```text
float = (+0.e) power 6
0.000001
```

### Correction

Typical `float` approximately **6–7 decimal digits of precision** provide karta hai.

### Example

```c
float marks = 85.5;
float price = 99.99;
```

---

## 9.3 char

`char` ek **single character** store karta hai.

Original examples:

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

## 9.4 void

Original note:

```text
void = None (Not a Number)
```

### Correction

`void` ka meaning relevant context mein:

**No Value / No Type**

### Example

```c
void display()
{
    printf("Hello");
}
```

Yeh function koi value return nahi karta.

---

# 10. TYPE MODIFIERS

C mein important Type Modifiers:

→ `signed`
→ `unsigned`
→ `short`
→ `long`

### Example

```c
unsigned int age;
long int population;
short int number;
```

---

# 11. TYPE QUALIFIERS

Original note mein:

```text
Quakufier
→ Short
→ long
→ Restrict
→ extern
```

### Correct Concept

C ke important Type Qualifiers:

→ `const`
→ `volatile`
→ `restrict`

### Important

| Keyword  | Category                |
| -------- | ----------------------- |
| short    | Type Modifier           |
| long     | Type Modifier           |
| extern   | Storage-Class Specifier |
| restrict | Type Qualifier          |

---

## 11.1 const

Variable ki value ko modify hone se prevent karne ke liye.

```c
const int x = 10;
```

---

## 11.2 volatile

Compiler ko indicate karta hai ki variable ki value program ke normal flow ke bahar change ho sakti hai.

Common use:

→ Hardware Registers
→ Interrupt-related Variables
→ Memory-mapped I/O

---

## 11.3 restrict

`restrict` pointer qualifier hai.

Yeh compiler ko pointer access ke regarding optimization assumptions provide karta hai.

---

# 12. STORAGE CLASS

C mein four important Storage-Class Specifiers:

1. `auto`
2. `extern`
3. `register`
4. `static`

---

## 12.1 auto

Local variables ke liye default storage class.

```c
auto int x = 10;
```

---

## 12.2 extern

Variable/function ki definition kisi other file/place par ho sakti hai, ye indicate karta hai.

```c
extern int x;
```

---

## 12.3 register

Compiler ko suggest karta hai ki variable ko fast-access storage/register mein rakhna useful ho sakta hai.

```c
register int i;
```

---

## 12.4 static

Variable ki lifetime/scope behavior ko control karta hai.

```c
static int count = 0;
```

---

# 13. C89 / C90 — 32 KEYWORDS

C89/C90 mein total **32 keywords** hote hain.

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
