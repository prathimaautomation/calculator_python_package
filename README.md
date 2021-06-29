# This package is for simple calculations addition, substraction, multiplication, division

- code for calculator.py
```python
class SimpleCalc:

    def add(self, num1, num2):
        return num1 + num2

    def subtract(self, num1, num2):
        return num1 - num2

    def multiply(self, num1, num2):
        return num1 * num2

    def divide(self, num1, num2):
        return num1 / num2

```
- code for program.py
```python
from app.calculator import SimpleCalc

calc = SimpleCalc()

print(calc.multiply(2,3))
print(calc.add(5,8))
print(calc.divide(10, 5))
print(calc.subtract(19, 5))
```
- pip install . to install our package using pip package manager
