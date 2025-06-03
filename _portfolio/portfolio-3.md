---
title: "Data Analysis with Python"
# excerpt: "Short description of portfolio item number 1<br/><img src='/converter_3dview.png'>"
collection: portfolio
---


## Setup and Teardown

```python
import unittest

def setUpModule():
  print('setUpModule()')

def tearDownModule():
  print('tearDownModule()')

class SimpleTest(unittest.TestCase):

  @classmethod
  def setUpClass(cls):
    print('setUpClass()')

  @classmethod
  def tearDownClass(cls):
    print('tearDownClass()')

  def setUp(self):
    print('setUp()')

  def tearDown(self):
    print('tearDown()')

  def test_a(self):
    print('testA()')

  def test_b(self):
    print('testB()')

  @unittest.skip("demonstrating skipping")
  def test_c(self):
    print('testC()')
    self.fail()

if __name__ == '__main__':
  unittest.main()
```


