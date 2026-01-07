# Python Code Readability Dataset Generator

## Overview

This project generates a labeled dataset of Python code snippets classified as **readable** or **unreadable**. The output is intended for machine learning experiments, research, and tooling related to code quality and readability.

The dataset is created programmatically to ensure variation, consistency, and scalability.

---

## What the Notebook Does

* Stores examples of readable and unreadable Python code
* Groups unreadable code by common problem types
* Randomizes code to increase dataset diversity
* Assigns readability labels
* Removes duplicate samples
* Exports the final dataset as a CSV file

---

## Dataset Format

The generated CSV file contains the following columns:

| Column  | Description                                      |
| ------- | ------------------------------------------------ |
| `code`  | Python code snippet                              |
| `label` | Readability label (1 = readable, 0 = unreadable) |

---

## Readable vs Unreadable Code

**Readable code** follows common best practices such as:

* Clear indentation
* Descriptive variable and function names
* Simple and understandable logic

**Unreadable code** simulates poor practices, including:

* Inconsistent indentation
* Unclear or misleading naming
* Overly complex or confusing logic
* Invalid or misleading syntax patterns

---

## How to Run

### Requirements

* Python 3.8 or higher
* Jupyter Notebook or Google Colab

### Dependencies

```
pandas
```

### Steps

1. Open `main.ipynb`
2. Run all cells in order
3. The dataset will be saved as `python_code_readability_dataset.csv`

---

## Use Cases

* Code readability classification
* Static analysis experiments
* AI-assisted code review tools
* Educational examples for code quality

---

## Notes

* All code samples are synthetically generated
* No proprietary or real-world source code is included
* The dataset is suitable for experimentation and research

---

<div align="center">

© johnbrainarddelacruz 2025

</div>
111
