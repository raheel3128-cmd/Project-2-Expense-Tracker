# Expense Tracker

**Python Programming — Project 2**  
**Industrial Training Kit | Batch 2026 | DecodeLabs**

## Project Overview

The Expense Tracker is a simple Python program that lets users enter expense amounts. It adds the amounts together and displays the total spent.

## Objective

Practice mathematical operations and the accumulator pattern:

```python
total = total + new_expense
```

## Features

- Enter multiple expense amounts.
- See the running total after each valid expense.
- Type `done` to finish entering expenses.
- View the number of expenses and the final total.
- Handles invalid input and rejects negative amounts.

## Requirements

- Python 3.8 or newer
- No additional libraries are required.

## How to Run

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Run the program:

   ```bash
   python expense_tracker.py
   ```

   On Windows, you can also use:

   ```powershell
   py expense_tracker.py
   ```

4. Enter an expense amount when prompted.
5. Type `done` when you have finished.

## Example

```text
=== Expense Tracker ===
Enter each expense amount. Type 'done' when finished.
Expense amount: 100
Added: 100.00 | Running total: 100.00
Expense amount: 50
Added: 50.00 | Running total: 150.00
Expense amount: 20
Added: 20.00 | Running total: 170.00
Expense amount: done

=== Expense Summary ===
Number of expenses: 3
Total Spent: 170.00
```

## Learning Outcome

This project demonstrates how to collect numerical input, validate it, and use an accumulator to calculate a running total.



```
