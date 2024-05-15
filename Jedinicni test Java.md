Pisano u VSCode u Python jeziku.

1. Pravimo fajl calculator.py i sadrzi:

class Calculator:
    def calculate(self, a, b):
        return a + b

2. Pravimo drugi fajl calculator_test.py i sadrzi:

import unittest
from calculator import Calculator

class TestCalculator(unittest.TestCase):
    def test_calculate(self):
        calculator = Calculator()
        result = calculator.calculate(2, 3)
        self.assertEqual(result, 5)

if __name__ == '__main__':
    unittest.main()



3. U terminalu navigiramo do foldera gde su fajlovi, u mom slucaju cd C:\Users\Max\Downloads\Calculator i pokrecemo sledecu komandu:

python calculator_test.py

4. Rezultat:

.
----------------------------------------------------------------------
Ran 1 test in 0.001s

OK

