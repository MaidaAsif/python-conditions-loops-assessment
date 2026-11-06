# Python Conditions & Loops Assessment

## Overview
This repository contains two beginner-friendly Python programs that demonstrate conditional statements and loop structures using real-world scenarios.

| File | Topic |
|------|-------|
| `student_scholarship_system.py` | Conditional statements (`if`, `elif`, `else`) |
| `pharmacy_inventory_system.py` | Loops (`for`, `range()`), counters, accumulators |

## Task 1: Student Scholarship Eligibility System

Evaluates whether a student qualifies for a university scholarship.

**Input:** name, academic marks, attendance percentage, monthly family income.

**Eligibility criteria:**
- Marks of at least 80%
- Attendance of at least 85%
- Monthly family income of Rs. 50,000 or less

**Result:**
- All criteria met and marks of 90% or above: **Full Scholarship**
- All criteria met and marks between 80% and 89%: **Partial Scholarship**
- Otherwise: **Not Eligible**, with every failed criterion listed as a reason

## Task 2: Smart Pharmacy Inventory & Sales Management System

Processes medicine sales and calculates daily revenue.

**Input:** number of medicines, then for each one: name, available stock, price per unit, quantity sold.

**Features:**
- Checks that the requested quantity is available in stock
- Calculates the sale amount and remaining stock for each medicine
- Shows a low-stock warning when remaining stock is below 10 units
- Tracks total revenue with an accumulator
- Counts medicines that need restocking
- Prints a final report with medicines processed, total revenue, and restock count

**Design choice:** a rejected sale (quantity greater than stock) is not counted as processed and adds nothing to revenue.

## Python Concepts Used
- Variables, `input()`, `print()`, and f-strings
- Arithmetic operators
- Conditional statements: `if`, `elif`, `else`
- `for` loop with `range()`
- `while` loops for input validation
- `try` / `except` for handling invalid values
- Lists and `append()`
- Accumulator (`total_revenue`) and counters (`processed`, `restock`)
- `continue` to skip a rejected sale
- Functions with parameters and return values
