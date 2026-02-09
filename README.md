# SGPA Calculator (VTU)

## Description
This program calculates the **SGPA (Semester Grade Point Average)** based on the marks entered for 8 subjects.  
It follows a **credit-based grading system** similar to VTU.

The program:
- Takes marks as input
- Checks for invalid marks
- Converts marks into grade points
- Calculates SGPA
- Displays the final grade

---

## Subjects and Credits

| Subject Code | Credits |
|-------------|---------|
| BCS501 | 4 |
| BCS502 | 4 |
| BCS503 | 4 |
| BAIL504 | 1 |
| BCD586 | 2 |
| BRMK557 | 3 |
| BCS508 | 1 |
| BAI515A | 3 |

**Total Credits = 22**

---

## Grade Point System

| Marks Range | Grade Point |
|------------|-------------|
| 90 – 100 | 10 |
| 80 – 89 | 9 |
| 70 – 79 | 8 |
| 60 – 69 | 7 |
| 50 – 59 | 6 |
| 40 – 49 | 5 |
| 30 – 39 | 4 |
| 20 – 29 | 3 |
| 10 – 19 | 2 |
| Below 10 | 0 |

---

## Final Grade Based on SGPA

| SGPA Range | Grade |
|-----------|-------|
| ≥ 9.0 | A |
| ≥ 8.0 | B |
| ≥ 7.0 | C |
| ≥ 6.0 | D |
| ≥ 5.0 | E |
| < 5.0 | Fail |

---

## How the Program Works

1. The user enters marks for all 8 subjects.
2. The program checks if any mark is less than 0 or greater than 100.
3. If invalid marks are found, it prints an error message.
4. If marks are valid:
   - Each subject mark is converted to a grade point.
   - Grade points are multiplied by subject credits.
   - SGPA is calculated using the formula:
     SGPA = Total (Grade Point × Credit) / Total Credits

5. The SGPA and final grade are displayed.

---

## How to Run the Program

1. Make sure Python is installed.
2. Save the program in a `.py` file.
3. Run the file using:
   python filename.py
4. Enter the marks when prompted.

---

## Notes
- Marks must be between **0 and 100**.
- Decimal SGPA is rounded to **2 decimal places**.
- This program is suitable for **basic academic projects and practice**.

---

## Author
Student Project – SGPA Calculator using Python

   


