=== BINARY SEARCH ===

Binary search is a search algorithm that divide and conquer the problem into smaller chunks.
Binary search and many search algorithm only works if the data is already sorted.

#### How it Works
1. The algorithm determine the first element and the last element of an array
2. Then it'll pick a point in the middle
3. Check if the middle point is equal, smaller, or bigger than the target
4. if the middle is equal to the target, return the item to the output
5. if the middle is smaller than the target, move the first element into middle + 1
6. if the middle is bigger than the target, move the last element into middle - 1
7. repeat the 5th or 6th step until the algorithm find the target

