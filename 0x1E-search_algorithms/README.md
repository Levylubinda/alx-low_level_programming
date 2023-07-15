More Info
You will be asked to write files containing big O notations. Please use this format:

O(1)
O(n)
O(n!)
n*m -> O(nm)
n square -> O(n^2)
sqrt n -> O(sqrt(n))
log(n) -> O(log(n))
n * log(n) -> O(nlog(n))
Types of Search Algorithms
In this post, we are going to discuss two important types of search algorithms:

Linear or Sequential Search
Binary Search
Let's discuss these two in detail with examples, code implementations, and time complexity analysis.

Linear or Sequential Search
This algorithm works by sequentially iterating through the whole array or list from one end until the target element is found. If the element is found, it returns its index, else -1.

Now let's look at an example and try to understand how it works:

arr = [2, 12, 15, 11, 7, 19, 45]
Suppose the target element we want to search is  7.

Approach for Linear or Sequential Search
Start with index 0 and compare each element with the target
If the target is found to be equal to the element, return its index
If the target is not found, return -1
Code Implementation
Let's now look at how we'd implement this type of search algorithm in a couple different programming languages.

Linear or Sequential Search in Java…
