# COBOL Portfolio Gateway

**Author:** Hayden Schmidt

**Github:** [Haschm05](https://github.com/Haschm05/Haschm05)

---

## About Me
Welcome to my GitHub portfolio gateway! I am currently studying Computer Information Systems at Wayne State College.  
This repository serves as a central directory for my projects.

---

## Table of Contents

| Project  | TechStack | Description | Repo | Publicity
|----------|-------------|-------------|------|------|
| CALC2000 | COBOL / JCL | Calculates future investment values using compound growth and repeated doubling logic | [CALC2000](https://github.com/Haschm05/COBOL_CALC2000) | Private |
| UTIL2000 | COBOL / JCL | Calculates future value of investments for multiple individuals | [UTIL2000](https://github.com/Haschm05/COBO_UTIL2000) | Private |
| RPT2000  | COBOL / JCL | Produces a YTD sales report with year-over-year comparison and percent change calculations | [RPT2000](https://github.com/Haschm05/COBOL_RPT2000) | Public |
| RPT5000  | COBOL / JCL | Advanced reporting system with multi-level totals and control break processing | [RPT5000](https://github.com/Haschm05/COBOL_RPT5000) | Public |
| RPT6000  | COBOL / JCL | Implements table-driven processing with indexed lookups and modular design | [RPT6000](https://github.com/Haschm05/COBOL_RPT6000) | Public |
| SEQ3000  | COBOL / JCL | Maintains employee records with add, update, and delete operations | [SEQ3000](https://github.com/Haschm05/COBOL_SEQ3000) | Public |

---

**Note:** RPT3000 and IND2000 were parts of larger projects and thus not added to the final gateway

---

## CALC2000

**Description:**
A COBOL program that calculates the future value of an investment using a fixed annual interest rate over a set number of years. After the initial calculation, the program doubles the investment amount twice, recalculating the future value each time to produce three total results.

**Key Concepts:**
- Compound interest calculations
- Iterative processing
- Arithmetic operations in COBOL
- Sequential output generation

**Language(s):**
COBOL / JCL

**Status:**
Complete

[Table of Contents](#table-of-contents)

---

## UTIL2000

**Description:**
A COBOL program that calculates the future value of investments for multiple individuals. The program processes three separate inputs and generates future value calculations for each.

**Key Concepts:**
- Repetitive financial calculations
- Multi-record processing
- Input/output handling
- Basic report-style output

**Language(s):**
COBOL / JCL

**Status:**
Complete

[Table of Contents](#table-of-contents)

---

## RPT2000

**Description:**
A COBOL reporting program that analyzes customer sales data by calculating year-over-year changes in both dollar amount and percentage. The program generates a structured report containing detailed customer and sales information.

**Key Concepts:**
- Arithmetic computations (difference and percentage change)
- Report generation and formatting
- Working storage and data movement
- Structured output design

**Language(s):**
COBOL / JCL

**Colaborator(s):**
Grant Peverett

**Status:**
Complete

[Table of Contents](#table-of-contents)

---

## RPT5000

**Description:**
A COBOL program that generates a detailed Year-To-Date (YTD) Sales Report. It calculates sales differences and percentage changes while producing structured summaries at the sales representative, branch, and overall levels.

**Key Concepts:**
- Multi-level control break processing
- Accumulation of totals (Salesrep, Branch, Grand)
- Arithmetic computations (difference and percentage change)
- Structured report formatting
- Sequential file processing

**Language(s):**
COBOL / JCL

**Colaborator(s):** 
Jacob Schamp

**Status:**
Complete

[Table of Contents](#table-of-contents)

---

## RPT6000

**Description:**
An advanced COBOL reporting system that builds upon RPT5000 by introducing table-driven processing, modular design, and dynamic data lookups. The program generates a comprehensive YTD Sales Report with enhanced formatting and data handling capabilities.

**Key Concepts:**
- Table processing with indexed access
- REDEFINES for flexible data structures
- Modular programming using COPY libraries
- Dynamic data loading and lookup
- Multi-level control break reporting
- Special value handling (N/A, overflow conditions)

**Language(s):**
COBOL / JCL

**Colaborator(s):** 
Violet French

**Status:**
Complete

[Table of Contents](#table-of-contents)

---

## SEQ3000

**Description:**
A COBOL-based employee file maintenance system that processes sequential transaction records to update a master employee file. The program applies add, change, and delete operations while generating both an updated master file and an error file for invalid transactions.

**Key Concepts:**
- Sequential file processing
- Balanced-line processing
- Multi-file input/output handling
- Transaction-based record updates (Add, Change, Delete)
- Error handling and validation
- File sorting and merge preparation
- Introduction to indexed file concepts (VSAM)

**Language(s):**
COBOL / JCL

**Status:**
Complete

[Table of Contents](#table-of-contents)
