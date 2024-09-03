# Sorting-Algorithms
Different types of sorting algorithms. The comparison_demo.py file shows the minimum execution speed of each algorithm.

# Merge sort is a divide-and-conquer algorithm
It recursively splits the list into halves until each sublist contains a single element
Then merges those sublists back together in sorted order.

# The selection_sort algorithm
This is a simple comparison-based sorting algorithm.
It works by repeatedly finding the minimum element (considering ascending order),
from the unsorted part of the list and moving it to the beginning.

# The quick_sort algorithm
This is a divide-and-conquer algorithm that works by selecting a "pivot" element from the array
and partitioning the other elements into two sub-arrays,
according to whether they are less than or greater than the pivot. The sub-arrays are then sorted recursively.

# TimSort is a hybrid sorting algorithm
It derived from merge sort and insertion sort.
It is designed to perform well on many kinds of real-world data.
It’s actually the default sorting algorithm used in Python’s built-in sorted() function and list.sort() method.

# The "Stalin Sort" algorithm
This is a humorous and non-standard sorting algorithm that works by iterating through the list
and only keeping the elements that are in non-decreasing order.
If an element is out of order, it's "removed" from the list—hence the name, referencing Stalin's purges.
