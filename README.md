# grades-manager-c

Tiny CS1-style program to store students and grades.

**Features**
- Add students and attach grades
- Search by name, list all students
- Compute per-student and class averages
- Dynamic array (malloc/realloc)

## Build & run
```bash
# macOS/Linux (gcc/clang):
gcc -Wall -Wextra -O2 -o grades_manager grades_manager.c
./grades_manager

# Windows (MinGW):
# gcc -Wall -Wextra -O2 -o grades_manager.exe grades_manager.c
# .\grades_manager.exe

## Sample Run

```text
--- Grades Manager ---
1) Add student
2) Add grade to student
3) Show student by name
4) List all students
5) Class average
0) Quit

Choice: 1
Student name: Aiden

Choice: 1
Student name: Alice

Choice: 2
Student name: Aiden
Grade (0-100): 77

Choice: 2
Student name: Alice
Grade (0-100): 92

Choice: 4
Aiden: 77 (avg: 77.00)
Alice: 92 (avg: 92.00)

Choice: 5
Class average: 84.50

Choice: 0
Goodbye!
