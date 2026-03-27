# Collatz Library
**Programmer:** Vansh Raj

A specialized Python library designed to simplify Collatz Conjecture calculations and visualizations. This library eliminates the need to write complex logic from scratch, allowing you to solve sequences and trees with simple functions.

## Goal
To provide an efficient toolkit for Collatz Conjecture solvers. This library includes functions for:
* `seq`: Generate the Collatz sequence.
* `ocn`: Opposite number count.
* `dcn`: Division count in a sequence.
* `mcn`: Multiplication count in a sequence.
* `inct`: Generate a full Inverse Collatz Tree.

## Installation
You can run this library across various environments:
* **Python Codepad:** Recommended for visualizing the **Inverse Collatz Tree**.
* **Pydroid 3:** Best for mobile development and general library usage.
* **Any Python Compiler:** Works with standard Python 3.x setups.

## How it Works
The library is built using **Python**. It uses optimized iterative and recursive logic to handle sequence generation and tree mapping, ensuring the output is structured and easy to read.

## Usage
After downloading the `collatz` library files to your directory, you can use it as follows:

```python
import collatz

# Generate a sequence for the number 5
print(collatz.seq(5))

# Output: 5, 16, 8, 4, 2, 1
