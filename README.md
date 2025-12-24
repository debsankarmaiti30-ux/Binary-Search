# Binary-Search

Introduction

Binary Search is an efficient searching algorithm used to find the position of a target element in a sorted array. It works by repeatedly dividing the search interval in half, significantly reducing the number of comparisons.

⚙️ How Binary Search Works

Start with two pointers:

low at the beginning of the array

high at the end of the array

Find the middle element:

mid = (low + high) / 2

Compare the middle element with the target:

If equal → element found

If target is smaller → search the left half

If target is larger → search the right half

Repeat until the element is found or the search space becomes empty.

✅ Prerequisites

The array must be sorted (ascending or descending).

Random access to elements (works best with arrays).

⏱️ Time & Space Complexity
Case	Time Complexity
Best Case	O(1)
Average	O(log n)
Worst Case	O(log n)

Space Complexity

Iterative approach: O(1)

Recursive approach: O(log n)

📌 Applications

Searching in large sorted datasets

Used in databases and libraries

Finding lower and upper bounds

Competitive programming problems

❌ Limitations

Does not work on unsorted arrays

Inefficient for small datasets compared to linear search

Requires random access (not suitable for linked lists)
