InsertionMergeHeapSort Summary:

A sorting exercise using insertion, merge, and heap sorting functions to compare sort times. The classes are set up to analyze big O performance.

This assignment was mediated by the professor of the class (Dr. Gerry Howser) who aided with the coding at varying points. 


The classes are described in detail below

CorrectnessTest: an algorithm that checks to make sure a list is sorted, numerically speaking.

HeapSort: a recursive, sorting funtion that treats an arraylist as a binary tree and sorts it in reverse order from the middle of the list to the top. The idea is that for any given node n that is less than half the size of the arraylist there are two children nodes 2n and 2n+1 that are uniquely the children of n. As the sort gets closer to the root, the recursive function is called increasingly more as the children nodes have children nodes and so on and so forth. Eventually, one last recursion goes through the entire arraylist and the it emerges on the other side completely ordered.

HeapTesterMain: tests the HeapSort class for correctness (to ensure the arraylist was sorted) and runs the sort on varying arraysizes 75,000 through 675,000 in steps of 75,000.

InsertionSort: a sorting function that runs through an array linearly and inserts numbers into their correct spot in the sorted list. It sorts from the front to the back of the arraylist, causing the front of the list to become sorted and leaving the back unordered as the function runs its course.

InsertionTesterMain: tests the InsertionSort class for correctness and runs the sort on varying arraysizes 25,000 through 225,000 in steps of 25,000.

MergeSort: a sorting function that recursively divides the list size in half until there is only one node in each list. It uses a queue structure to join each pair of nodes together into one sorted queue and that proceeds until every node has been recombined into one sorted list.

MergeTesterMain: tests the InsertionSort class for correctness and runs the sort on varying arraysizes 25,000 through 225,000 in steps of 25,000.
