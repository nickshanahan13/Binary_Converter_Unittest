# Binary Converter Unittest

```python
#!/usr/bin/env python3

import unittest

from numberToBinary import to_binary

class TestBinary(unittest.TestCase):
    def test_basic(self):
        test_n = 13
        expected = bin(1101)[2:]
        self.assertEqual(to_binary(test_n), expected)

unittest.main()
```
