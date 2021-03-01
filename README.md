# Sorting

You will implement the merge and quick sort algorithms.

**Learning Objectives:**

1. understand how merge sort and quicksort work
1. practice recursion
1. practice using property-based tests

**Real-world application:**
Given a dataset, the first step of processing is almost always to sort the data.
This allows efficient lookups via binary search,
but it even makes sequential search significantly faster due to an optimization in modern CPUs called "branch prediction".
(See [the most upvoted stackoverflow question of all time](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array) for details.)

In the real world, you will never implement your own sorting algorithm,
and will always use a built-in library routine.
But it is still important to understand how they work in order to select which algorithm to use.

## Tasks

Complete the following tasks:

1. Fork the [sorting repo](https://github.com/mikeizbicki/sorting) and enable github actions
1. Update the `README.md` file so that the travis button points to your repo
1. Implement the `_merged`, `merge_sorted`, and `quick_sorted` functions so that all test cases in `tests/test_main.py` pass.
   You must implement `merge_sorted` and `quick_sorted` recursively.
1. (optionally)
   You can receive 1 point of extra credit for implementing the `quick_sort` function and passing the tests in `tests/test_ec.py`.

## Submission

Submit the link to your forked repository on sakai.

## Collaboration Policy

**You are not allowed to look at another student's github repo.**

All other forms of collaboration with other students are encouraged.
You may use any other online resources you like to complete this assignment.
