
## TOTAL = 32 KEYWORDS

```text
Data Types          → 5
Decision Making     → 5
Looping             → 3
Jump Statements     → 4
Storage Class       → 4
Type Modifiers      → 4
User-Defined Types  → 4
Other               → 3
                     ----
TOTAL               → 32
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

### Important

`class` **C89 ka keyword nahi hai**.

`class` **C++ ka keyword hai**.

---

# 14. COMPILER

Compiler source code ko compile karke object/executable code generate karta hai.

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

Interpreter source program ko execution ke saath process/translate karta hai.

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

Modern programming language implementations pure compiler ya pure interpreter nahi hoti. Compilation, bytecode aur JIT techniques ka combination bhi ho sakta hai.

---

# 16. COMPILER vs INTERPRETER

| Compiler                                        | Interpreter                                                      |
| ----------------------------------------------- | ---------------------------------------------------------------- |
| Program ko execution se pehle compile karta hai | Translation/execution runtime ke saath closely combined hoti hai |
| Object/executable code generate kar sakta hai   | Runtime par execution hoti hai                                   |
| Generally compiled code fast execute hota hai   | Traditionally execution comparatively slower ho sakti hai        |
| Compilation phase mein errors mil sakte hain    | Runtime par errors mil sakte hain                                |
| C, C++                                          | Python, JavaScript                                               |

---

# 17. ASCII

### ASCII → American Standard Code for Information Interchange

ASCII characters ko numerical codes assign karta hai.

### Important ASCII Values

```text
A → 65
Z → 90

a → 97
z → 122
```

### Ranges

```text
A-Z → 65-90
a-z → 97-122
```

Original ASCII **7-bit** standard hai aur 128 character codes define karta hai.

---

# 18. ASSEMBLY LANGUAGE

Assembly Language ek **low-level programming language** hai.

### File Extension

```text
.asm
```

### Example

```asm
MOV AX, 10
ADD AX, 20
```

Assembly source ko **Assembler** object/machine code mein translate karta hai.

### Flow

```text
Assembly Code
      ↓
Assembler
      ↓
Object Code
```

---

# 19. .OBJ → BINARY

`.obj` generally **Object File** ko represent karta hai.

Object file mein machine-level code/data ho sakta hai.

### Important

`.obj` directly executable hona zaroori nahi hai.

### Flow

```text
Source Code
     ↓
Compiler / Assembler
     ↓
.obj
     ↓
Linker
     ↓
Executable
```

---

# 20. LOADER

Loader executable program ko memory mein load karta hai.

### Windows

```text
.exe
```

### Unix / Linux

```text
a.out
```

### Basic Flow

```text
Executable
     ↓
Loader
     ↓
Memory
     ↓
CPU
     ↓
Program Execution
```

---

# 21. MCU vs MPU

## MCU → Microcontroller Unit

Generally ek single chip mein:

→ CPU
→ Memory
→ I/O
→ Peripherals

integrated hote hain.

### Common Uses

→ Embedded Systems
→ Sensors
→ IoT Devices
→ Robotics
→ Appliances
→ Control Systems

---

## MPU → Microprocessor Unit

MPU generally processing core provide karta hai.

System architecture ke according external:

→ Memory
→ Peripherals
→ I/O

ki requirement ho sakti hai.

### Common Uses

→ General-purpose Computing
→ Embedded Linux Systems
→ Advanced Computing Systems

---

# 22. SOC / SoC

### SoC → System on Chip

SoC ek single chip par multiple system components integrate kar sakta hai.

### Possible Components

→ CPU
→ GPU
→ Memory Controller
→ I/O
→ Communication Interfaces
→ Other Peripherals

---

# 23. OTA

### OTA → Over-The-Air

OTA ka meaning hai wireless/network connection ke through software ya firmware update karna.

### Flow

```text
Internet / Network
        ↓
      Device
        ↓
    OTA Update
        ↓
New Firmware / Software
```

### Common Uses

→ Smartphones
→ IoT Devices
→ Embedded Systems
→ Smart Devices
→ Vehicle Systems

---

# 24. INTERPRETER — STATIC & DYNAMIC

Original Note:

```text
Interpreter

1. Static
2. Dynamic
   (Read Real Time)
```

### Correction

**Static** aur **Dynamic** interpreter ke standard two types nahi hain.

Ye terms mainly **typing, analysis aur runtime behavior** ke context mein use hoti hain.

---

## Static

Information/analysis ko compile time par determine/check kiya ja sakta hai.

### Static Typing

→ Type checking mainly compile time par hoti hai.

---

## Dynamic

Information/runtime behavior execution ke time determine ho sakta hai.

### Dynamic Typing

→ Type checking mainly runtime par hoti hai.

---

# 25. C PROGRAM EXECUTION FLOW

Complete basic flow:

```text
C Source Code
       ↓
Preprocessor
       ↓
Compiler
       ↓
Assembly Code
       ↓
Assembler
       ↓
Object File
(.obj / .o)
       ↓
Linker
       ↓
Executable
       ↓
Loader
       ↓
Memory
       ↓
CPU
       ↓
Program Execution
```

---

# 26. QUICK REVISION

```text
MCU  → Microcontroller Unit

MPU  → Microprocessor Unit

CPU  → Central Processing Unit

ALU  → Arithmetic Logic Unit

SoC  → System on Chip

ASCII → American Standard Code for Information Interchange

OTA  → Over-The-Air
```

### Electronics

```text
L → Inductor
C → Capacitor
R → Resistor
```

### File Extensions

```text
.asm → Assembly Source File

.obj → Object File

.exe → Windows Executable

a.out → Common Unix/Linux executable name
```

### ASCII

```text
A → 65
Z → 90

a → 97
z → 122
```

### C89/C90

```text
32 Keywords
```

---

# 27. COMPLETE CONCEPT FLOW

```text
Counting
   ↓
Mathematics
   ↓
Abacus
   ↓
Mechanical Calculator
   ↓
Charles Babbage
   ↓
Electrical Concepts
   ↓
Boolean Algebra
   ↓
Transistor
   ↓
Digital Electronics
   ↓
CPU
   ↓
MCU / MPU
   ↓
Assembly Language
   ↓
C Programming
   ↓
Compiler / Assembler
   ↓
Object Code
   ↓
Linker
   ↓
Executable
   ↓
Loader
   ↓
Operating System
   ↓
Linux
   ↓
Applications
   ↓
Internet
   ↓
Artificial Intelligence
```

# END OF NOTES
