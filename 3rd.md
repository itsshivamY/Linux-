# 📘 C PROGRAMMING — COMPLETE NOTES

---

# 13. C89 / C90 — 32 KEYWORDS

C89/C90 contains a total of **32 keywords**.

## TOTAL = 32 KEYWORDS

| Category           | Number of Keywords |
| ------------------ | -----------------: |
| Data Types         |                  5 |
| Decision Making    |                  5 |
| Looping            |                  3 |
| Jump Statements    |                  4 |
| Storage Class      |                  4 |
| Type Modifiers     |                  4 |
| User-Defined Types |                  4 |
| Other              |                  3 |
| **TOTAL**          |             **32** |

---

## Complete 32 Keywords

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

`class` is **not a C89 keyword**.

`class` is a **C++ keyword**.

---

# 14. COMPILER

A **Compiler** translates source code into object code or executable code.

## Basic Flow

```text
Source Code
     ↓
Compiler
     ↓
Object / Executable Code
     ↓
Run
```

## Examples

→ C
→ C++

---

# 15. INTERPRETER

An **Interpreter** processes and executes source code at runtime.

## Simplified Flow

```text
Source Code
     ↓
Interpreter
     ↓
Execute
```

## Example

→ Python

### Important Note

Modern programming language implementations are not always purely compiler-based or purely interpreter-based.

They may use a combination of:

→ Compilation
→ Bytecode
→ Interpretation
→ JIT (Just-In-Time) Compilation

---

# 16. COMPILER vs INTERPRETER

| Compiler                                                 | Interpreter                                         |
| -------------------------------------------------------- | --------------------------------------------------- |
| Usually compiles/translates the program before execution | Processes/executes code at runtime                  |
| Can generate object/executable code                      | Usually executes code through a runtime/interpreter |
| Compiled code generally executes faster                  | Traditional interpretation can be slower            |
| Many errors can be detected during compilation           | Some errors appear during execution                 |
| Examples: C, C++                                         | Examples: Python, JavaScript                        |

---

# 17. ASCII

## ASCII → American Standard Code for Information Interchange

ASCII assigns numerical codes to standard characters.

## Important ASCII Values

```text
A → 65
Z → 90

a → 97
z → 122
```

## Ranges

```text
A-Z → 65-90

a-z → 97-122
```

Original ASCII is a **7-bit character encoding standard** and defines **128 character codes**.

---

# 18. ASSEMBLY LANGUAGE

Assembly Language is a **low-level programming language**.

## File Extension

```text
.asm
```

## Example

```asm
MOV AX, 10
ADD AX, 20
```

Assembly source code is translated into object/machine code by an **Assembler**.

## Flow

```text
Assembly Code
      ↓
Assembler
      ↓
Object Code
```

---

# 19. .OBJ → BINARY

`.obj` generally represents an **Object File**.

An object file may contain machine-level code and/or data.

## Important

`.obj` does **not necessarily mean a directly executable file**.

## Flow

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

A **Loader** loads an executable program into memory so that it can be executed.

## Windows

```text
.exe
```

## Unix / Linux

```text
a.out
```

`a.out` is a traditional executable filename used by some Unix/Linux toolchains.

## Basic Flow

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

An MCU generally integrates multiple components on a single chip:

→ CPU
→ Memory
→ I/O
→ Peripherals

## Common Uses

→ Embedded Systems
→ Sensors
→ IoT Devices
→ Robotics
→ Appliances
→ Control Systems

---

## MPU → Microprocessor Unit

An MPU generally provides the processor/core.

Depending on the system architecture, external components may be required, such as:

→ Memory
→ Peripherals
→ I/O

## Common Uses

→ General-Purpose Computing
→ Embedded Linux Systems
→ Advanced Computing Systems

---

# 22. SoC / SOC

## SoC → System on Chip

An SoC integrates multiple system components into a **single chip**.

## Possible Components

→ CPU
→ GPU
→ Memory Controller
→ I/O
→ Communication Interfaces
→ Other Peripherals

---

# 23. OTA

## OTA → Over-The-Air

OTA means updating software or firmware through a wireless/network connection.

## Flow

```text
Internet / Network
        ↓
      Device
        ↓
    OTA Update
        ↓
New Firmware / Software
```

## Common Uses

→ Smartphones
→ IoT Devices
→ Embedded Systems
→ Smart Devices
→ Vehicle Systems

---

# 24. INTERPRETER — STATIC & DYNAMIC

## Original Note

```text
Interpreter

1. Static

2. Dynamic

   (Read Real Time)
```

## Correction

**Static** and **Dynamic** are not standard two types of interpreters.

These terms are mainly used in the context of:

→ Typing
→ Analysis
→ Runtime Behavior

---

## Static

Information or analysis can be determined or checked before runtime, often during compilation.

### Static Typing

→ Type checking is mainly performed at compile time.

---

## Dynamic

Information or behavior can be determined during program execution.

### Dynamic Typing

→ Type checking is mainly performed at runtime.

---

# 25. C PROGRAM EXECUTION FLOW

## Complete Basic Flow

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

## Important Full Forms

```text
MCU   → Microcontroller Unit

MPU   → Microprocessor Unit

CPU   → Central Processing Unit

ALU   → Arithmetic Logic Unit

SoC   → System on Chip

ASCII → American Standard Code for Information Interchange

OTA   → Over-The-Air
```

---

## Electronics

```text
L → Inductor

C → Capacitor

R → Resistor
```

---

## File Extensions

```text
.asm → Assembly Source File

.obj → Object File

.exe → Windows Executable

a.out → Common Unix/Linux executable name
```

---

## ASCII

```text
A → 65

Z → 90

a → 97

z → 122
```

---

## C89/C90

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

---

# 📌 END OF NOTES