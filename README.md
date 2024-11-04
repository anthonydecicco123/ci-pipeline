# ci-pipeline
git clone https://github.com/YOUR_USERNAME/ci-pipeline.git
cd ci-pipeline
# hello.py
def greet():
    return "Hello, World!"
# test_hello.py
import unittest
from hello import greet

class TestGreet(unittest.TestCase):
    def test_greet(self):
        self.assertEqual(greet(), "Hello, World!")

if __name__ == "__main__":
    unittest.main()
git add .
git commit -m "Add hello.py and test_hello.py"
git push origin main

