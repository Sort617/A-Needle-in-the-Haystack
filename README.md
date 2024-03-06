
# Needle Finder Function

This repository contains a Python script designed to locate a specific element, termed 'needle', within a list. The primary focus of this utility is to demonstrate the usage of list search operations in Python.

## Functionality

The main script, `find_needle.py`, includes a function `find_needle(haystack)` that searches for the string `'needle'` in a given list `haystack`. If found, it returns a string indicating the position of `'needle'` within the list.

## Testing

The file `test_find_needle.py` contains predefined test cases for the `find_needle` function. These tests are designed to verify the accuracy of the function across various scenarios, including different list compositions and positions of `'needle'`.

### Test Execution

To run the tests, ensure you have a testing framework like `unittest` in Python. Each test case invokes the `find_needle` function with a predefined list and checks if the returned value matches the expected position of `'needle'`.

## Usage

1. Clone this repository to your local machine.
2. Ensure Python is installed on your system.
3. Run the test file to verify the functionality: `python test_find_needle.py`.

Note: Modify the test cases in `test_find_needle.py` as needed to fit your specific testing requirements.
