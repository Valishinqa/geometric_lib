# Geometric library
The project provides simple functions for calculating the area and perimeter of a circle and square.

## Functions
### The module circle.py
- area(r): Calculates the area of a circle based on radius r.
- perimeter(r): Calculates the length of a circle based on the radius r.

### The module square.py
- area(a): Calculates the area of a square with side a.
- perimeter(a): Calculates the perimeter of a square with side a.

## Examples
### The module circle.py
```python
 radius = 5
 print(f"The area of the circle: {area(radius)}") # Output: 25 * Pi (~78.5)
 print(f"Circle length {perimeter(radius)}") # Output: 10 * Pi (~31.4)
```
### The module square.py
```python
 side = 4
 print(f"Square area: {area(side)}") # Output: 16
 print(f"The perimeter of the square: {perimeter(side)}") # Output: 16
```

## Math formulas
### Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

### Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

## Commit History

### [c6ee140](https://github.com/username/repo/commit/c6ee140ab7b11f3845986e5090a46edba6fb941b) - Fix examples of function calls

### [b6a3f60](https://github.com/username/repo/commit/b6a3f6012e66e2da3ad9e5299260b0ccce24d03a) - Add examples of function calls

### [f1afd01](https://github.com/username/repo/commit/f1afd01d6e9883fd15afb087f20b075729363279) - Update README.md
- Added a description of the functions to the documentation
- Updated the structure README.md

### [c1863f8](https://github.com/username/repo/commit/c1863f8a210d7248a1b896a60e9fa2b057089b2a) - Add documentation
- Added documentation to `circle.py `
- Added documentation to `square.py `