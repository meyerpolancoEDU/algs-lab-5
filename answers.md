# CMPS 2200 Reciation 5
## Answers

**Name:**Meyer Polanco


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
If the input list is sorted, fivet-pivot increases in runtime at a extremely superlinear rate as we would expect from an algorithm with a asymptotic runtime of O(n^2). ssort also increases at a similar rate due to its O(n^2) runtime. random-pivot on the other hand increase only slightly more than a linear increase, which conforms to the expected runtime of the alogrithm O(nlogn). However, if the input list is unsorted, we avoid the worst case for the fixed-pivot algorithm, so the observed runtime ends up being very similar to random-pivot, which is effectively the same in either case. Both end up being ~O(nlogn). But, ssort does not benefit from this improvement in runtime because it still needs to look through the entire list regarless of the format of the list. So its runtime remains ~the same for sorted and unsorted lists.



- **1c.**
The runtime of tim-sort, in both the sorted and unsorted cases, is far faster than both qsort implementations. In the sorted case it is ~170 times faster than random-pivot on a list of size 5000. In the unsorted case it is ~10 times fater than fixed-pivot (which is itself marginally faster than random-pivot) on a list of size 5000.
