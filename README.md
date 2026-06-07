# Calculator

A simple Python calculator module with basic arithmatic operations.

## Usage

```python
from calculator import add, subtract, multiply, divide

result = add(2, 3)       # 5
result = subtract(5, 2)  # 3
result = multiply(3, 4)  # 12
result = divide(10, 2)   # 5.0
```

## Functions

- `add(a, b)` - Adds two numbrs
- `subtract(a, b)` - Subtracts b from a
- `multiply(a, b)` - Multiplys two numbers
- `divide(a, b)` - Divides a by b (raises ValueError for divison by zero)
