[![Build Status](https://travis-ci.com/cucak559/open-source-development-course-hw02-1.svg?branch=pr%2Fstep1)](https://travis-ci.com/cucak559/open-source-development-course-hw02-1)

# Simple Vector implementation in python 

Very simple vector implementation supporting basic operations.

## Usage

```python
from ossdev import Vector, Matrix
a = Vector([0, 1, 2, 3])
print(a)

m = Matrix.ident(4)
print(m)
print(m + m)
```

Operations:
- Addition with a scalar `a+1`
- Vector addition: `a + b`
- Multiplication:
  - scalar * vector
  - row-vector * col-vector
  - col-vector * row-vector

Matrix operations:
- Addition
- Vector substraction: `a - b`
- Vector multiplication: `a * b`
- Vector xor: `a ^ b`
- Vector comapring, eg.: `a < b`
- Vector length: `a.length()`

## Installation

```bash
pip install -U --no-cache . 
```
