# Messy Python Code Improvement

A small Python project refactored using Cursor AI to improve readability while preserving the original output.

## Features

- Calculates the average of scores after the first skipped value
- Counts how many scores are above the calculated average
- Uses descriptive names, constants, functions, docstrings, and f-strings
- Preserves the original program output

## Requirements

- Python 3

## Run

```bash
python messy.py
```

## Expected Output

```text
Average: 80.0
Above average: 1
```

## How It Works

The first value in the list is skipped using the `SKIPPED_ITEMS` constant. The program then calculates the average of the remaining values and counts how many are greater than that average.

## Files

- `messy.py` — Refactored Python program
- `original_output.txt` — Reference output saved before refactoring
