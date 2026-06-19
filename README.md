# Interpolation Search Analysis

## Overview

This project implements the **Interpolation Search** algorithm in Python and compares its performance with **Binary Search** on sorted datasets of different sizes.

Interpolation Search is an improved searching technique for uniformly distributed sorted data. Instead of always checking the middle element like Binary Search, it estimates the likely position of the target using an interpolation formula.

## Features

* Implementation of Interpolation Search
* Implementation of Binary Search for comparison
* Comparison of execution times
* Comparison of number of comparisons performed
* Performance analysis on datasets of varying sizes

## Algorithms Used

### Interpolation Search

* Average Time Complexity: **O(log log n)**
* Worst Case Time Complexity: **O(n)**
* Space Complexity: **O(1)**

### Binary Search

* Time Complexity: **O(log n)**
* Space Complexity: **O(1)**

## Dataset Sizes Tested

* 1,000 elements
* 5,000 elements
* 10,000 elements
* 50,000 elements
* 100,000 elements

## Sample Output

```text
Array: [2, 5, 10, 15, 23, 35, 48, 60, 75, 90, 105, 120]
Searching for: 35
Found at index: 5, Comparisons: 2
```

## How to Run

```bash
python interpolation_search.py
```

## Learning Objectives

* Understand the working of Interpolation Search
* Compare search algorithms on large datasets
* Analyze time complexity and performance
* Explore algorithm efficiency on uniformly distributed data

## Author

Manha Tabassum Tajudeen

Computer Science Engineering Student
